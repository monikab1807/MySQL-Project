# Walmart Sales
This project focuses on analyzing Walmart’s sales data to gain a deeper understanding of the performance of various branches and products. By examining key metrics such as sales figures, product categories, and customer behavior, the project aims to identify the top-performing branches and products across different regions. The analysis also explores sales trends, highlighting fluctuations and patterns in consumer demand for specific products over time. Additionally, it investigates customer purchasing behaviors to understand preferences, buying patterns, and seasonal trends. The ultimate goal of this project is to provide actionable insights that can help optimize Walmart's sales strategies, improve inventory management, enhance customer targeting, and increase overall sales performance. By leveraging data, the project seeks to uncover opportunities for growth, ensuring Walmart can make more informed, strategic decisions moving forward.
## Analysis List
* Product Analysis 
> Conduct analysis on the data to understand the different product lines, the products lines performing best and the product lines that need to be improved.
* Sales Analysis
> This analysis aims to answer the question of the sales trends of product. The result of this can help use measure the effectiveness of each sales strategy the business applies and what modificatoins are needed to gain more sales.
* Customer Analysis
> This analysis aims to uncover the different customers segments, purchase trends and the profitability of each customer segment.
## Getting Started
* Data Wrangling: This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace, missing or NULL values.
  - Build a database
  - Create table and insert the data.
  - Select columns with null values in them. There are no null values in our database as in creating the tables, we set NOT NULL for each field, hence null values are filtered out.
* Feature Engineering: This will help use generate some new columns from existing ones.
  - Add a new column named time_of_day to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day most sales are made.
  - Add a new column named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.
  - Add a new column named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which month of the year has the most sales and profit.
* Exploratory Data Analysis (EDA): Exploratory data analysis is done to answer the listed questions and aims of this project.
## Conclusion
In conclusion, this project analyzes Walmart's sales data to identify top-performing branches and products, as well as key customer behavior trends. The insights gained can help optimize sales strategies and inventory management. By understanding sales patterns and customer preferences, Walmart can make more informed, data-driven decisions. Ultimately, the findings aim to improve overall sales performance and customer satisfaction.
