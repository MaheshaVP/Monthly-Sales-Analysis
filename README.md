# 📊 Monthly Sales Analysis Dashboard

## Overview

This project demonstrates an end-to-end data analytics workflow using Python, MySQL, and Power BI. Raw sales data was cleaned and transformed in Python, stored in a MySQL database, and visualized through an interactive Power BI dashboard to generate actionable business insights.

## Dashboard Preview

<img width="1207" height="680" alt="Dashboard" src="https://github.com/user-attachments/assets/ca240112-74c9-401d-b27c-4263ba64d833" />


## Project Workflow

* Extracted sales data from Excel.
* Cleaned and transformed data using Python (Pandas).
* Removed duplicate records and handled invalid date values.
* Created business metrics such as Profit, Year, and Month.
* Loaded the cleaned dataset into MySQL using SQLAlchemy.
* Connected Power BI to MySQL and built an interactive dashboard.

## Dashboard Insights

* Total Sales Performance
* Total Profit Analysis
* Monthly Sales Trends
* Regional Profit Comparison
* Product-wise Sales Distribution

## Tech Stack

* **Python:** Pandas, SQLAlchemy, PyMySQL
* **Database:** MySQL
* **Visualization:** Power BI
* **Source Data:** Excel

## Data Cleaning & Transformation

* Removed duplicate records (520 → 500 rows).
* Converted date columns to proper datetime format.
* Removed records with invalid or missing dates.
* Created calculated fields:

  * Profit = Sales − Cost
  * Year
  * Month
* Exported cleaned data for database loading and reporting.

## Key Features

* End-to-end ETL pipeline
* Data cleaning and preprocessing
* MySQL database integration
* Interactive Power BI dashboard
* KPI tracking and business performance analysis

## Repository Structure

```text
├── dashboard/
│   └── sales_dashboard.pbix
├── notebooks/
│   └── sales_analysis.ipynb
├── sql/
│   └── database_setup.sql
├── data/
│   └── sales_cleaned.csv
├── assets/
│   └── dashboard_preview.png
└── README.md
```

## Results

The final dashboard enables users to monitor sales performance, analyze profitability across regions and products, and identify monthly trends for better business decision-making.
