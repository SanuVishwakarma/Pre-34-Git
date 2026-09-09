# 📊 BlinkIt - Power BI Dashboard

<img width="1280" height="720" alt="maxresdefault" src="https://github.com/user-attachments/assets/80463b6e-f2d8-4752-8472-51a9698f31e6" />



## 📌 Executive Summary
Provide a brief 2–3 sentence overview of the business context and objective of this dashboard. 
* **Target Audience:** [e.g., Executive Leadership, Sales Operations, Finance Team]
* **Primary Objective:** [e.g., Track sales pipeline performance, monitor inventory turnover, analyze customer retention]

---

## 🔥 Key Features & Insights
* **📈 Key Performance Indicators (KPIs):** Instant visibility into total revenue, profit margins, and year-over-year (YoY) growth.
* **🔎 Interactive Filtering:** Slice and dice data by region, product category, time period, and customer segment.
* **🗓️ Time Intelligence:** Dynamic tracking of Year-to-Date (YTD), Quarter-to-Date (QTD), and Month-over-Month (MoM) metrics.
* **🎯 Drill-Through Navigation:** Detailed grain analysis allowing deep-dives into individual transaction logs.

---

## 🏗️ Data Model & Architecture

### 1. Data Schema
The report relies on a **Star Schema** architecture optimized for fast aggregation performance:
* **Fact Table(s):** `Fact_Sales` / `Fact_Transactions`
* **Dimension Tables:** `Dim_Date`, `Dim_Customer`, `Dim_Product`, `Dim_Region`
