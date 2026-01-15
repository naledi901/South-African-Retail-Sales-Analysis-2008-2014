# 🇿🇦 South African Retail Sales Analytics Dashboard (2008–2024)

An end-to-end **business & data analytics project** analysing South Africa’s national retail trade sales from 2008 to 2024 using **Power BI**.

This project demonstrates **data cleaning, data modelling, DAX time intelligence, and professional dashboard design** aligned with real-world business analysis standards.

---

## 📊 Project Overview

Retail sales data is influenced by seasonality, inflation, and economic shocks such as **COVID-19 lockdowns** and **load shedding**.

This project answers key business questions:
- How have retail sales changed over time?
- Which retail categories contribute the most to total sales?
- How does inflation impact retail sales (Current vs Constant prices)?
- What are the Year-on-Year (YoY) and long-term growth trends?
- Are there clear seasonal sales patterns?

---

## 🎯 Dashboard Features

### KPI Metrics
- **Total Sales**
- **Year-on-Year Growth (%)**
- **Annual Growth Rate (CAGR)**
- **Rolling 12-Month Sales**

### Visualisations
- **Sales by Category**  
  Horizontal bar chart with dynamic filters
- **Seasonal Sales Distribution**  
  Monthly box-and-whisker analysis
- **Inflation Impact**  
  Current vs Constant price comparison
- **Trend Analysis**  
  Multi-line category trends with Rolling 12-Month smoothing
- **Growth Analysis**  
  YoY % change and long-term performance

### Interactive Filters
- Year (2008–2024)
- Category
- Price Type
- Value Type

---

## 🧠 Analytics & Modelling

- Data cleaning and transformation using **Power Query**
- Star-schema modelling with a **Date dimension**
- DAX time-intelligence measures:
  - YoY Growth
  - Rolling 12-Month Sales
  - CAGR (Annual Growth Rate)
- Business-focused dashboard storytelling

---

## 🛠️ Tech Stack

- Power BI Desktop
- DAX
- Power Query
- Excel / CSV
- SQL (conceptual modelling)

---

## 📂 Repository Structure

South-African-Retail-Sales-Analysis-2008-2024/
│
├── data/
│   ├── retail_sales_sample.csv
│   └── README.md
│
├── dashboard/
│   └── SouthAfricanRetailSales.pbix
│
├── images/
│   ├── dashboard_overview.png
│   ├── sales_by_category.png
│   └── yoy_growth.png
│
├── model/
│   ├── dimdate_definition.md
│   └── dax_measures.md
│
├── docs/
│   └── insights_summary.md
│
└── README.md
