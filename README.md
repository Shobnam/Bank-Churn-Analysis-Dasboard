# Bank-Churn-Analysis-Dasboard
Developed a customer churn analysis project using SQL and Power BI. Built a fact table from multiple datasets, created KPIs with DAX, and visualized churn drivers across demographics, geography, and products. Delivered insights on credit score, tenure, and active status to guide customer retention strategies.
# 📊 Bank Customer Churn Analysis – SQL + Power BI

## 📌 Project Overview
This capstone project analyzes **bank customer churn** using SQL for data modeling and Power BI for visualization.  
The objective is to identify drivers of churn, detect high-risk customers, and recommend retention strategies.  

The workflow included:
- Designing a **fact table** in SQL (star schema with dimension tables).  
- Writing **SQL queries** to calculate churn metrics, segment customers, and detect outliers.  
- Creating **DAX measures** in Power BI for KPIs like churn rate, average balance, and active members.  
- Building a **4-page interactive dashboard** to deliver business insights.  

---

## 🗂️ Dataset
The dataset consists of **7 tables**:  
- **Bank_Churn** – core customer attributes (tenure, balance, churn flag).  
- **CustomerInfo** – demographics (age, salary, DOJ, gender ID, geography ID).  
- **Gender** – gender categories.  
- **Geography** – regions (France, Spain, Germany).  
- **CreditCard** – credit card types.  
- **ActiveCustomer** – account activity categories.  
- **ExitCustomer** – churn reasons.  

---

## 🏗️ Data Modeling
- Built a **fact table** (`fact_bank_churn`) consolidating customer, geography, gender, credit, and churn details.  
- Applied a **star schema** design to support efficient querying and reporting.  

---

## 📊 Dashboard Pages

1. **Executive Overview**  
   - KPIs: Average Age, Balance, Tenure, Salary, Churn Rate.  
   - At-a-glance metrics for decision makers.
   - Screenshot https://github.com/Shobnam/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_index.png

2. **Customer Behavior**  
   - Churn by age group, tenure, and products.  
   - Insights: higher churn among customers aged 30–39 and those holding multiple products.
   - Screenshot https://github.com/Shobnam/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_customer_behavior.png

3. **Geography & Demographics**  
   - Churn by geography and gender.  
   - Maps + charts revealed **Germany** as the highest-risk geography.
   - Screenshot https://github.com/Shobnam/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_geography_and_demographic.png

4. **Risk & Predictions**  
   - Outlier detection in balances.  
   - High-risk customer segmentation by credit score, balance, and tenure buckets.
   - https://github.com/Shobnam/Bank-Churn-Analysis-Dasboard/blob/main/Bank_churn_analysis_risk_and_predictions.png

---

## 📌 Key Insights
- Churn rate = **20.37%** across all customers.  
- **Germany** shows the **highest churn rate**.  
- Customers with **low credit scores** churn more frequently.  
- Credit card ownership has **minimal impact** on churn.  
- Female customers exhibit slightly higher churn than males.  
- Customers with **3–6 years tenure** have the highest churn risk.  

---

## 🚀 Tools & Technologies
- **SQL (MySQL Workbench)** – data modeling & queries.  
- **Power BI** – dashboards, DAX measures, and visuals.  
- **Excel** – source data preparation.  

---

## 🎯 Business Impact
The analysis highlights **key churn drivers** and identifies **high-value at-risk customers**.  
This enables the bank to design **targeted retention campaigns**, improve customer satisfaction, and reduce revenue leakage.  

---
<img width="1312" height="746" alt="image" src="https://github.com/user-attachments/assets/57495a7e-65d7-4498-abd5-18ff119d37c6" />
<img width="1305" height="736" alt="image" src="https://github.com/user-attachments/assets/8ccce610-1eda-4795-af2d-40634377071a" />
<img width="1316" height="731" alt="image" src="https://github.com/user-attachments/assets/39c5ffe7-a113-4c4d-86d5-b2b25e6760f4" />
<img width="1341" height="751" alt="image" src="https://github.com/user-attachments/assets/ac92746c-67ea-432c-82d4-d6a25c0d2a98" />




