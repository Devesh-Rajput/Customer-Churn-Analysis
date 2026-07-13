# Customer Churn Analysis & Customer Intelligence

An end-to-end Data Analytics project that analyzes customer churn behavior for a subscription-based platform. The project combines SQL, Python, data visualization, and business intelligence techniques to identify churn patterns, customer segments, revenue loss, and retention opportunities.

---

## 📌 Project Overview

Customer churn is one of the most important business metrics for subscription-based companies. This project analyzes customer demographics, subscription information, and customer support interactions to understand:

- Which customers are churning
- Why they are leaving
- Which customer segments are at high risk
- Revenue impact of churn
- Actionable business recommendations to improve customer retention

The complete workflow includes SQL data extraction, data cleaning, feature engineering, exploratory data analysis, KPI calculation, visualization, and business insight generation.

---

## 🎯 Objectives

- Analyze customer churn rate
- Calculate important business KPIs
- Identify high-risk customer groups
- Study churn across subscription plans and locations
- Measure revenue loss due to churn
- Generate actionable retention strategies

---

## 🛠 Tech Stack

- Python
- SQL (SQLite)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset Structure

The project uses three relational tables.

### Customer Table

- Customer ID
- Name
- Gender
- Country
- State
- Date of Birth
- Interests
- Pincode

### Subscription Table

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

### Support Table

- Customer ID
- Complaint Date
- Escalations
- CSAT Score
- Comments

---

## ⚙️ Project Workflow

### 1. Data Extraction

- Connect SQLite database
- Retrieve data using SQL queries
- Merge multiple relational tables

### 2. Data Cleaning

- Handle missing values
- Rename columns
- Fix data types
- Remove inconsistencies
- Perform quality checks

### 3. Feature Engineering

Created additional business metrics such as:

- Customer Tenure
- Active Customers
- Churn Flag
- Retention Status
- Revenue Metrics
- Customer Age

### 4. Exploratory Data Analysis

Performed analysis using:

- GroupBy
- Aggregations
- Pivot Tables
- Statistical summaries

### 5. Data Visualization

Visualizations include:

- Churn Distribution
- Churn by Subscription Plan
- Churn by State
- Monthly Churn Trend
- Revenue Analysis
- Customer Segmentation
- Customer Tenure Distribution

---

## 📈 Key Performance Indicators (KPIs)

- Customer Churn Rate
- Retention Rate
- Average Revenue Per User (ARPU)
- Customer Lifetime Value (CLTV)
- Revenue at Risk
- Average Customer Tenure
- Churn by Plan Type
- Churn by State
- Escalation Rate
- Average Complaints per Customer
- Support Escalation vs Churn Correlation

---

## 📊 Business Insights

The analysis helps answer questions such as:

- Which subscription plans have the highest churn?
- Which regions contribute the most to customer loss?
- What is the revenue impact of churn?
- Does customer support affect churn?
- Which customer segments should be targeted first?
- How does contract type influence retention?

---

