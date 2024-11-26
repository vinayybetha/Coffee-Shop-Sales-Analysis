
# Coffee Shop Sales Analysis

Project Overview

Developed a Power BI project focused on analyzing sales data for a coffee shop. The project aims to construct a comprehensive dashboard that provides actionable insights into various aspects of sales performance, including total sales, order analysis, sales trends by time and location, and product performance.





Problem Statement


 The coffee shop is struggling to understand its sales performance. The specific areas of concern include:

•	Total sales analysis

•	Total order analysis

•	Total quantity sold analysis

•	Sales analysis by weekdays and weekends

•	Sales analysis by store location

•	Daily sales with average line

•	Sales analysis by product category

•	Top 10 products by sales

•	Sales analysis by days and hours

•	The goal is to analyze these aspects to identify key drivers of sales and areas for improvement.
## Tools Used

•	MySQL: For storing and querying sales data.

•	Excel: For initial data cleaning and preparation.

•	Power BI: For data visualization and exploratory data analysis (EDA).



## Data Source

MySQL Database: Contains sales data with columns including date, product, location, sales amount, quantity sold, order ID, etc.

Excel Files: Used for additional data preparation and cleaning tasks.

## Data Cleaning and Analysis

Data cleaning was performed in Excel and transformed into power bi power query to ensure data integrity and consistency.

Excel

•	Changing Data Types: Ensured that numeric columns (e.g., sales amount, quantity sold, order ID) were set to appropriate numeric data types.

•	Replacing Null Values: Applied methods such as filling with mean/median for numeric fields.

•	Formatting Cells: Ensured proper formatting for columns, such as setting number formats with appropriate decimal places.

•	Handling Missing Values: Used Excel functions to fill or remove missing data.

•	Categorizing Products and Locations: Ensured consistent labeling for products and locations.
•	Standardizing Date Formats: Used Excel functions to convert date columns to a consistent format.


Power BI

•	Data Modeling: Created a date table and connected it with the transaction table using the date column as the common key. This allows for time-based analysis and filtering in the dashboard.

•	Conditional Formatting: Used conditional formatting to highlight important data points and trends in the visualizations.

•	Data Validation: Implemented data validation rules to ensure data quality and accuracy.

•	Data Transformation: Utilized Power Query Editor to perform data cleaning operations such as removing duplicates, filtering rows, and transforming data types.

## Visualization Used in Power BI


•	Total Sales Analysis: Card and line chart to visualize total sales over different time periods.

•	Total Order Analysis: Card and line chart to show the number of orders over different time periods.

•	Total Quantity Sold Analysis: Card and line chart to display the total quantity of products sold.

•	Sales Analysis by Weekdays and Weekends: pie chart to compare sales on weekdays versus weekends.

•	Sales Analysis by Store Location: Bar chart to show sales performance by location.

•	Daily Sales with Average Line: Column chart with an average line to show daily sales trends.

•	Sales Analysis by Product Category: Bar chart to display sales distribution across different product categories.

•	Top 10 Products by Sales: Bar charts to highlight the top 10 products based on sales.

•	Sales Analysis by Days and Hours: Matrix chart to analyze sales performance across different days and hours.

•	Calendar map for monthly and daywise: Matrix chart used to filter analysis based on month and day.

•	Tooltip in calender map and days & hours chart Implemented tooltip for the calendar map and matrix chart to display detailed information when hovering over each day and hour for analysis.

## Exploratory Data Analysis (EDA)

•	What are the total sales and sales trends over different time periods?

•	How do the total orders and quantity sold vary over time?

•	What are the sales patterns on weekdays versus weekends?

•	How does sales performance vary across different store locations?

•	What are the daily sales trends, and how do they compare to the average sales?

•	Which product categories contribute the most to sales?

•	Which are the top 10 products by sales?

•	How does sales performance vary by days and hours?

## Dashboard Result

![App Screenshot](https://github.com/vinayybetha/Coffee-Shop-Sales-Analysis/blob/main/Coffee%20Shop%20Sales%20Analysis.PNG?raw=true)






## Recommendations

Based on the analysis, the following insights and recommendations were derived:

•	Optimize Product Mix: Focus on high-performing products and consider phasing out or improving low-performing products.

•	Enhance Location Performance: Identify locations with lower sales and analyze factors contributing to underperformance.

Implement targeted strategies to boost sales in these locations.

•	Weekday vs. Weekend Promotions: Leverage sales patterns to design promotions and marketing campaigns tailored for weekdays and weekends.

•	Time-Based Marketing: Utilize insights from daily and hourly sales analysis to optimize opening hours and schedule targeted promotions.

•	Customer Preferences: Use product sales data to understand customer preferences and tailor offerings accordingly

## Conclusion


The Coffee Shop Sales Analysis dashboard provides valuable insights into the sales performance of the coffee shop. By understanding key metrics and trends, the company can make data-driven decisions to enhance sales strategies, improve product offerings, and optimize overall performance.