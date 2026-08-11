# 📊 Customer Trends & Shopping Behavior Analysis (Python, SQL & Power BI)

An end-to-end data analytics portfolio project analyzing **3,900 consumer purchase transactions** to uncover strategic business intelligence, customer segmentation, discount sensitivity, and revenue drivers.

---

## 📌 Project Overview
This project simulates a complete data analytics pipeline mirroring real-world business analyst responsibilities:

1. **Data Cleaning & Preprocessing (Python / Pandas)**: Handled missing ratings via category medians, standardized schema, and engineered age cohorts and purchase frequency metrics.
2. **Database Modeling & Analytical Querying (PostgreSQL & SQL)**: Loaded cleaned data into PostgreSQL and executed 10 complex queries using CTEs, window functions (`ROW_NUMBER`), and aggregations.
3. **Interactive Business Dashboard (Power BI)**: Visualized customer demographics, sales channels, shipping preferences, and loyalty segments for stakeholder reporting.
4. **Executive Reporting**: Produced a structured business report and presentation deck outlining actionable strategic recommendations.

---

## 🔑 Key Business Findings

- **Customer Segmentation**:
  - **Loyal (>10 purchases)**: 3,116 customers (80%+ of total volume)
  - **Returning (2-10 purchases)**: 701 customers
  - **New (1 purchase)**: 83 customers
- **Revenue by Gender**: Male customers generated **$157,890**, Female customers generated **$75,191**.
- **Top Rated Products**: Gloves (3.86/5), Sandals (3.84/5), Boots (3.82/5), Hat (3.80/5).
- **Highest Spending Age Cohort**: Young Adults ($62,143 total revenue).
- **Discount Dependency**: Products with highest discount usage included Hats (50.0%) and Sneakers (49.66%).

---

## 🛠️ Tech Stack & Tools

- **Data Processing & ETL**: Python (`pandas`, `numpy`, `sqlalchemy`)
- **Database & Querying**: PostgreSQL 15 / SQLite & SQL (`customer_behavior_sql_queries.sql`)
- **Visualization**: Power BI (`customer_behavior_dashboard.pbix`)
- **Documentation**: Markdown, PDF Business Report, PowerPoint Deck

---

## 📂 Repository Structure

```text
├── Customer_Shopping_Behavior_Analysis.ipynb  # Python notebook for Data Cleaning & EDA
├── customer_behavior_sql_queries.sql          # 10 Business Intelligence SQL queries
├── run_sql_analysis.py                        # Python runner to execute SQL queries
├── customer_behavior_dashboard.pbix           # Power BI Dashboard file
├── customer_shopping_behavior.csv             # Raw transactional dataset (3,900 rows)
├── Customer Shopping Behavior Analysis.pdf    # Executive Business Report
├── Customer-Shopping-Behavior-Analysis.pptx   # Executive Presentation Deck
├── Business Problem Document.pdf              # Business Problem & Objectives statement
└── README.md                                  # Project Documentation
```

---

## 🚀 Quick Start Guide

### 1. Clone the Repository
```bash
git clone https://github.com/sh1vam31/customer-trends-data-analysis-SQL-Python-PowerBI.git
cd customer-trends-data-analysis-SQL-Python-PowerBI
```

### 2. Install Dependencies
```bash
pip install pandas numpy sqlalchemy psycopg2-binary
```

### 3. Run Data Preparation Notebook
Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter Notebook or VS Code and run all cells to clean data and upload it into PostgreSQL.

### 4. Run SQL Queries
Run the helper script to execute all 10 SQL queries directly against the database:
```bash
python3 run_sql_analysis.py
```

