# 🇿🇦 South Africa Retail Sales Analytics Dashboard (2008–2024)

An **end-to-end analytics project** analyzing South Africa’s national retail trade performance from **2008 to 2024**.  
The project demonstrates **data modeling, DAX calculations, time-series analysis, and dashboard storytelling** using Power BI.

This dashboard is designed for **business stakeholders**, enabling clear insights into long-term trends, inflation effects, seasonality, and growth performance across retail categories.

---

## 📊 Dashboard Overview

The Power BI dashboard answers key business questions such as:

- How have retail sales evolved over time?
- Which retail categories contribute most to total sales?
- How do **current vs constant prices** reveal inflation impact?
- What are the **year-on-year growth trends**?
- How strong is long-term growth (CAGR)?
- Are there visible impacts from **COVID-19 lockdowns** and **load shedding periods**?

---

## 🔍 Key Features & Visuals

### 1️⃣ KPI Summary
- **Total Sales**
- **Year-on-Year (YoY) Growth**
- **Annual Growth Rate (CAGR)**
- **Last 12 Months Sales (Rolling 12M)**

---

### 2️⃣ Sales by Category
- Horizontal bar chart ranking retail categories by total sales
- Fully interactive with Year, Category, Price Type, and Value Type filters

---

### 3️⃣ Trend Analysis (2008–2024)
- Multi-line trend chart showing category performance over time
- Rolling 12-month smoothing to reduce seasonality noise

---

### 4️⃣ Inflation Impact Analysis
- Comparison of **At Current Prices vs At Constant Prices**
- Highlights real growth vs inflation-driven growth

---

### 5️⃣ Seasonal Sales Patterns
- Monthly seasonality analysis using box-and-whisker visuals
- Identifies recurring retail peaks (e.g. December trading periods)

---

## 🎛 Interactive Filters (Slicers)

The dashboard includes dynamic slicers for:

- **Year** (2008–2024)
- **Retail Category**
- **Price Type** (Current vs Constant)
- **Value Type**

All visuals respond instantly to slicer selections.

---

## 🧠 Analytical Techniques Used

- Star schema data modeling
- Dedicated **Date Dimension (DimDate)**
- Time intelligence with DAX
- Rolling 12-month calculations
- Year-on-Year growth analysis
- CAGR computation
- Inflation-adjusted comparisons

---

## 🛠 Tech Stack

- **Power BI**
- **DAX**
- **Power Query**
- **Excel**
- **SQL-style data modeling**
- **Time-series analysis**

---

## 📁 Project Structure

```text
├── data/
│   └── retail_trade_sales_raw.xlsx
│
├── model/
│   └── dim_date_logic.md
│
├── dashboard/
│   └── south_africa_retail_sales.pbix
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
