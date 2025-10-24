# Sales Analytics SQL Project

## Description
This project contains a comprehensive set of SQL queries and views for analyzing sales, products, and customers in a data warehouse. It provides actionable insights and KPI calculations for business intelligence purposes.

The SQL file includes:

- Monthly and yearly sales aggregation
- Running totals and moving averages
- Product performance analysis and year-over-year comparison
- Category-wise sales contribution
- Product cost segmentation
- Customer segmentation (VIP, Regular, New)
- Creation of two main reporting views:
  - `gold.report_customers`
  - `gold.report_products`

---

## Technologies Used
- SQL (T-SQL/PostgreSQL compatible syntax)
- Database: Star-schema warehouse with tables:
  - `gold.fact_sales`
  - `gold.dim_products`
  - `gold.dim_customers`

---

## Dataset
This project **does not include the dataset**.  
To run the queries and views, you need to provide your own data or create sample data for the following tables:

- `fact_sales`  
- `dim_products`  
- `dim_customers`  

You can create sample data using SQL `INSERT` statements or CSV files. Make sure the table structure matches the columns used in the queries.

---

## How to Use
1. Create the necessary tables (`fact_sales`, `dim_products`, `dim_customers`) in your database.  
2. Load your own data or create sample data for testing.  
3. Execute the SQL file sequentially:
   - Aggregation and analysis queries
   - Creation of reporting views
4. Explore the views `gold.report_customers` and `gold.report_products` for consolidated insights.

---

## Project Highlights
- Customer segmentation and KPIs (total sales, avg order value, monthly spend)  
- Product segmentation and performance metrics  
- Running totals, moving averages, and YoY comparison  
- Category-level sales contribution  
- Cost-based product segmentation

---
