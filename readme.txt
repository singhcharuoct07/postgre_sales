# Retail Sales Data Analysis using PostgreSQL

## 📌 Project Overview
This project is developed using PostgreSQL to perform data cleaning, data exploration, and business analysis on retail sales data.

The database stores transaction-level sales records including customer details, product category, quantity, pricing, and total sales.

The project demonstrates practical use of SQL for solving real-world business problems.

---

## 🛠 Technologies Used
- PostgreSQL
- SQL
- pgAdmin

---

## 📂 Database Schema

Table Name: SALES

Columns:
- transactions_id (Primary Key)
- sale_date (DATE)
- sale_time (TIME)
- customer_id
- gender
- age
- category
- quantity
- price_per_unit
- cogs
- total_sale

---

## 🧹 Data Cleaning
- Checked for NULL values in all columns
- Deleted records containing NULL values

---

## 📊 Data Exploration
- Total number of sales transactions
- Unique customers
- Distinct product categories

---

## 📈 Business Analysis & SQL Queries

The following business problems were solved using SQL:

1. Retrieve sales made on a specific date.
2. Filter category-based sales with quantity condition.
3. Calculate total sales per category.
4. Find average age of customers by category.
5. Identify high-value transactions.
6. Count transactions by gender and category.
7. Calculate monthly average sales and best-selling month.
8. Find top 5 customers based on total sales.
9. Count unique customers per category.
10. Categorize sales into shifts (Morning, Afternoon, Evening).

---

## ⏰ Shift Classification Logic
- Morning → Before 12 PM
- Afternoon → Between 12 PM and 5 PM
- Evening → After 5 PM

---

## 🚀 How to Run the Project
1. Install PostgreSQL.
2. Open pgAdmin.
3. Create a new database.
4. Run the SQL script file.
5. Execute queries for analysis.

---

## 🎯 Key Concepts Used
- CREATE TABLE
- PRIMARY KEY
- SELECT Queries
- WHERE Clause
- GROUP BY
- ORDER BY
- Aggregate Functions (SUM, COUNT, AVG)
- DISTINCT
- CASE Statement
- Common Table Expression (WITH)
- EXTRACT Function

---

## 👩‍💻 Developed By
Charu Singh  
B.Tech 2nd Year
