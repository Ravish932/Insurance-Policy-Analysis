# 📊 Insurance Policy Analysis Dashboard – Power BI

## 📁 Project Overview
This project focuses on analyzing **10 years of insurance data (2015–2025)** to help company understand policy performance, premium trends, customer behavior, and maturity outcomes.

The dashboard provides a **single source of truth** for stakeholders across sales, underwriting, and finance—presenting clear, interactive insights that support decision-making.

---

## 🎯 Business Problem
Insurance companies often struggle to **track premiums, maturity amounts, customer segments, and financial performance** across multiple policy types and regions.  
Data is scattered, insights are slow, and decision-making becomes reactive.

👉 This dashboard solves the problem by consolidating all insurance data and converting it into **actionable insights**, enabling stakeholders to evaluate:

- Which policy types generate the highest revenue  
- State-wise premium performance  
- Customer demographics and purchasing behavior  
- Investment vs. maturity value analysis  
- Profitability and underwriting expenses  
- Individual customer-level policy details  

---

## 🛠️ Tools & Technologies
- **Power BI** – Dashboarding & Data Modeling  
- **Power Query** – ETL (Cleaning & Transformation)  
- **DAX** – Measures, Calculated Columns & Dynamic Parameters  
- **Row-Level Security (RLS)** – Role-based restricted access  

---

## 📌 Key Features

### ✅ 1. Summary Report
- Total Policies  
- Total Premium  
- Total Annual Premium  
- Total Premium Paid  
- Total Premium Payable  
- Underwriting Expenses  
- Searchable customer table with policy details  

---

### ✅ 2. Insurance Overview Report
- Premium distribution by **State, Policy Type, Policy Name, Year, Occupation**  
- **Dynamic Visual Parameter** enabling users to switch between metrics:  
  - Total Annual Premium  
  - Total Premium  
  - Total Premium Paid  
  - Total Premium Payable  
  - Underwriting Expenses  
  - Profit/Gain  
- All visualizations update automatically based on selected metric  

---

### ✅ 3. Financial Performance Report
- **Investment vs. Maturity Value Analysis**  
  - Investment = Total Premium Amount  
  - Maturity Value = Total Maturity Amount  
  - Average Annualized ROI shown as a line chart  
- Revenue breakdown  
- Profitability insights  

---

## 🔐 Row-Level Security (RLS)
RLS ensures that different stakeholders only access relevant data:

- **Agent-level:** Can view only their customers  
- **Manager-level:** Can view data for their region  
- **Executive-level:** Full dataset access  

This implementation enhances data confidentiality and simulates a real-world reporting environment.

---

## 📈 Insights Generated
- Identified high-performing states and policy types  
- Detected top customers by premium contribution  
- Highlighted low-profit policies due to high underwriting expenses  
- Compared investment vs. maturity value to understand customer ROI  
- Analyzed customer demographics & behavior patterns  

---


