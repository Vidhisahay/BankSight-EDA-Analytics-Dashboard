# BankSight: Banking Data Analytics and Dashboard

## Executive Summary
Banksight analyzed data from 3,000 high-net-worth retail banking customers to uncover patterns in deposit behavior, loyalty engagement, and churn risk. A key finding revealed that 44% of customers in the entry-level Jade tier hold the highest average deposits ($697K) exceeding even Platinum-tier clients. This exposes a $12M annual revenue risk from potential outflows by under-engaged, high-value customers. 

To mitigate this, Banksight proposes the Deposit Loyalty Accelerator (DLA) a precision-targeted program offering fee waivers and yield incentives to upgrade Jade clients. Early projections show 12% higher retention, 8% growth in deposits, and a 3:1 ROI within a year. Insights are visualized in an interactive Power BI dashboard enabling executives to monitor loyalty health, segment customers, and respond to data-driven alerts in real time.

![Banking Dashboard](https://github.com/Vidhisahay/BankSight-EDA-Analytics-Dashboard/blob/main/Pictures/Dashboard%20Mockup.png)

## Company Summary
BankSight Analytics is a mid-sized financial institution committed to leveraging data-driven insights to enhance customer experience and operational efficiency. The bank offers a wide range of retail and corporate banking services, focusing on personalized financial solutions, digital transformation, and sustainable growth through advanced analytics.

## Business Problem
The main challenge is a 15–20% yearly churn among Jade-tier customers, who hold 44% of total deposits but cause major balance fluctuations. In 2025, U.S. banks are facing intense competition from digital-first players like Chime and Ally, driving over $50B in deposit shifts each year. The dataset reflects this trend Jade customers maintain higher deposits (~$697K, 5% above Silver/Gold) but have shorter tenures (7–10 years), showing strong acquisition but weak retention. This churn translates to $2K–$3K in lost annual revenue per customer, or about $12M across 500 clients. While risk remains steady (avg. 2.26), 30% of lending capacity stays unused, and with deposits declining 1.1% in early 2025, banks could face a 5–8% portfolio shrinkage by 2026 if retention strategies aren’t strengthened.

## Detailed Insights from Data Exploration

1. **Loyalty and Deposit Dynamics**
   - Jade tier clients joined most recently (average 8.5 years ago) but control the largest share of deposits.
   - Platinum clients, despite 14+ years of tenure, average $85K less in deposits.
   - This suggests acquisition channels are highly effective, but onboarding and progression pathways are broken.
   - **Actionable Implication:** A one-time upgrade nudge could convert transient wealth into lifelong relationships.

![Loyalty and Deposit Dynamics](https://github.com/Vidhisahay/BankSight-EDA-Analytics-Dashboard/blob/main/Pictures/Loyalty%20%26%20Deposit%20Dynamics.png)

2. **Fee Structure and Financial Engagement**
   - $684K average deposits (vs. $650K for Mid-fee)
   - Higher business lending ($863K avg.)
   - Lower risk weighting (2.24 avg.)
   - **This validates that** fee tolerance signals trust and intent to deepen the relationship a leading indicator for cross-sell success.

![Fee Structure and Financial Engagement](https://github.com/Vidhisahay/BankSight-EDA-Analytics-Dashboard/blob/main/Pictures/Fee%20Structure%20%26%20Financial%20Engagement.png)

3. **Demographic and Risk Patterns**
   - Australians own 1.59 properties on average and carry low risk (2.21): ideal for property-secured credit products.
   - Europeans (44% of base) dominate High-fee adoption and show balanced portfolios.
   - Asians and Africans skew younger and higher-risk: candidates for digital-first, low-friction offerings.

![Demographic and Risk Patterns](https://github.com/Vidhisahay/BankSight-EDA-Analytics-Dashboard/blob/main/Pictures/Demographics%20%26%20Risk%20Patterns.png)

4. **Correlation Matrix Highlights**
   - Among 10 financial variables, the strongest relationship is between Bank Loans and Business Lending (r = 0.42).
   - This confirms a clear SME customer segment that bundles personal and business debt, a prime target for integrated cash flow solutions.

![Correlation Matrix Highlights](https://github.com/Vidhisahay/BankSight-EDA-Analytics-Dashboard/blob/main/Pictures/Lending%20vs%20Loan%20Relationship.png)

## Business Recommendation: Deposit Loyalty Accelerator Program
To address retention gaps, deploy a tiered upgrade initiative leveraging data signals like high Jade deposits and fee tolerance. Core Components are:

- **Targeting:** Segment 1,000 Jade clients with >$500K deposits (33% of tier); prioritize High-fee Europeans (48% overlap). 
- **Incentives:** 6-month fee rebate (up to $200) for Silver upgrade; 2% APY bonus on linked deposits for Gold. 
- **Implementation:** Digital nudge via app/email, A/B test vs. control group.
- **Metrics & ROI:** Track retention (+12% target), deposit growth (+8%), churn reduction.
