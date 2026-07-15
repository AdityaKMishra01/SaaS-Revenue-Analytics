# 📊 SaaS Revenue Analytics Dashboard

> End-to-End SaaS Revenue Analytics Project using **Python, SQL, Pandas, DAX, and Power BI**

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
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
│
├── dashboards
    ├── SaaS_Revenue_Analytics.pbix
    ├── Executive_Overview.png
    ├── Revenue_Movement.png
    └── Plan_Performance.png
    

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

# 📊 Power BI Dashboard

## Executive Overview

![Executive Dashboard](Dashboard/Executive%20Overview%20Dashboard.png)

Highlights:

- Total MRR
- Active Customers
- Latest NRR
- Expansion MRR
- Revenue Lost
- Monthly Revenue Trend

---

## Revenue Movement Analysis

![Revenue Movement](Dashboard/Revenue%20Movement%20Dashboard.png)

Highlights:

- Expansion Revenue
- Contraction Revenue
- Churn Revenue
- Top Revenue Customers
- Monthly Revenue Movement

---

## Plan Performance Analysis

![Plan Performance](Dashboard/Plan%20Performance%20Dashboard.png)

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

# 📷 Dashboard Preview

- Executive Overview
- <img width="532" height="657" alt="Screenshot 2026-07-06 225212" src="https://github.com/user-attachments/assets/04e3bcb1-f32b-402a-a907-0c9ba2e4ffa3" />

- Revenue Movement
- <img width="321" height="498" alt="Screenshot 2026-07-06 225620" src="https://github.com/user-attachments/assets/c7b474a9-74f2-4bda-99e7-453a02558a48" />

- Plan Performance
- <img width="487" height="577" alt="Screenshot 2026-07-06 230528" src="https://github.com/user-attachments/assets/c19978e9-3527-4497-b89c-02b33f66587c" />


---

# 👨‍💻 Author

**Aditya Mishra**

📧 Email: adityamishra1872@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/adityakmishra01

💻 GitHub: https://github.com/adityakmishra01


⭐ If you found this project helpful, consider giving it a star.
