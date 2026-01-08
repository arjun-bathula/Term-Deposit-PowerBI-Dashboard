# Term Deposit Marketing Campaign – Power BI Executive Dashboard

## Project Overview
This project presents an executive-level Power BI dashboard analyzing a bank’s term deposit telephonic marketing campaign. The objective is to evaluate campaign performance, identify high-conversion customer segments, and provide actionable recommendations to improve marketing efficiency and reduce operational costs.

The dashboard focuses on clear storytelling, data accuracy, and executive-friendly insights to support strategic decision-making.

---

## Business Context
Term deposits are a major revenue source for banks. While telephonic marketing campaigns are effective, they are also costly. This analysis helps identify which customers are most likely to subscribe, enabling the bank to target the right segments and optimize call center investments.

---

## Dataset
- **Source:** Banking Dataset – Marketing Targets (Kaggle)
- **File Used:** `Banking data - Term deposits.xlsx`
- The dataset includes customer demographics, financial attributes, previous campaign outcomes, and subscription results.

---

## Target Persona
**Executive / Senior Leadership**

The dashboard is designed to provide quick, high-level insights while allowing deeper exploration where required.

---

## Dashboard Details
- **Tool:** Microsoft Power BI
- **Canvas Size:** 1400 x 900
- **Report Pages:** 2  
  - Campaign Overview  
  - Subscription Analysis

---

## Key KPIs
- **Total Customers Contacted:** 45K  
- **Total Subscriptions:** 5,289  
- **Campaign Success Rate:** 11.70%  
- **Non-Conversion Rate:** 88.30%  
- **Previously Contacted Customers (%):** 18.26%

These KPIs provide an immediate snapshot of campaign effectiveness and customer engagement.

---

## Page 1 – Campaign Overview
This page provides a high-level summary of campaign performance:
- Overall campaign success and non-conversion rates
- Success rate by contact type (cellular, telephone, unknown)
- Time-based performance trends by month
- Top 5 job categories with the highest subscription success
- Distribution of subscription outcomes (Yes vs No)

### Key Insights
- **Cellular contact** has the highest success rate (~14.9%), outperforming traditional telephone outreach.
- Campaign performance varies significantly by month, indicating opportunities for seasonal optimization.
- **Students and retired customers** are among the top-performing job segments.

---

## Page 2 – Subscription Analysis
This page provides deeper insights into customer behavior and campaign drivers:
- Success rate by age group
- Impact of previous campaign outcomes
- Engagement and success rate by balance group
- Success rate by education level
- Combined impact of housing loan, personal loan, and credit default status

### Key Insights
- Customers aged **60+** show the highest campaign success rate, making them a high-priority segment.
- Customers with a **previous successful campaign outcome** are significantly more likely to subscribe again.
- Higher account balance groups generally show better engagement and conversion.
- Customers **without personal loans, housing loans, or credit defaults** have the highest subscription success rates.

---

## Business Recommendations
- Prioritize telephonic outreach to **senior customers (60+)**, especially those who are retired or students.
- Focus campaigns on **cellular contact channels** to improve conversion efficiency.
- Deprioritize customers with existing loan obligations or credit defaults to reduce low-yield calls.
- Leverage previous campaign outcomes to retarget customers with a history of success.
- Optimize campaign timing based on high-performing months to maximize ROI.

---

## Data Integrity & Performance
- Source data was validated for row counts and consistency.
- Clear KPI definitions were applied to avoid ambiguity.
- Measures were used for key calculations to ensure performance and accurate filtering.
- Visuals and slicers were optimized for fast load times and executive usability.

---

## Files Included
- `Bank - Term Deposits.pbix` – Power BI dashboard
- `Bank - Term Deposits.pdf` – Executive-ready exported report
- `Banking data - Term deposits.xlsx` – Source dataset
- `README.md` – Project documentation

---

## Outcome
This dashboard enables executives to quickly assess telephonic campaign effectiveness, identify high-value customer segments, and make informed decisions to optimize marketing strategies while reducing costs and improving conversion rates.
