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

# Dashboard Notes:
<i>Along with learning to import data from an external source and create various visualizations. This project was also to practice customizing those visualizations.</i>

Each borough as their own separate dashboard.  Borough dashboards consists of donut charts and bar charts

You’ll find pie charts and donut charts showing the distribution of sales across different products and countries, clustered coulmn charts and Area Chart depicting year-wise sales trends, and much more. The dashboard is interactive and customizable, allowing you to filter the data by Year, Quarter, Month, and Product to suit your needs.
1.	Total Sales by Product: This donut chart shows the distribution of total sales across different products. It helps in understanding which product contributes more to the total sales.
2.	Total Sales by Country: This donut chart provides information about the total sales in different countries. It helps in identifying the countries contributing most to the sales.
3.	Year-wise Total Sales by Product: This clustered column chart shows the total sales by product for each year. It helps in understanding the trend of sales for each product over the years.
4.	Year-wise Total Sales by Country: This Area chart provides the total sales by country for each year. It helps in understanding the trend of sales in each country over the years.
5.	Total Sales For Discount Brands: This pie chart shows the total sales for discount brands. It helps in understanding the contribution of discount brands to the total sales.
6.	Total Sales by Segment: This pie chart shows the total sales by segments like Enterprise, Government, and Small Business. It helps in understanding the contribution of each segment to the total sales.
These charts provide a comprehensive view of the sales data and can be customized using the filters for Year, Quarter, Month, and Product.
I believe this dashboard will serve as a powerful tool for data-driven decision making and I look forward to hearing your feedback. Please feel free to share your thoughts and suggestions.


#### To help with the intial analysis we used software for get a visual of the dataset tables and how they relate to each other.
![Table Relationships](https://github.com/julyndav/AtliQ-Hardware/blob/main/Analysis%20Images/Database%20flowchart.png)

<br></br>

## Analysis Steps:
| Step |Description |
| --- | --- |
| 1 | Create project decomposition plan |
| 2 | Connect to SQLite database |
| 3 | Import libraries |
| 4 | Upload and review the data |
| 5 | Geographic segmentation |
| 6 | Customer segmentation and analysis |
| 7 | Sales Analysis |
| 8 | Customer to Products Analysis |
| 9 | Cohort Analysis along with Customer Churn Rate |
| 10 | Project Conclusion(s) |
| 11 | Project citation of sources |

<br></br>

## AtliQ Project Analysis Plan 

The TTWC team assigned to AtliQ will conduct the necessary research, and create informative dashboards that AtliQ will be able to use later. Certain sections of the TTWC team will select one of the three above areas to focus on. My team is responsible for Customer Analysis. 

During the Customer Analysis, customer segmentation will be used to understand the purchasers and gain an understanding on more effective sales, marketing, and personalization strategies. Each segment can answer a myriad of questions that the company may have. To further help with the segmentation, we will connect the customers to the products and sales data to give a better overview of the customer focused analysis.  

To really embrace the real-world feel and to set good habits, the decomposition plan was created as if I was an actual Analyst for TTWC.  Below is a snippet of the decomposition plan, you can see the entire plan from the link in the Table of Contents. 
