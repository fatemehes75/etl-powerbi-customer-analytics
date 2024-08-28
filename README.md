# Customer Insights with Power BI: An E-commerce ETL Project

<img width="1137" alt="Screenshot 2024-08-26 at 8 22 17 PM" src="https://github.com/user-attachments/assets/f09afe50-aba6-4177-8674-86aabe23dd58">

## Project Overview:
This is an ETL (Extract, Transform, Load) project with Amazon S3, SnowFlake and Power BI. Project goals are:
  * Developing a customer-centric dashboard using Power BI to monitor and analyze customer data from an e-commerce platform.  The goal is to create actionable insights that enhance business decision-making by providing a comprehensive view of customer behavior, purchasing patterns, and sales trends.
  * Extracting data stored in an S3 bucket on AWS, transforming it within Snowflake, and loading it into Power BI for visualization.

## Dataset Description:
The dataset used in this project consists of 286,392 entries across 36 columns, capturing detailed information about customer orders on the e-commerce website. The dataset includes both numerical and categorical data, such as:

Numerical Data: Item ID, quantity ordered, price, value, discount amount, total, customer ID, year, reference number, age, zip code, and discount percentage.
Categorical Data: Order ID, order date, and order status.
This dataset is ideal for analyzing purchasing patterns, identifying popular products, and understanding customer behavior. It also supports the development of predictive models for forecasting customer behavior and sales trends.

## Key Objectives:

1. ETL Process:
* Extraction: Pull data from AWS S3 into Snowflake.
* Automation: Set up a Snowpipe to automate loading data from an S3 bucket into a Snowflake table. 
* Transformation: Clean, transform, and model the data within Snowflake to ensure it is suitable for analysis.
* Loading: Load the transformed data into Power BI for visualization and analysis.
  
2. Dashboard Development: Design and develop an interactive Power BI dashboard that provides insights into:
* Customer Behavior: Revenue per State, Revenue based per Gender, Revenue based on Age and Percentage of Revenue per Region. 
* Sales Trends: Identification of top-selling products, seasonal trends, and sales performance over time.
* Discount Analysis: Impact of discounts on sales and customer purchasing behavior, Quantity - Discount Percentage Correlation.


## Business Impact:
The insights derived from this ETL project will empower the e-commerce business to make data-driven decisions, such as optimizing product offerings, personalizing marketing strategies, and improving customer satisfaction. By understanding customer behavior and sales trends, the business can better align its operations with customer needs, leading to increased sales and customer loyalty.

## Technology Used:
* Data Storage: AWS S3
* Data Warehouse: Snowflake
* Data Visualization: Power BI
* ETL Tools: SQL, DAX (for Power BI)
* Cloud Platform: AWS

## Conclusion:
This ETL project demonstrates the ability to extract, transform, and load large datasets from cloud storage, create impactful visualizations, and generate actionable business insights. The customer-centric approach ensures that the business remains aligned with customer needs, fostering a competitive advantage in the e-commerce market.
