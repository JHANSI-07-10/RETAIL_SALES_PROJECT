# RETAIL_SALES_PROJECT
## Retail Performance & Profitability Dashboard
📊 Project Overview
This project analyzes retail sales data to evaluate performance and profitability across product categories, regions, and time periods. The data was sourced from SQL and CSV files, cleaned, processed, and visualized using SQL queries and a Jupyter notebook.

## 🗂️ Data Sources
orders.sql: SQL scripts for creating and populating the orders table (50 sample orders).

orders1.csv: Supplementary dataset containing order details.

Retail_Sales.ipynb: Jupyter notebook for data analysis and dashboard generation.

## 📈 Key Metrics
Total Sales: 26,000

Total Profit: 3,090

Total Inventory Days: 4,703

Average Number of Orders: 1,030

## 🔍 Insights
Profit by Sub-Category
Top Profit Drivers: Laptops, Sofas, Phones

Low/Negative Profit Sub-Categories: Tables, Pens, Paper

Sales by Region
South: 35.51% of sales

West: 34.82% of sales

East: 15.54% of sales

North: 14.13% of sales

Sales Trend (Monthly)
Peak: February

Dip: March

Slight Rise: April

Inventory & Orders
Average inventory days: ~50 (varies by category)

Orders dominated by Technology and Furniture

## 🛠️ SQL Data Preparation
Removed records with NULL in critical fields

Deleted records with inventory_days <= 0 or stock_qty < 0

Standardized region names (trimmed whitespace)

Adjusted outlier profits

## ✅ Conclusion
This dashboard offers actionable insights into retail sales and profitability:

Identify best-performing products and regions

Guide stock management

Highlight areas for operational improvements
