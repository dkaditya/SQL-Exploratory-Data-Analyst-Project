# Sales Analytics SQL Project

## Description
This project contains a comprehensive set of SQL queries and views for analyzing sales, products, and customers in a data warehouse. It provides actionable insights and KPI calculations for business intelligence purposes.

The single SQL file includes:

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

## How to Use
1. Load the SQL file into your SQL database.
2. Make sure the tables `gold.fact_sales`, `gold.dim_products`, and `gold.dim_customers` exist and are populated.
3. Execute the queries in the file sequentially:
   - Aggregation and analysis queries
   - Creation of reporting views
4. Use the views `gold.report_customers` and `gold.report_products` to quickly get consolidated insights.

---

## Project Highlights
- Customer segmentation and KPIs (total sales, avg order value, monthly spend)
- Product segmentation and performance metrics
- Running totals, moving averages, and YoY comparison
- Category-level sales contribution
- Cost-based product segmentation

---
