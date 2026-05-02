# 📊 SQL Data Analytics Project

> A comprehensive collection of SQL scripts that demonstrate real-world analytical techniques applied to sales data — built on top of a fully structured Data Warehouse.

---

## 🧭 Overview

This project showcases advanced SQL-based analytics covering a wide range of business intelligence techniques. The goal is to extract meaningful, actionable insights from structured sales data — answering real business questions around performance, trends, and customer behavior.

The analyses are organized into focused modules, each targeting a specific analytical pattern commonly used in data analytics and BI roles.

---

## 🔗 Data Source — Built on a Real DWH

> ⚠️ **Important:** The data used in this project is **not a raw dataset** — it is the output of a fully designed and implemented **Data Warehouse (DWH)** that I built from scratch.

The DWH consolidates data from two source systems (ERP & CRM), applies data cleansing, and produces an integrated, analytics-ready data model using a **medallion architecture** (Bronze → Silver → Gold layers).

👉 **Check out the Data Warehouse project here:**  
[sql-data-warehouse-project](https://github.com/mohammedelkomy/sql-data-warehouse-project)

This means the analytics scripts in this repository operate on clean, well-structured Gold-layer tables — reflecting a real-world end-to-end data pipeline workflow.

---

## 📁 Repository Structure

```
sql-data-analytics-project/
│
├── datasets/          # Sample data used for analysis
└── scripts/           # SQL analysis scripts organized by technique
```

---

## 🔍 Analytical Techniques Covered

### 📈 Changes Over Time
Track how key metrics (revenue, orders, customers) evolve month-over-month and year-over-year. Useful for identifying growth trends and seasonal patterns.

### 📊 Cumulative Analysis
Calculate running totals and moving averages to understand the accumulation of business performance over time.

### 🏆 Performance Analysis
Rank products, customers, and regions by performance. Identify top performers and underperformers using window functions like `RANK()`, `DENSE_RANK()`, and `ROW_NUMBER()`.

### 🧩 Data Segmentation
Group customers and products into meaningful segments based on behavior, value, or attributes — enabling targeted insights and decision-making.

### 🥧 Part-to-Whole Analysis
Understand the contribution of each product, category, or region to the overall business — answering questions like "what percentage of total revenue comes from each category?"

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **SQL Server (T-SQL)** | All analytics scripts |
| **SSMS** | Query development & testing |
| **DWH Gold Layer** | Source of structured, clean data |

---

## 💼 Who Is This For?

This project is designed as a **portfolio project** demonstrating practical SQL analytics skills relevant to:

- Data Analyst roles
- Business Intelligence roles
- Data Engineer roles working on the analytics layer

It reflects real-world patterns and best practices used in professional data environments.

---

## 🤝 Connect with Me

**Mohamed Elkomy** — Data Analyst & Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-elkomy-me30/)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/share/1CZhXTTZWh/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:moahmedelkomy367@gmail.com)
