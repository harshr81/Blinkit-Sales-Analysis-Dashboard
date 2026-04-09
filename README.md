# 🛒 BlinkIT Grocery Sales Dashboard

An interactive Power BI dashboard built on BlinkIT's grocery sales data, providing insights into sales performance, outlet distribution, and product-level trends across India's quick-commerce market.

---

## 📊 Dashboard Preview

![BlinkIT Dashboard](https://github.com/harshr81/Blinkit-Sales-Analysis-Dashboard/blob/b8cb46fefb756a6502300db898632084755ec330/images/Blinkit%20dashboard.png)

---

## 📌 Objective

To analyze BlinkIT's grocery sales data and uncover actionable insights around:
- Which outlet types and locations drive the most revenue
- How fat content and item type affect sales performance
- Trends in outlet establishment over time
- Customer ratings across different store formats

---

## 📂 Dataset Overview

- **Source:** BlinkIT Grocery Sales Data
- **Records:** 8,523 rows × 12 columns
- **File:** `BlinkIT_Grocery_Data.xlsx`

### Column Description

- `Item Identifier`           : Unique product code
- `Item Type`                 : Category (e.g., Fruits, Dairy, Snacks) — 16 types
- `Item Fat Content`          : Low Fat / Regular
- `Item Weight`               : Weight of the product
- `Item Visibility`           : Display prominence in store
- `Outlet Identifier`         : Unique store code
- `Outlet Type`               : Supermarket Type1/2/3 or Grocery Store
- `Outlet Size`               : Small / Medium / High
- `Outlet Location Type`      : Tier 1 / Tier 2 / Tier 3 cities
- `Outlet Establishment Year` : Year outlet was opened (2011–2022)
- `Sales`                     : Item-level sales figure
- `Rating`                    : Customer rating (1–5 scale)

---

## 📈 Key Metrics

- Total Sales : **$1.20M**
- Avg Sales per Item : **$141**
- Total Items : **8,523**
- Avg Customer Rating : **3.92**

---

## 🔍 Key Insights

- **Supermarket Type1** dominates with **$787.55K** in total sales across 5,577 items
- **Tier 3** city outlets outperform others, generating **$472.13K** in revenue
- **Fruits & Vegetables** and **Snack Foods** are the top-selling item categories (~$0.18M each)
- Outlets established in **2018** saw peak sales at **$205K**
- **Low Fat** products account for a significant share of sales despite being fewer in number
- **Grocery Stores** have the highest item visibility score (0.10) among all outlet types

---

## 🛠️ Tools Used

- **Microsoft Power BI:** Dashboard creation and visualization
- **Microsoft Excel:** Raw data storage and initial exploration
- **DAX:** Custom measures (Total Sales, Avg Sales, No. of Items, Avg Rating)
- **Power Query:** Data transformation and cleaning

---

## ⚙️ Features of the Dashboard

- **Filter Panel** — Slice data by Outlet Location Type, Outlet Size, and Item Type
- **Fat Content Analysis** — Donut chart and Bar breakdown of Low Fat vs Regular sales
- **Item Type Breakdown** — Horizontal bar chart comparing sales across 16 categories
- **Outlet Establishment Trend** — Line chart tracking sales growth from 2011–2022
- **Outlet Size & Location** — Donut chart and Funnel chart for geographic/size distribution
- **Outlet Type Table** — Detailed comparison of Total Sales, Avg Sales, Rating, and Item Visibility across all 4 outlet formats

---

## 🧠 What I Learned

- Building end-to-end dashboards from raw data in Power BI
- Writing DAX measures for dynamic KPI cards
- Designing a clean, branded dashboard layout (BlinkIT's yellow theme)
- Deriving business insights from e-commerce transactional data

---

## 📬 Connect

If you found this project useful or have feedback, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/harsh-ranjan-759b81284/).
