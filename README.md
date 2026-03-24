# Metro Bank Analysis Project

![Project Banner](https://img.shields.io/badge/Metro_Bank_Analysis-Data_Analytics-blue)

---

## Project Overview.

This project provides a **comprehensive analysis of Metro Bank** across customers, accounts, transactions, branch operations, and complaints & risk, aiming to improve customer retention, enhance operational efficiency and reduce risk exposure. The analysis was conducted entirely in **Excel**.  

## Project Objectives
- Analyze customer demographics, loyalty, and income segments.
- Assess account and transaction trends to identify opportunities and risks.
- Evaluate branch performance and staff efficiency.
- Monitor complaints and fraud patterns to mitigate risk.
- Provide actionable recommendations for operational and strategic improvements.
---

## Data Description
This Dataset consists of 5 tables across each dimensions:
- **Customer Data:** Age, gender, income, occupation, loyalty, customer segment,region.
- **Account Data:** Account types (Savings, Checking, Credit Card, Loans), balances, and trends.
- **Transaction Data:** Volume, value, channels (POS, ATM, Online), and top merchants.
- **Branch Data:** Branch name, Revenue, profit, operating costs, staff count, and efficiency metrics.
- **Complaints Fraud & Risk Data:** Categories, resolution times, backlog, and customer segments, staus, fraud cases .


**Data Preparation:**
- Cleaned missing values, duplicates, and inconsistencies in the Power Query.
- Transformed dates and numeric fields for analysis.
- Created data model in power pivot for easy connection across the tables.
- Created Calculated columns for age group,income bracket,tenure,balance bracket,and risk level.
- Aggregated and merged datasets for multidimensional insights.

---

## Analysis & Methodology
 **Excel Tools:** Power Query, PivotTables, charts, Power Pivot measures.  
- **Metrics:** Revenue/profit/margin, customer growth/retention, complaint resolution, fraud cases, transaction volume & channels.  
- **Workflow:** Clean → Pivot → Measure → Visualize dashboards.


---

## Key Findings
## Customer Analysis
![dashboard](https://github.com/ARAFAH-LAWAL102/Metro-Bank-Analysis-Excel-Project/blob/main/Metro%20bank%20Customer%20db.png)

## Customer Insights & Actions

**1. Customer Base Decline & Loyalty**
- **Insight:** Total customers dropped 51% and average income declined 18%, yet 54% remain loyal (tenure 5–10 years). This signals a shrinking customer base but highlights a core group of high-value, long-term clients at risk if not engaged.
- **Action:** Offer personalized loyalty rewards to high-value, long-term customers, such as fee waivers, cashback, or priority service, to reduce churn and retain revenue.

**2. Demographics & High-Value Segments**
- **Insight:** Average customer age is 46 with balanced gender (51% F / 49% M). The Private segment earns the highest income ($118K), representing a strong revenue opportunity if effectively targeted.
- **Action:** Introduce tailored savings and investment products for Private customers, such as high-interest accounts or wealth management bundles, to increase future revenue.

**3. Geography & Generational Spread**
- **Insight:** Most customers are in the South region, dominated by Gen X and Boomers, while Gen Z is underrepresented. This limits long-term growth and adoption of digital services.
- **Action:** Launch digital-first accounts and targeted social campaigns for Gen Z, and expand marketing efforts in West and North regions to grow the customer base.

**4. Occupation & Income Distribution**
- **Insight:** Majority of customers are Engineers, Retired, or Teachers, while Traders are least represented. Misaligned products may reduce engagement and revenue potential.
- **Action:** Develop profession-specific products: salary loans and educational savings for teachers, retirement bundles for retirees, and investment portfolios for engineers to improve engagement and revenue.

## Account Analysis
![d](https://github.com/ARAFAH-LAWAL102/Metro-Bank-Analysis-Excel-Project/blob/main/Metro%20bank%20Account%20db.png)
## Account Insights & Actions

**1. Overall Decline vs LY**
- **Insight:** Total accounts decreased 44%, leading to a 43% decline in total balances. Additionally, 237 customers hold multiple accounts. This decline signals reduced engagement and underutilized customer relationships.
- **Action:** Identify inactive accounts and consolidate multiple accounts per customer. Launch targeted deposit campaigns to increase balances.

**2. Credit Score vs Loan Status**
- **Insight:** Approved loans dropped 100% in 2025. Rejected customers had an average score of 592, while approved customers averaged 581, showing inconsistencies. This exposes gaps in risk assessment and potential financial misalignment.
- **Action:** Review and standardize loan approval criteria to ensure credit scores accurately reflect risk.

**3. Most Used Product**
- **Insight:** Savings accounts make up 38% of total accounts, indicating customer preference and financial stability. This highlights opportunities to increase engagement through product upgrades.
- **Action:** Promote premium savings products or add rewards/incentives to encourage larger balances and engagement.

**4. High Balance Segment**
- **Insight:** Gen X holds the highest balances (31%), followed by Boomers. The Private segment holds the highest average balance ($275K). Underrepresented segments like Gen Z and Corporate customers represent untapped growth potential.
- **Action:** Offer targeted incentives to underrepresented segments to grow their balances.

**5. Loan Risk**
- **Insight:** Retailers borrowed the highest loans ($25M), increasing exposure to default risk. This highlights the need for stronger monitoring of high-risk segments.
- **Action:** Investigate segment repayment capacity and enforce stricter lending requirements for high-risk borrowers.

## Transaction Analysis
![k](https://github.com/ARAFAH-LAWAL102/Metro-Bank-Analysis-Excel-Project/blob/main/Metro%20bank%20Transaction%20db.png)
## Transaction Insights and Actions

**1. Transaction Volume Decline**
- **Insight:** Total transaction volume dropped 36%, resulting in $25.1M total value (38% decline YoY) and an average transaction of $5,013. This decline signals reduced customer engagement and potential revenue loss.
- **Action:** Promote digital payment adoption by offering incentives, rewards, or simplified payment options to increase usage and engagement.

**2. Credit Card Usage**
- **Insight:** Only 21% of payments are by credit card users while 79% are non-credit card users, indicating sharp decline in adoption. This shows missed opportunities for fee-based revenue and limits customer convenience.
- **Action:** Encourage credit card usage by offering rewards, cashback, or smoother payment options.

**3. Money Flow Imbalance**
- **Insight:** Withdrawals ($6.39M) exceed deposits ($6.20M), indicating a net outflow of funds. This imbalance can reduce liquidity and affect interest income.
- **Action:** Implement strategies to increase deposits, such as incentivized savings programs.

**4. Transaction Channels**
- **Insight:** POS is the most used channel, while online transactions are the lowest, highlighting underutilization of digital channels and potential friction in customer experience.
- **Action:** Improve online transaction UX to enhance smoothness and encourage adoption.

**5. Top Merchants**
- **Insight:** Airbnb and Apple dominate transaction volume, whereas Walmart and Amazon lag behind, signaling uneven merchant engagement and missed opportunities in key retail segments.
- **Action:** Expand merchant partnerships with top-performing merchants and key retailers like Walmart and Amazon to increase transaction volume.


## Branch Operational Analysis
![d](https://github.com/ARAFAH-LAWAL102/Metro-Bank-Analysis-Excel-Project/blob/74e007d271a2affa25a44b03cd21c51aa53d8ac7/Metro%20bank%20Branch%20db.png)
## Branch Performance Insights and Actions


**1. Uneven Profitability**
- **Insight:** Total profit across 20 branches is $38.25M, but high operating costs in some locations are eroding margins. South region generates 40% of revenue ($23.48M), while West Loganmouth loses $652K and Javiertown has the highest operating costs ($1.97M). North region achieves the highest efficiency with a 76% profit margin. This shows that branch performance is highly variable and operational inefficiencies are costing money.
- **Action:** Downsize or close underperforming branches (West Loganmouth, Javiertown) to stop losses, and apply North region's efficiency model to other locations.

**2. Staff vs Performance**
- **Insight:** More staff does not guarantee higher revenue; small, lean teams outperform larger teams. Misaligned staffing increases payroll overhead and reduces profitability.
- **Action:** Reallocate excess staff from low-performing branches to high-performing branches (South region) instead of hiring new personnel.

**3. Revenue Growth Opportunity**
- **Insight:** Investing in high-performing branches like South with tech and marketing upgrades could increase total revenue by an estimated $5M. Efficient operations and strategic investments amplify returns.
- **Action:** Focus capital and resources on the South region to scale revenue, leveraging its 40% share of total income.

**4. Cost Optimization**
- **Insight:** Closing or fixing the bottom 2 branches and adopting lean team models can reduce yearly losses by $1.1M+ and overhead by 15%.
- **Action:** Implement cost control measures, optimize payroll, and standardize operational best practices across all branches.

  

## Customoer Complaints and Risk Analysis
![d](https://github.com/ARAFAH-LAWAL102/Metro-Bank-Analysis-Excel-Project/blob/96229d94ff5cf3cb890df25f461c4a9c8748bc58/Metro%20Bank%20Risk%20db.png)

## Complaints Key Insights & Actions

**1.Backlog Bottleneck**
- **Insight:** 172 cases "In Progress," averaging 34 days to resolve; "Charges Disputes" lead with 184 cases. Delays on high-friction complaints risk customer churn.
- **Action:** Implement an automated triage system to resolve simple disputes within 48 hours, freeing senior agents for complex cases.

**2.High-Value Retention Risk**
- **Insight:** Premium earners generate 242 complaints, Retail customers 58% of total complaints. The most profitable segment is the most dissatisfied.
- **Action:** Establish a Priority Resolution Lane for Premium/Private segments with a 15-day SLA.

**3.Regional Hot Spots**
- **Insight:** South region accounts for 226 complaints, indicating branch-level operational or technical issues.
- **Action:** Conduct a South-region branch audit to identify root causes (staff, process, or infrastructure).

**4.Fraud & Product Vulnerability**
- **Insight:** 142 fraud cases, primarily in Checking Accounts (36 cases). Peaks occur in April and November; resolution averages 28 days—too slow to protect assets.
- **Action:** Deploy Predictive Fraud Alerts for Checking and Credit Card accounts during peak months to prevent losses proactively. 
---
## 🔹 Key Challenges Faced

- **Data Quality Issues:** Missing values, duplicates, and inconsistencies in the datasets required careful cleaning and validation.  
- **Complex Data Relationships:** Linking multiple tables across dimensions (Customer, Account, Transaction, Branch, Complaints & Risk) required thoughtful data modeling.  
- **Longitudinal Analysis:** Six years of historical data introduced inconsistencies and required normalization for accurate trends.  
- **Actionable Storytelling:** Translating raw data into insights that tell a business story required iterative dashboards and visualization.

---

## 🔹 Limitations

- **Data Completeness:** Some tables contain missing or inconsistent entries, which could slightly affect accuracy.  
- **Time Frame:** Analysis covers six years, providing a strong longitudinal view, but older data may be less reliable.  
- **Assumptions:** Calculated fields rely on assumptions that may not fully reflect real-world complexity.  
- **External Factors:** Market conditions, competitor actions, and regulatory changes are not captured, which could influence outcomes.

---

## Conclusion & Recommendations

- **Customer Retention:** Focus on high-value, loyal customers with personalized programs to reduce churn.  
- **Revenue Growth:** Target underrepresented segments (Gen Z, Corporate) and invest in high-performing branches to scale profits.  
- **Operational Efficiency:** Optimize or close low-performing branches and replicate best practices from top-performing locations.  
- **Risk Management:** Standardize loan approvals, implement predictive fraud alerts, and prioritize resolution for premium customers.  
- **Future Work:** Incorporate competitor data, macroeconomic indicators, and multi-year trends to strengthen insights and predictive capabilities.

