## Project Topic: KMS Sales Data Analysis Using SQL
### Project Overview 

This project involved performing extensive data exploration and transformation on KMS’s sales data using SQL. The objective was to gain insight into sales performance, customer behavior, product profitability, shipping methods, and regional sales dynamics. The analysis aimed to guide business decisions through data-driven insights.

### Tools Used

- Microsoft SQL Server Management Studio (SSMS) or any SQL environment

- SQL (DDL & DML commands, joins, aggregations, filtering, sorting, and grouping)
### Data Cleaning and Preparation 

Handled nulls: Replaced invalid PROFIT values with NULL.

Data type casting: Converted columns such as profit and unit_price to appropriate types (float, decimal).

Removed irrelevant columns: Dropped unnecessary fields like unit_price before recreating it with corrected types.

Joined datasets: Merged KMS Sql Case Study with Order_Status using order_id to create a comprehensive final table (kms_final_joined).

Checked for duplicates: Identified duplicate Order_id entries.
### Exploratory Data Analysis 

1. Top Performing Product Category:

Office Supplies had the highest number of sales.

2. Top and Bottom 3 Regions by Sales:

Top: Ontario, Quebec, British Columbia

Bottom: Nunavut, Northwest Territories, Yukon

3. Most Profitable Consumer Customer:

Emily Phan with over ₦34,000+ in profit.

4. Top 10 Most Valuable Customers:

Identified based on total sales volume, e.g., Deborah Brumfield, Roy Skaria, Julia Barnett.

5. Preferred Shipping Method:

Delivery Truck incurred the highest total shipping cost.

6. Customer Segments with Returns:

Highlighted which customers and segments returned items.

7. Small Business Customer with Highest Sales:

Identified based on customer_segment and aggregated sales.

8. Revenue from Appliances in Ontario:

₦202,346.80 in total sales for appliance-related products.
### Recommendation 

- Target top customer segments: Focus on high-value consumers like Emily Phan and replicate their purchasing patterns.

- Reduce shipping costs: Optimize the use of Delivery Trucks, which are currently the most expensive method.

- Regional Strategy: Improve engagement in low-performing regions like Nunavut and Northwest Territories.

- Profit Boosting: Upsell high-margin categories such as Office Supplies and Technology.

- Customer Retention: Prioritize customers with frequent returns for better satisfaction and retention strategies.
