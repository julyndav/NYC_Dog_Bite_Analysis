# NYC_Dog_Bite_Analysis
I am happy to share my first Power BI project: a dynamic and interactive Dashboard for Dog bite data from various New York city boroughs. The time frame for the data covers 2015 through 2021.  

The initial dataset for this analysis was cleaned using the Kaggle platform then imported into PowerBI. There is a link to the Kaggle analysis below. There is also a link to the original dataset from the New York Open Data website (the dataset is continually being updated).

This dashboard provides a comprehensive view of the data broken down by Borough with an overall view, key metrics and visualizations that offer valuable insights.  


## Table of Contents:
[Kaggle Analysis w/dataset](https://www.kaggle.com/code/julyndav/ny-dog-bite-analysis-visualizations)

[New York Open Data](https://data.cityofnewyork.us/Health/DOHMH-Dog-Bite-Data/rsgh-akpg/about_data)



## Dog Bite Data Variables:
| Variable |Purpose |
| --- | --- |
| UniqueID| Unique dog bite case identifier |
| DateofBite| Date bite took place |
| Species | Type of animal |
| Breed | Breed of dog |
| Age | Age of dog at time of bite |
| Gender | Gender of dog |
| SpayNeuter | Whether reproductive organs have been removed |
| Borough | New York City neighborhood/borough that bite took place in |
| ZipCode |Zip code bite took place in |

<br></br>


# Project Overview:
## Data Notes: 
* Ages with value of 0 were kept for the analysis. Zero age would be valid to keep in cases where the dog was a stray, or ran off after the bite incident.
* Bite Month and Bite Year columns were added to the data set to aid in analysis.

## Dashboard Notes:
<i>Along with learning to import data from an external source and create various visualizations. This project was also to practice customizing those visualizations.</i>

There is a main landing page/home page where an individual borough can be selected. The overview option shows various KPI's and other bite trends. 
Each borough as their own separate dashboard. Borough dashboards consists of donut charts and bar charts. Clicking a variable on either bar chart will filter the other visuals within the page.
![Dashboard Homescreen](https://github.com/julyndav/NYC_Dog_Bite_Analysis/blob/main/Images/HomeScreen.png)

### Borough Dashboards
1.	Spayed/Neutered Percentage: This donut chart shows the distribution of total sales across different products. It helps in understanding which product contributes more to the total sales.
2.	Gender Percentage: This donut chart provides information about the total sales in different countries. It helps in identifying the countries contributing most to the sales.
3.	Bites per Year: This clustered column chart shows the total sales by product for each year. It helps in understanding the trend of sales for each product over the years.
4.	Top 8 Dog Breeds: This Area chart provides the total sales by country for each year. It helps in understanding the trend of sales in each country over the years.

### Overview Dashboard   
6.	Total Sales For Discount Brands: This pie chart shows the total sales for discount brands. It helps in understanding the contribution of discount brands to the total sales.
7.	Total Sales by Segment: This pie chart shows the total sales by segments like Enterprise, Government, and Small Business. It helps in understanding the contribution of each segment to the total sales.
These charts provide a comprehensive view of the sales data and can be customized using the filters for Year, Quarter, Month, and Product.
I believe this dashboard will serve as a powerful tool for data-driven decision making and I look forward to hearing your feedback. Please feel free to share your thoughts and suggestions.


These charts provide a comprehensive view of the sales data and can be customized using the filters for Year, Quarter, Month, and Product.
I believe this dashboard will serve as a powerful tool for data-driven decision making and I look forward to hearing your feedback. Please feel free to share your thoughts and suggestions.



