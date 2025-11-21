# 📊 Task 6: Sales Trend Analysis Using Aggregations

This project performs sales trend analysis using SQL to calculate monthly revenue and order volume from an online sales dataset.

# 📌 Objective

Analyze:

• Monthly revenue

• Monthly order volume

• Time-based sales trends

# 🛠️ Tools Used

• PostgreSQL / MySQL / SQLite

• SQL Aggregation Functions

# 📂 Dataset

Table Name: online_sales
• order_id

• order_date

• product_id

• customer_id

• category

• amount

• payment_method

• status

# 🧠 SQL Concepts Applied

• EXTRACT(YEAR FROM order_date) → get year

• EXTRACT(MONTH FROM order_date) → get month

• SUM(amount) → calculate total monthly revenue

• COUNT(DISTINCT order_id) → calculate order volume

• GROUP BY year, month → aggregate data

• ORDER BY year, month → sort results



