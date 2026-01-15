🇿🇦 South African Retail Sales Analytics Dashboard (2008–2024)

An end-to-end data analytics project analysing South Africa’s national retail trade sales from 2008 to 2024.
The project focuses on long-term growth, seasonality, inflation impact, and category performance, delivered through a fully interactive Power BI dashboard.

This repository demonstrates data modelling, DAX time-intelligence, and dashboard design best practices suitable for real-world business analysis roles.

📊 Project Overview

Retail sales data is often noisy, seasonal, and affected by macro-economic shocks such as COVID-19 lockdowns and load shedding.
This project answers key business questions such as:

How have retail sales evolved over time?

Which retail categories contribute most to total sales?

How does inflation affect sales at current vs constant prices?

What are the year-on-year (YoY) and long-term (CAGR) growth trends?

Are there clear seasonal patterns in monthly retail activity?

🎯 Key Features & Visuals
📌 KPI Summary

Total Sales

YoY Growth (%)

Annual Growth Rate (CAGR)

Rolling 12-Month Sales

📈 Core Visualisations

Sales by Category
Horizontal bar chart with dynamic filters

Seasonal Sales Distribution
Monthly box-and-whisker plots

Inflation Impact Analysis
Current vs Constant price comparison

Trend Analysis
Multi-line category trends with Rolling-12-Month smoothing

Growth Metrics
YoY % change and long-term growth indicators

🎛️ Interactive Slicers

Year (2008–2024)

Category

Price Type (Current / Constant)

Value Type

🧠 Analytical Techniques Used

Data cleaning & transformation (Power Query)

Star-schema modelling with a DimDate table

Time-intelligence DAX measures:

YoY Growth

Rolling 12-Month Sales

CAGR (Annual Growth Rate)

Business-focused dashboard layout and storytelling

🛠️ Tech Stack

Power BI Desktop

DAX

Power Query

Excel / CSV

SQL (schema design & modelling concepts)

📂 Repository Structure
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

📁 Data Notes

A sample dataset is provided for reproducibility.

The full dataset is excluded due to file size limitations.

To use the full dataset:

Place the cleaned CSV inside the data/ folder

Update the data source path in Power BI

Refresh the report

🚀 How to Run the Dashboard

Clone this repository

Open Power BI Desktop

Open dashboard/SouthAfricanRetailSales.pbix

Update data source path if needed

Refresh visuals

🔍 Key Insights (Summary)

Retail sales show strong long-term growth despite economic shocks

Clear seasonal peaks appear in Q4 across most categories

Inflation significantly widens the gap between current and constant prices over time

COVID-19 lockdowns (2020) show a visible disruption in trends

Certain retail categories consistently outperform others in contribution

(Full insights available in /docs/insights_summary.md)
