# 📊 Customer Sales Analysis with Databricks SQL

## Overview

This project demonstrates end-to-end **customer sales analytics** using **Databricks SQL** on a synthetic dataset.  
It simulates real-world **business intelligence use cases** such as customer segmentation, revenue analysis, churn detection, and executive dashboards.

The goal is to showcase how Databricks SQL can be used to transform raw customer data into **actionable insights** through SQL analytics and interactive visualizations.

---

## 📁 Dataset Summary

The dataset used in this project is:

**`customer_sales_summary_small.csv`**  
It contains **100 synthetic customer records**, enriched with revenue and ordering behavior.

### Schema

| Column Name        | Description |
|--------------------|-------------|
| `customer_id`      | Unique customer identifier |
| `first_name`       | Customer first name |
| `last_name`        | Customer last name |
| `country`          | Customer country |
| `signup_date`      | Customer registration date |
| `avg_order_value`  | Average value per order |
| `order_count`      | Total number of orders |
| `last_order_date`  | Most recent order date |
| `total_sales`      | Total revenue per customer (`avg_order_value × order_count`) |

---

## ✅ Key Achievements

### 1️⃣ Customer Cohort Segmentation

- Segmented customers into **Low**, **Mid**, and **High Value** cohorts based on order frequency
- Analyzed:
  - Revenue contribution per segment
  - Customer distribution across segments

**Business Use Case:**  
Identify high-value customers and prioritize retention strategies.

---

### 2️⃣ Sales Distribution by Country

- Calculated total revenue per country
- Measured customer contribution by geography
- Built comparative visualizations

**Business Use Case:**  
Understand geographical revenue concentration and market performance.

---

### 3️⃣ Revenue & Signup Growth Trends

- Tracked new customer signups by month
- Analyzed revenue contribution over time
- Identified seasonal growth patterns

**Business Use Case:**  
Support forecasting and marketing campaign planning.

---

### 4️⃣ Recency (Churn Risk) Analysis

- Calculated days since last purchase
- Flagged inactive or at-risk customers
- Prepared churn-focused dashboards

**Business Use Case:**  
Enable proactive customer retention actions.

---

### 5️⃣ Top Customers Leaderboard

- Ranked customers by total revenue
- Created executive-friendly tables and charts

**Business Use Case:**  
Highlight VIP customers and support account-based strategies.

---


