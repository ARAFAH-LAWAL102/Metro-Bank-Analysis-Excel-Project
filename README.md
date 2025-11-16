# Metro Bank Analysis Project

![Project Banner](https://img.shields.io/badge/Metro_Bank_Analysis-Data_Analytics-blue)

---

## Business Problem
Metro Bank is experiencing declining customer activity, rising operational costs, and inconsistent branch performance. Management wants a full end-to-end analysis to understand what is happening across the business and identify where interventions are needed.

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

**1. Customer Base Decline & Loyalty:** Total customers dropped **51%**, average income down **18%**, but **54% are loyal** (tenure 5–10 years).  
**Action:**  Offer **personalized loyalty rewards** to high-value, long-term customers, such as fee waivers, cashback, or priority service, to reduce churn and retain revenue. 

**2. Demographics & High-Value Segments:** Average age **46**, gender balanced (**51% F / 49% M**). The **Private segment** has the highest income (**$118K**).  
**Action:**  Introduce **tailored savings and investment products** for Private customers, such as high-interest accounts or wealth management bundles, to increase future revenue.  

**3. Geography & Generational Spread:** Most customers are in the **South region**, dominated by Gen X and Boomers; **Gen Z is underrepresented**.  
**Action:**  Launch **digital-first accounts** and targeted social campaigns for Gen Z, and expand marketing efforts in **West and North regions** to grow the customer base.  

**4. Occupation & Income Distribution:** Majority are **Engineers, Retired, or Teachers**, with Traders least represented.  
**Action:**  Develop **profession-specific products**: salary loans and educational savings for teachers, retirement bundles for retirees, and investment portfolios for engineers to improve engagement and revenue.  


- **Customer Retention:** Implement targeted retention programs for high-value and at-risk customers to address the 51% decline.  
- **Financial Incentives:** Offer personalized promotions or loyalty rewards for segments with declining average income to boost engagement.  
- **Focus on High-Value Segments:** Prioritize **Private segment** and **Gen X/Boomers** for premium services and investment products.  
- **Regional Strategy:** Strengthen presence and marketing efforts in the **South region**, where most customers are located.  
- **Youth Engagement:** Develop tailored products and campaigns for **Gen Z** to grow future high-value customers.  
- **Occupation-Specific Solutions:** Create specialized services for underrepresented occupations (e.g., **Traders**) to diversify the customer base.


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

