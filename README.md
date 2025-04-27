# 🛒 Retail Sales Analysis (SQL Project)

## 📋 Project Overview
This project focuses on analyzing a retail sales dataset using SQL.  
We created a database and table, performed data cleaning, explored key metrics, and answered important business questions to generate insights for better business decisions.

## 🎯 Objectives
- Create a structured database for retail sales transactions.
- Perform data cleaning to handle missing and inconsistent data.
- Explore and analyze sales metrics.
- Solve real-world business problems using SQL queries.

## 🗂️ Project Structure
| File | Description |
| :--- | :--- |
| `SQL - Retail Sales Analysis.csv` | Raw dataset containing retail transactions |
| `sql_query_p1.sql` | SQL queries for database creation, cleaning, exploration, and analysis |
| `README.md` | Project overview and documentation |

## 📊 Dataset Details
- **Table Name**: `retail_sales`
- **Columns**:
  - `transactions_id` (Primary Key)
  - `sale_date`
  - `sale_time`
  - `customer_id`
  - `gender`
  - `age`
  - `category`
  - `quantity`
  - `price_per_unit`
  - `cogs`
  - `total_sale`

## 🧹 Data Cleaning Steps
- Checked for NULL values across all columns.
- Deleted records with missing essential data to ensure a clean dataset.

## 🔎 Data Exploration
- Total number of sales.
- Number of unique customers.
- Unique product categories.

## 📊 Business Questions Answered
- Retrieve sales made on a specific date.
- Find transactions where quantity sold is high in specific categories.
- Calculate total sales by each category.
- Find the average age of customers purchasing from "Beauty" category.
- Identify transactions where total sale amount exceeded 1000.
- Find total transactions by gender in each category.
- Determine the best-selling month each year.
- Identify top 5 customers based on total sales.
- Find number of unique customers purchasing from each category.
- Analyze order distribution across different shifts (Morning, Afternoon, Evening).

## 📈 Key Findings
- Top-selling months and categories were identified.
- High-value customers were discovered contributing significantly to revenue.
- Peak sales timings were analyzed based on shifts.

## 🧰 Tools Used
- SQL (PostgreSQL / MySQL)
- CSV Dataset

## 🧠 Learnings
- Strengthened skills in SQL for data cleaning and analysis.
- Learned how to extract valuable business insights from raw data.
- Practiced writing complex SQL queries for real-world business scenarios.
