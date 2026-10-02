# 🍕 Pizza Hut Sales Analysis Project (SQL)

## 📌 Project Overview

This project analyzes Pizza Hut sales data using **MySQL** to extract meaningful business insights related to **revenue, customer ordering behavior, and product performance**.

The project simulates a real-world business analytics case and demonstrates practical SQL skills relevant to **Data Analyst, Business Analyst, and SQL Developer** roles.

---

## 🎯 Business Objectives

- Calculate total revenue and overall sales performance
- Identify top-selling pizzas and categories
- Analyze customer ordering behavior
- Perform time-based sales analysis
- Analyze pizza sizes and product performance
- Calculate key sales KPIs
- Generate insights to support business decision-making

---

## 🛠️ Tools & Technologies

- **SQL — MySQL**
- **Jupyter Notebook (.ipynb)**
- **GitHub**

---

## 📂 Dataset Description

The project uses a relational database consisting of the following tables:

| Table | Description |
|---|---|
| `orders` | Contains order date and time information |
| `order_details` | Contains pizza quantity and order-level details |
| `pizzas` | Contains pizza size and price information |
| `pizza_types` | Contains pizza names and categories |

---

## 🔍 SQL Concepts & Techniques Used

- `SELECT` — Data retrieval
- `WHERE` — Data filtering
- `ORDER BY` — Sorting results
- `LIMIT` — Retrieving top records
- `SUM()`, `COUNT()`, `AVG()` — Aggregations
- `GROUP BY` — Group-level analysis
- `HAVING` — Filtering aggregated results
- `INNER JOIN` — Multi-table analysis
- Subqueries — Advanced data analysis
- Date & Time Functions — Time-based analysis
- Revenue and KPI calculations
- Window Functions — Ranking and analytical calculations

---

## 📊 Key Insights Generated

- Identified top-selling pizzas based on quantity and revenue
- Analyzed the most popular pizza categories
- Identified customer ordering patterns
- Analyzed sales performance by pizza size
- Identified peak ordering periods
- Calculated total revenue and average order value
- Analyzed daily and monthly sales trends
- Evaluated product-level sales performance

---

## 📈 Business Value

The analysis helps understand:

- Which products generate the highest sales
- Which pizza categories and sizes are most popular
- When customer demand is highest
- How customers behave across different ordering periods
- Which products contribute most to overall revenue

These insights can support **sales planning, product strategy, inventory management, and business decision-making**.

---

## 📁 Project Structure

```text
Pizza-hut-Sales-Analysis-Project-SQL/
│
├── Dataset/
│   └── pizza_sales.csv
│
├── Questions/
│   └── SQL_Questions.sql
│
├── pizzahut_Analysis_sqlProject.ipynb
│
└── README.md
