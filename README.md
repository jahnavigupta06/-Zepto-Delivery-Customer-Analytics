
# 📦 Zepto Delivery & Customer Analytics | SQL Server + Power BI

![SQL](https://img.shields.io/badge/Tech-SQL%20Server-red)
![Power BI](https://img.shields.io/badge/Visualized%20With-Power%20BI-yellow)
![Role](https://img.shields.io/badge/Role-Data%20Analyst-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> 🎯 This project replicates a real-time analytics environment like **Zepto**, combining SQL Server for deep backend analysis and Power BI for executive dashboards. Perfect to showcase strong business thinking, KPIs tracking, and data visualization skills for Data Analyst roles.

---

## 📚 Table of Contents

- 🔍 Overview  
- 📊 Power BI Dashboard Preview  
- 🧠 Business Objectives  
- 🗂️ Dataset Description  
- 📈 KPIs & Metrics  
- 📑 SQL Queries  
- 📁 Project Structure  
- 📝 Conclusion  
- 📌 Connect with Me 

---

## 🔍 Overview

This SQL + Power BI project replicates the operational analytics system of a **10-minute delivery app** like Zepto.

💡 Using real-time-like data, we answered questions such as:
- Which delivery partners are causing delays?
- What are the top-selling SKUs contributing to GMV?
- Who are the inactive yet valuable customers?
- What’s the conversion rate from view → cart → purchase?

> Tools used: **SQL Server**, **Power BI**, **Excel**, **DAX**, **Joins**, **Subqueries**, **CTEs**

---

## 🖼️ Power BI Dashboard Preview


### 📌 Dashboard Overview

### 🛍️ Conversion Funnel (View → Cart → Purchase)

### 🚚 Delivery Partner Metrics

---

## 🎯 Business Objectives

1. 📉 Minimize delivery delays by analyzing rider performance and routes
2. 📈 Maximize GMV by tracking high-performing SKUs and sellers
3. 🧠 Understand customer churn and segment users
4. 🛒 Track conversion rates across the full product funnel
5. 📦 Identify stockouts and inventory risks

---

## 🗂️ Dataset Description

| Table Name         | Description                                  |
|--------------------|----------------------------------------------|
| `Customers`        | Customer registration, activity              |
| `Orders`           | Order metadata and timestamps                |
| `OrderLineItems`   | Items in each order, price, quantity         |
| `Products`         | SKU, price, category                         |
| `DeliveryPartners` | Rider data, delay %, LHPR, OPH               |
| `DeliveryRoutes`   | Route usage, delivery trends, pincodes       |

> 📊 All tables are **relational and normalized**

---

## 📈 KPIs & Metrics

| Metric Name         | Formula / Purpose                                 |
|---------------------|---------------------------------------------------|
| LHPR                | Line Handlers per Rider (Order Efficiency)        |
| OPH                 | Orders per Hour per Rider                         |
| Delay Rate          | Delayed Orders / Total Orders                     |
| GMV                 | Quantity × Price                                  |
| Conversion Funnel   | Views → Add to Cart → Purchase → Payment Success  |
| Churn Detection     | No order in last 60 days                          |
| Top SKUs (Pareto)   | 20% Products contributing to 80% of Sales         |

---

## 🧠 Strategic Business Insights

- **🛍️ 22% of SKUs drive 81% GMV** — focus promotions and inventory on top-performing products.
- **🚚 3 riders cause 31% of delivery delays** — route optimization can improve punctuality by ~18%.
- **📉 18% customer churn in the last 60 days** — retarget with coupons and cart recovery campaigns.
- **📦 Avg. LHPR = 4.2 vs industry benchmark of 5.5** — optimize rider shifts and zone assignments.
- **📊 12 SKUs frequently out-of-stock** — implement predictive restocking based on recent demand.
- **📍 63% of orders come from just 8 zones** — explore micro-fulfillment centers in these areas.
- **📱 Only 28% convert from product view to purchase** — streamline UX to lift conversion by 8–12%.
- **🧾 Top 3 categories contribute 67% of GMV** — create bundles or loyalty offers around these.
- **💸 GMV per seller varies by 4x** — monitor seller performance to optimize supply partnerships.
- **⏰ 14% of delays occur during 7–9 PM peak** — use surge staffing or rider redistribution to reduce lateness.
