#  Customer Churn Analysis & Customer Intelligence

An end-to-end Data Analytics project that analyzes customer churn behavior using **PostgreSQL**, **Python**, and data visualization techniques. This project combines SQL querying, data cleaning, feature engineering, exploratory data analysis (EDA), KPI generation, and business intelligence to uncover customer churn patterns and provide actionable retention strategies.

---

## 📌 Overview

Customer churn is one of the most critical business challenges for subscription-based companies. Losing customers directly impacts revenue and long-term growth.

This project performs an in-depth churn analysis by integrating customer demographics, subscription history, and customer support data from a PostgreSQL database. The objective is to identify high-risk customers, measure business impact, and generate insights that help improve customer retention.

The project demonstrates a complete data analytics workflow from database connectivity to business reporting.

---

## 🎯 Objectives

- Analyze customer churn behavior
- Calculate business KPIs
- Identify high-risk customers
- Measure revenue loss due to churn
- Analyze customer support impact on churn
- Compare churn across subscription plans and regions
- Generate actionable business recommendations

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Database | PostgreSQL |
| Database Connectivity | SQLAlchemy, Psycopg2 |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook |

---

# 📂 Database Schema

The project uses a **PostgreSQL relational database** consisting of three interconnected tables.

## 1. Customer Table

- Customer ID
- Name
- Gender
- Country
- State
- Date of Birth
- Interests
- Pincode

---

## 2. Subscription Table

- Customer ID
- Subscription Start Date
- Renewal Date
- Subscription Type
- Plan Type
- Contract Type
- Monthly Charges
- Cancellation Date
- Cancellation Reason
- Customer Lifetime Value (CLTV)
- Churn Score

---

## 3. Support Table

- Customer ID
- Complaint Date
- Escalations
- Customer Satisfaction Score (CSAT)
- Comments

---

# 🔄 Project Workflow

## Step 1 — Data Extraction

- Connected Python with PostgreSQL
- Executed SQL queries
- Joined multiple relational tables
- Imported data into Pandas DataFrames

---

## Step 2 — Data Cleaning

Performed various preprocessing tasks including:

- Handling missing values
- Removing duplicates
- Correcting data types
- Renaming columns
- Data quality checks
- Formatting date columns

---

## Step 3 — Feature Engineering

Created additional business features such as:

- Customer Tenure
- Active Customer Flag
- Churn Flag
- Retention Status
- Customer Age
- Revenue Metrics
- Service Usage Duration

---

## Step 4 — Exploratory Data Analysis (EDA)

Performed detailed analysis using

- GroupBy Operations
- Aggregate Functions
- Pivot Tables
- Customer Segmentation
- Distribution Analysis
- Correlation Analysis

---

## Step 5 — Data Visualization

Generated visualizations including

- Customer Churn Distribution
- Churn by Subscription Plan
- Churn by State
- Monthly Churn Trend
- Revenue Analysis
- Customer Segmentation
- Customer Tenure Distribution
- Support Escalation Analysis

---

# 📈 Key Performance Indicators (KPIs)

The following business KPIs were calculated:

- Customer Churn Rate
- Retention Rate
- Average Revenue Per User (ARPU)
- Customer Lifetime Value (CLTV)
- Revenue at Risk
- Average Customer Tenure
- Churn by Subscription Plan
- Churn by State
- Monthly vs Annual Contract Churn
- Escalation Rate
- Average Complaints per Customer
- Support Escalation vs Churn Correlation

---

# 📊 Business Questions Answered

- Which subscription plans experience the highest churn?
- Which states contribute the most to customer churn?
- What is the average customer lifetime?
- How much revenue is at risk due to churn?
- Does customer support influence churn?
- Which customers should be prioritized for retention?
- How does contract type affect customer retention?

---

# 💡 Business Insights

The analysis provides insights into:

- Customer churn trends
- Customer retention performance
- Revenue leakage
- Customer lifetime value
- High-risk customer identification
- Subscription performance
- Customer support effectiveness

---

# 📚 Python Libraries Used

```python
pandas
numpy
matplotlib
seaborn
sqlalchemy
psycopg2
jupyter
```
