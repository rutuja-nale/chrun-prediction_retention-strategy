# 🔄 Customer Churn Prediction & Retention Strategy Dashboard

## 📌 Project Overview

This project identifies high-risk churn segments in an e-commerce environment and presents actionable retention strategies. We use machine learning to predict churn and Power BI to visualize insights that help improve customer loyalty.

---

## 🎯 Business Objective

Customer retention is cheaper than acquisition. This project enables decision-makers to proactively reduce churn by understanding behavioral patterns and tailoring retention actions.

---

## 📊 Dataset Features

- `Customer_ID`, `Sign_Up_Date`, `Last_Active_Date`
- `Subscription_Plan`: Basic, Standard, Premium
- `Monthly_Purchases`, `Total_Spend`, `Support_Tickets`
- `Engagement_Score` (0–100)
- `Churn` (Target variable)

---

## 🧠 Machine Learning Model

Used logistic regression to predict churn likelihood. Key factors included:
- Engagement Score
- Support Tickets
- Monthly Purchase Frequency

Predictions were segmented into **Low**, **Medium**, and **High Risk** buckets.

---

## 📈 Power BI Dashboard

- **KPI Cards**: Churn %, Retention %, Avg Engagement
- **Visuals**:
  - Bar chart: Churn by Plan
  - Pie chart: Churned vs Active
  - Scatter: Spend vs Engagement
  - Table: Risk-based Recommendations
- **Filters**: Subscription Plan, Risk Segment

---

## 🛠️ Tools Used

- Python (pandas, scikit-learn)
- Power BI
- Faker (data generation)
- Jupyter Notebook

---

## 📁 Repository Structure
