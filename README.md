# Zepto Inventory Data Analysis using SQL

## Project Overview
This project analyzes Zepto product inventory data using PostgreSQL. The objective is to explore product pricing, discounts, stock availability, product categories, and inventory weight to derive meaningful business insights.

## Tools & Technologies
- PostgreSQL 18
- pgAdmin 4
- SQL

## Dataset Description
The dataset contains Zepto product information, including:
- Product ID
- Product category and name
- Maximum Retail Price (MRP)
- Discount percentage
- Discounted selling price
- Available quantity
- Product weight
- Stock availability

## SQL Analysis Performed

### 1. Data Exploration
- Counted total records.
- Retrieved sample product records.
- Checked for NULL values.
- Identified distinct product categories.
- Compared in-stock and out-of-stock products.
- Identified duplicate product names.

### 2. Data Cleaning
- Identified products with zero prices.
- Removed records with zero MRP.
- Converted prices from paise to rupees.

### 3. Business Analysis
- Identified the top 10 products by discount percentage.
- Found high-MRP products that are out of stock.
- Estimated inventory value by product category.
- Identified products with high MRP and low discounts.
- Ranked categories by average discount.
- Calculated price per gram to compare product value.
- Classified products by weight.
- Calculated total inventory weight by category.

## Key Skills Demonstrated
- SELECT, WHERE and DISTINCT
- GROUP BY and HAVING
- ORDER BY and LIMIT
- Aggregate functions (COUNT, SUM, AVG)
- CASE statements
- UPDATE and DELETE
- Data cleaning and exploratory analysis

## Project Screenshots

Screenshots of SQL queries and their outputs are available in the `Output screenshots` folder.

## Project Structure
- `zepto_SQL_Analysis/` – SQL script and dataset
- `Output screenshots/` – Query output screenshots
- `README.md` – Project documentation

## Conclusion
This project demonstrates the use of PostgreSQL to explore retail inventory data, analyze product pricing and discounts, and derive inventory-related business insights.

