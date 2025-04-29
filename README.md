# Task 6 - Sales Trend Analysis Using Aggregations

## 📚 Objective
Analyze monthly revenue and order volume using SQL aggregation techniques on the `online_sales` dataset.

## 🛠 Tools Used
- MySQL Workbench
- SQL Language

## 🗃 Dataset Information
- Table: `online_sales`
- Columns:
  - `order_id` (Primary Key)
  - `order_date` (Date of the order)
  - `amount` (Revenue amount for the order)
  - `product_id` (ID of the product sold)

## 🧠 SQL Concepts Used
- `YEAR()` and `MONTH()` functions to extract year and month
- `SUM(amount)` to calculate total monthly revenue
- `COUNT(DISTINCT order_id)` to calculate total monthly order volume
- `GROUP BY` year and month to organize the data
- `ORDER BY` to sort the result chronologically

## 📝 Steps Performed
1. Created the `online_sales` table with relevant columns.
2. Inserted sample data into the table.
3. Wrote a SQL query to:
   - Extract year and month from the `order_date`.
   - Aggregate revenue and distinct order counts.
   - Group and sort the data properly.
4. Executed the query and captured the output.

## 📂 Files Included
- `sales_analysis.sql` → SQL script containing the final query.
- `screenshot.png` → Screenshot of the query output table.
- `README.md` → This file explaining the project.

## 📈 Output Summary
The query provides a monthly breakdown of:
- Total Revenue
- Total Number of Distinct Orders

The results are ordered by year and month to show sales trends over time.
