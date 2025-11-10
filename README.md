# Metro Bank Analysis Project

![Project Banner](https://img.shields.io/badge/Metro_Bank_Analysis-Data_Analytics-blue)

---

## Project Overview
This project analyzes Metro Bank’s performance across multiple dimensions:

- **Customer Base:** Demographics, loyalty, income, accounts, and high-value segments.
- **Accounts & Transactions:** Total accounts, balances, deposits, loans, transaction volumes, and payment channels.
- **Branch Operations:** Revenue, profit, costs, staff efficiency, and regional performance.
- **Complaints & Risk:** Complaint trends, resolution efficiency, fraud cases, and high-risk segments.

The goal is to identify operational inefficiencies, customer retention challenges, and opportunities for revenue growth.

---

## Data Description
- **Customer Data:** Age, gender, income, occupation, loyalty, customer segment,region.
- **Account Data:** Account types (Savings, Checking, Credit Card, Loans), balances, and trends.
- **Transaction Data:** Volume, value, channels (POS, ATM, Online), and top merchants.
- **Branch Data:** Branch name, Revenue, profit, operating costs, staff count, and efficiency metrics.
- **Complaints Fraud & Risk Data:** Categories, resolution times, backlog, and customer segments, staus, fraud cases .


**Data Preparation:**
- Cleaned missing values, duplicates, and inconsistencies in the Power Query.
- Transformed dates and numeric fields for analysis.
- Created Calculated columns for age group,income bracket,tenure,balance bracket,and risk level.
- Aggregated and merged datasets for multidimensional insights.

---

## Project Objectives
- Analyze customer demographics, loyalty, and income segments.
- Assess account and transaction trends to identify opportunities and risks.
- Evaluate branch performance and staff efficiency.
- Monitor complaints and fraud patterns to mitigate risk.
- Provide actionable recommendations for operational and strategic improvements.

---

## Analysis & Methodology
- **SQL:** Data extraction, joins, aggregations, and trend calculations.
- **Excel / Power BI:** Visualization, KPI dashboards, and storytelling.
- **Metrics Used:**
  - Revenue, profit, and margin per branch
  - Customer growth/decline and retention
  - Complaint resolution rate and backlog
  - Fraud cases and high-risk segments
  - Transaction volumes and channel usage

---

## Key Findings

- **Customer Base:** Decline in customers (-51%) and accounts (-44%), with premium and retail segments most valuable.
- **Accounts & Transactions:** Savings accounts most used (38%), total transaction volume/value declined 36–38%, low credit card usage (21%).
- **Branch Performance:** 20 branches generated $59.42M revenue and $38.25M profit (64% margin); Lisaville and South Region lead performance.
- **Staff Efficiency:** No clear correlation between staff count and revenue; fewer-staff branches often perform better.
- **Complaints & Risk:** Complaints decreased 28%, but resolution is slow (~30 days); 54 active fraud cases mainly in checking, savings, and credit cards.
- **High-Value Insights:** Gen X and Private customers hold highest balances; retail customers drive loan exposure.

---

## Recommendations
- **Customer Strategy:** Retain premium and high-balance customers; improve acquisition.
- **Branch & Staff Efficiency:** Optimize staffing, replicate high-efficiency branches, reduce operational costs.
- **Transaction & Product Strategy:** Promote digital payments, increase credit card adoption, incentivize savings.
- **Risk & Complaints Management:** Enhance fraud controls, reduce complaint resolution times, prioritize high-risk segments.
- **Strategic Growth:** Leverage top merchants and highly engaged customers for targeted campaigns.

---

## Dashboard & Visualization
- Power BI dashboards include:
  - Customer demographics and loyalty
  - Branch revenue, profit, and staff efficiency
  - Transaction volumes, channels, and top merchants
  - Complaints and fraud trends
- Features dynamic filters for region, branch, customer segment, and time.

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/metro-bank-analysis.git

