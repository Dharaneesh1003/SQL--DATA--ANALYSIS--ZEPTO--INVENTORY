Zepto SQL Data Analysis Project

 Project Overview

This project focuses on analyzing "Zepto product and inventory data using PostgreSQL/SQL". The analysis explores product pricing, discounts, inventory availability, product categories, estimated revenue, and inventory weight to generate meaningful business insights.

The project demonstrates practical skills in "SQL data exploration, data cleaning, aggregation, filtering, sorting, CASE statements, and business-oriented data analysis".

Dataset

The dataset contains "3,732 product records" with 9 attributes:

* Category
* Product Name
* MRP
* Discount Percentage
* Available Quantity
* Discounted Selling Price
* Weight in Grams
* Out of Stock Status
* Quantity

Tools & Technologies

* "PostgreSQL"
* "SQL"
* "CSV Dataset"
* "GitHub"

 Project Workflow

 1. Data Exploration

* Checked the total number of records.
* Viewed sample product records.
* Identified unique product categories.
* Analyzed in-stock vs out-of-stock products.
* Identified products appearing under multiple SKUs.
* Checked for NULL values.

 2. Data Cleaning

* Identified products with zero MRP or selling price.
* Removed invalid records with zero MRP.
* Converted product prices from **paise to Indian Rupees**.

 3. Data Analysis

The project answers several business questions, including:

* What are the "top 10 best-value product" based on discount percentage?
* Which products have a "high MRP but are currently out of stock"?
* What is the "estimated revenue for each product category"?
* Which products have an "MRP above ₹500 and discount below 10%"?
* Which categories provide the "highest average discounts"?
* What is the "price per gram" of products?
* How can products be classified into "Low, Medium, and Bulk weight categories"?
* What is the "total inventory weight for each category"?

 Key SQL Concepts Demonstrated

* 'SELECT'
* 'WHERE'
* 'DISTINCT'
* 'ORDER BY'
* 'GROUP BY'
* 'HAVING'
* 'LIMIT'
* Aggregate Functions: 'COUNT()', 'SUM()', 'AVG()'
* 'CASE WHEN'
* 'ROUND()'
* 'DELETE'
* 'UPDATE'
* NULL value handling
* Conditional filtering
* Business KPI calculations

 Business Insights

This analysis can help identify:

* Products offering the best customer discounts.
* Categories generating higher potential revenue.
* High-value products that are out of stock.
* Categories with aggressive discount strategies.
* Products providing better value based on price per gram.
* Categories carrying larger inventory volumes.
* Opportunities for inventory and pricing optimization.

 Project Structure

text
Zepto-SQL-Data-Analysis
* Zepto_SQL_data_analysis.sql
* zepto_v2.csv
* README.md


 Project Objective

The primary objective of this project is to demonstrate how "SQL can be used to transform raw e-commerce inventory data into actionable business insights"  related to pricing, discounts, inventory, product availability, and revenue.

 Skills Demonstrated

"SQL | PostgreSQL | Data Cleaning | Data Analysis | Exploratory Data Analysis | Business Analysis | Data Aggregation | Inventory Analysis | E-commerce Analytics"

Developed By,

" Dharaneesh A "


