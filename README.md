# Real Estate Sale Data Analysis 
This project aims to analyze the real estate sale data from 1999 to 2021 in the United States and solve the following **business questions**:
* The trends in real-estate assessed value and sale amount by years
* The trends in real-estate assessed value, sale amount and the ratio by different towns. Which towns have the most valuable properties and properties that have the best growth potential?
* How the sales in real estate market affected by the residental type and the property type?
## Data 
The dataset was released by the office of Policy and Management in the United States. The data shows a listing of all real estate sales with a sales price of $2,000 ot above. 
## Build With
* PySpark
* PowerBI
## Roadmap
* [PySpark](https://github.com/Ruiqi-Alaina/Real-Estate-Sale-1999-2021-Data-Analysis/blob/main/real%20estate%20sale%20data%20in%20us.ipynb)<br>
  PySpark was utilized to preprocess data and calculate relevant statistics. At first, we checked the missing values and dropped attributes which have over 70% missing values. Then we dropped some instances which have
  sale prices less than 2000 dollars. This might be caused by misrecording. When it comes to property type and residential type,
  we cloud find some values of the property type are wrongly replaced by the residental type and vice versa. For single/two/three/four family under property type, we should replace them with 'residential'. And for 'condo' under residental type should be filled with NULL. Another point that needs to be aware of is the null values in 'Residential Type' are caused by their corresponding 'Property Type'.
 Moreover, the schema of some of the attibutes was changed for further data analysis. Finally, some statistics were computed for answering the business questions.
* [PowerBI dashboard PDF](https://github.com/Ruiqi-Alaina/Real-Estate-Sale-1999-2021-Data-Analysis/blob/main/Real%20estate%20sale%20data%20analysis.pdf)
* [PowerBI dashboard PBIX](https://github.com/Ruiqi-Alaina/Real-Estate-Sale-1999-2021-Data-Analysis/blob/main/Real%20estate%20sale%20data%20analysis.pbix)
  <br>Present the results in dashboard for stakeholders
## Conclusion
* Both assessed value and sale amount increase as year goes by. And real-estate market is to some extent underestimated which can be indicated by comparing the assessed value and sale amount especially in 2020, 2021.
* Trends in real-estate assessed value and sale prices were clearly demonstrated in the Power BI dashboard. We **calcuated the growth rate in sale prices** and found the **top 5** towns with best growth potiential are Windsor, North Stonington, North Haven, Willington and Roxbury.
* Single Family has the biggest demand in residential properties following by Four Family.
* Properties for industry have the highest median price which are almost twice the value of commecial properties and apartments.
