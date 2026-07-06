# 📊 SaaS Revenue Analytics Dashboard

> End-to-End SaaS Revenue Analytics Project using **Python, SQL, Pandas, DAX, and Power BI**

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![SQL](https://img.shields.io/badge/SQL-Analytics-blue)
![Power%20BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)

---

# 📌 Project Overview

This project analyzes SaaS subscription data to evaluate customer growth, recurring revenue, revenue retention, subscription performance, and business health.

The project demonstrates a complete analytics workflow starting from raw subscription data and ending with an interactive Power BI dashboard.

The analysis focuses on industry-standard SaaS metrics including:

- Monthly Recurring Revenue (MRR)
- Net Revenue Retention (NRR)
- Expansion Revenue
- Contraction Revenue
- Churn Revenue
- Active Customers
- Revenue by Subscription Plan

---

# 🎯 Business Problem

Subscription businesses rely on recurring revenue for long-term growth.

Business leaders need answers to questions such as:

- How is Monthly Recurring Revenue changing over time?
- Which subscription plans generate the highest revenue?
- How many customers remain active every month?
- How much revenue is lost due to churn?
- What is the company's Net Revenue Retention?
- Which customers generate the highest recurring revenue?

This project answers these questions through data analysis and visualization.

---

# 🛠 Tech Stack

| Tool | Purpose |
|-------|----------|
| Python | Data Cleaning & Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Computation |
| SQL | Business Analysis |
| Power BI | Dashboard Development |
| DAX | KPI Measures |
| Jupyter Notebook | Analysis |
| Git & GitHub | Version Control |

---

# 📂 Repository Structure

```text
SaaS-Revenue-Analytics
│
├── README.md
├── requirements.txt
├── LICENSE
│
├── data
│   ├── raw
│   └── processed
│
├── notebooks
│   ├── 01_Data_Cleaning.ipynb
│   ├── 02_MRR_Analysis.ipynb
│   ├── 03_NRR_Analysis.ipynb
│   └── 04_Revenue_Analytics.ipynb
│
├── sql
│   └── saas_analysis.sql
│
├── dashboards
│   ├── SaaS_Revenue_Analytics.pbix
│   ├── Executive_Overview.png
│   ├── Revenue_Movement.png
│   └── Plan_Performance.png
│
└── images
    └── workflow.png
```

---

# 🔄 Project Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
MRR Analysis
      │
      ▼
NRR Analysis
      │
      ▼
Revenue Analytics
      │
      ▼
SQL Business Analysis
      │
      ▼
Power BI Dashboard
```

---

# 📒 Notebook Description

## 01️⃣ Data Cleaning

Performed data preprocessing and feature engineering.

Tasks:

- Data inspection
- Missing value handling
- Date conversion
- Feature engineering
- Status creation
- Export cleaned dataset

Outputs:

- cleaned_subscription_data.csv

---

## 02️⃣ MRR Analysis

Calculated important SaaS revenue metrics.

Tasks:

- Monthly Recurring Revenue (MRR)
- Previous Month MRR
- Revenue Movement
- Expansion Revenue
- Contraction Revenue
- Churn Revenue

Outputs:

- final_mrr_table.csv
- monthly_expansion.csv
- monthly_contraction.csv
- monthly_churn.csv

---

## 03️⃣ NRR Analysis

Calculated Net Revenue Retention.

Tasks:

- Starting MRR
- Ending MRR
- Expansion
- Contraction
- Churn
- Monthly NRR %

Outputs:

- nrr_df.csv

---

## 04️⃣ Revenue Analytics

Performed business-focused analysis.

Tasks:

- Monthly Revenue Trend
- Active Customers
- Revenue by Plan
- Revenue Distribution
- Business Insights

Outputs:

- monthly_mrr.csv
- monthly_mrr_byPlan.csv
- total_active_cust.csv

---

# 🗄 SQL Analysis

SQL queries were written to answer business questions such as:

- Monthly Revenue Trend
- Revenue by Subscription Plan
- Active Customers
- Top Revenue Customers
- Monthly Customer Growth
- Revenue Distribution

---

# 📊 Power BI Dashboard

## Executive Overview

![Executive Dashboard](dashboards/Executive_Overview.png)

Highlights:

- Total MRR
- Active Customers
- Latest NRR
- Expansion MRR
- Revenue Lost
- Monthly Revenue Trend

---

## Revenue Movement Analysis

![Revenue Movement](dashboards/Revenue_Movement.png)

Highlights:

- Expansion Revenue
- Contraction Revenue
- Churn Revenue
- Top Revenue Customers
- Monthly Revenue Movement

---

## Plan Performance Analysis

![Plan Performance](dashboards/Plan_Performance.png)

Highlights:

- Revenue by Plan
- Revenue Distribution
- Plan-wise Revenue Trend
- Customer Distribution

---

# 📈 Key Performance Indicators

- Monthly Recurring Revenue (MRR)
- Net Revenue Retention (NRR)
- Active Customers
- Expansion Revenue
- Contraction Revenue
- Churn Revenue
- Revenue Lost

---

# 📌 Key Business Insights

- Monthly Recurring Revenue showed a consistent upward trend throughout the analysis period.
- Active customer count increased steadily, indicating healthy customer acquisition.
- Enterprise subscriptions contributed the largest share of recurring revenue.
- Revenue lost due to churn and contraction highlights opportunities to improve customer retention.
- Net Revenue Retention remained above 90% in the latest reporting period, indicating strong recurring revenue retention.

---

# 🚀 Future Improvements

- Churn Prediction using Machine Learning
- Revenue Forecasting
- Customer Lifetime Value (CLV) Analysis
- Real-Time Dashboard using SQL Database
- Automated ETL Pipeline
- Power BI Service Deployment

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/SaaS-Revenue-Analytics.git
```

Move into the project folder

```bash
cd SaaS-Revenue-Analytics
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open the notebooks in Jupyter Notebook or VS Code.

---

# 📷 Dashboard Preview

Replace these images with your dashboard screenshots.

- Executive Overview
- Revenue Movement
- Plan Performance

---

# 👨‍💻 Author

**Aditya Mishra**

Aspiring Data Analyst

📧 Email: your-email@example.com

🔗 LinkedIn: https://linkedin.com/in/your-profile

💻 GitHub: https://github.com/yourusername

---

# 📜 License

This project is licensed under the MIT License.

---

⭐ If you found this project helpful, consider giving it a star.
