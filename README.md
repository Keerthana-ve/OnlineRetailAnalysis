🛍️ Online Retail Analysis — SQL Project
📖 Overview

This project focuses on analyzing online retail sales data using SQL Server.
The goal was to clean, explore, and derive business insights from transactional data such as sales dates, customer details, product categories, and total sales.

🗂️ Project Structure

Database Name: OnlineRetailAnalysis

Table: retail_sales

Columns:
transaction_id, sale_date, sale_time, customer_id, gender, age, category, quantity, price_per_unit, cogs, total_sale

⚙️ Steps Performed

Data Import

Imported retail sales data from Excel into SQL Server.

Data Cleaning

Removed rows with NULL values.

Ensured all columns had correct data types and consistent formatting.

Exploratory Analysis

Filtered sales by specific dates and categories.

Calculated category-wise total revenue.

Explored trends like most popular products and customer demographics.

💡 Key SQL Queries

Sales made on a particular date.

Category-wise total sales using GROUP BY.

High-value transactions and customer purchase trends.

Monthly and daily sales summaries.

📊 Insights

Clothing and electronics were among the top-performing categories.

Peak sales occurred in November, indicating strong seasonal trends.

Customers aged 25–35 made the most purchases.

(You can tweak these if your data showed something different!)

🧠 Skills Gained

SQL database design and data import from Excel.

Data cleaning using DELETE, WHERE, and null value checks.

Writing analytical queries using GROUP BY, FORMAT, and aggregate functions.

Interpreting sales data for business decision-making.

🛠️ Tools Used

SQL Server

Microsoft Excel

🚀 How to Run

Clone this repository.

Open OnlineRetailAnalysis.sql in SQL Server Management Studio (SSMS).

Run the script to create the database and execute all queries.

Explore the dataset and modify queries as needed.

🙌 Acknowledgements

This project was created as part of my learning journey in Data Analysis and SQL.
