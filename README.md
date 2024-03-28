# NYC_Dog_Bite_Analysis
I am happy to share my first Power BI project: a dynamic and interactive Dashboard for Dog bite data from various New York city boroughs! The time frame for the data covers 2015 through 2021.  

The initial dataset for this analysis was cleaned using the Kaggle platform then imported into PowerBI. There is a link to the Kaggle analysis below.  There is also a link to the original dataset from the New York Open Data website (the dataset is continually being updated.

This dashboard provides a comprehensive view of the data broken down by Borough with an overall view, key metrics and visualizations that offer valuable insights.  

You’ll find pie charts and donut charts showing the distribution of sales across different products and countries, clustered coulmn charts and Area Chart depicting year-wise sales trends, and much more. The dashboard is interactive and customizable, allowing you to filter the data by Year, Quarter, Month, and Product to suit your needs.

## Table of Contents:
[Kaggle Analysis w/dataset](https://www.kaggle.com/code/julyndav/ny-dog-bite-analysis-visualizations)

[New York Open Data](https://data.cityofnewyork.us/Health/DOHMH-Dog-Bite-Data/rsgh-akpg/about_data)



## Required Project Libraries:
| Library |Purpose |
| --- | --- |
| SQLite3 | Allows connection to external database files |
| Pandas| Main library for working with data |
| Numpy | Used for numerical operations on large quantities of data |
| Seaborn | Python visualization library based on matplotlib |
| Matplotlib | Python visualization library |
| DateTime | Manipulating data in to date/time formats |
| Pathlib | To transfer dataframes into csv files for export and use with Tableau |
| ipython-sql | Use sql within the Jupyter environment |

<br></br>


# AtliQ Hardware Project Overview:
## Description of Data: 
This is an overview of the database tables used for Analysis. Note that since this analysis is customer focused, some of the tables will not be used. 
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