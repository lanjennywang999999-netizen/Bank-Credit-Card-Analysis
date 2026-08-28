# Bank-Credit-Card-Portfolio-P&L-Analysis

## Project Overview

This project analyzes the financial performance of a simulated credit card portfolio to identify the key drivers of profitability, revenue leakage, customer behavior, and credit risk.

Using SQL, Power BI, Python, and Excel, the analysis evaluates how different card products, customer segments, spending patterns, and delinquency levels impact overall portfolio performance. The project provides data-driven recommendations to improve profitability while reducing operational and credit risk.

## Business Problem

A retail bank has experienced steady growth in credit card customers and transaction volume, but overall profitability has not improved at the same pace. Rising cashback expenses, reward costs, fee waivers, and customer delinquency are reducing portfolio returns.

Management wants to answer the following questions:

* Which card products generate the highest profitability?
* Which revenue sources contribute the most?
* Where is revenue leaking?
* Which customer segments are most profitable?
* How does delinquency affect profitability?
* Which customers should be retained, upgraded, or monitored?
## Project Objectives
* Analyze overall portfolio profitability.
* Identify major revenue and cost drivers.
* Measure revenue leakage from cashback, rewards, and fee waivers.
* Evaluate profitability across customer segments and card products.
* Assess portfolio health and delinquency risk.
* Build an interactive executive dashboard for business decision-making.
* Recommend strategies to improve profitability and reduce risk.
## Dataset Overview
Metric	Value
* Customers	10,000
* Analysis Period	12 Months
* Transactions	150,000+
* Tables	4
* Dashboard Pages	5
### Data Model
* Cardholders
* Transactions
* Billing
* Delinquency
## Tools & Technologies
* SQL (MySQL) – Data extraction and business analysis
* Power BI – Interactive dashboard development
* Excel – Data validation and exploratory analysis
* GitHub – Version control and project documentation
*  ## Analytical Approach
The analysis was completed across five business areas:
* ### 1. Portfolio Profitability
* Revenue
* Cost
* Net Profit
* Profit Margin
* Monthly Performance
* ### 2. Product Profitability
* Card Type Performance
* Income Segment Analysis
* Customer Profitability
* City-wise Profitability
* ### 3. Revenue Leakage
* Cashback Cost
* Reward Cost
* Fee Waivers
* Leakage Ratio
* ### 4. Portfolio Risk
* Delinquency Analysis
* Outstanding Balance Exposure
* Credit Utilization
* Portfolio Health
* ### 5. Customer Spending Behaviour
* Spending Categories
* Transaction Analysis
* Customer Value
* Category-wise Spend
## Dashboard Pages
* Page 1 — Executive Portfolio Overview - 
Provides an executive summary of portfolio performance including revenue, profit, profit margin, revenue composition, product profitability, and delinquency KPIs.
<img width="903" height="506" alt="Executive" src="https://github.com/user-attachments/assets/a34af390-8361-49ac-b9df-cde65659996b" />


* Page 2 — Product Profitability & Revenue Leakage - 
Analyzes profitability across Classic, Gold, and Platinum cards while identifying major revenue leakage from cashback, rewards, and fee waivers.
<img width="903" height="512" alt="Product" src="https://github.com/user-attachments/assets/26063535-c88b-436b-acc6-8d80d03f6143" />

 * Page 3 — Risk & Delinquency - 
Evaluates delinquency movement across DPD buckets, outstanding balance exposure, and customer risk concentration.
<img width="876" height="488" alt="Risk" src="https://github.com/user-attachments/assets/496d2adb-678f-4b72-9dc5-d4f86327e2e9" />

*  Page 4 — Portfolio Health - 
Analyzes portfolio health distribution, watchlist customers, high-risk accounts, and credit utilization.
<img width="894" height="501" alt="Protfolio" src="https://github.com/user-attachments/assets/b06cf9a3-9a42-409a-a626-64298dd9d931" />

* Page 5 — Customer & Spend Behaviour - 
Explores customer profitability, spending categories, city-wise performance, and spending patterns.
<img width="908" height="514" alt="Customer" src="https://github.com/user-attachments/assets/470a97ca-9a53-486c-85ea-d42b96464c7b" />

## Key Business Findings
* Portfolio generated ₹50.38M in total revenue and ₹17.63M in net profit, achieving a 34.99% profit margin across 10,000 customers over 12 months.
* Interchange revenue contributed ₹17.75M (35.23% of total revenue), making it the largest individual revenue source and highlighting the importance of customer spending behaviour.
* Cashback cost reached ₹19.78M, making it the largest cost component and the primary driver of portfolio revenue leakage.
* Platinum cards achieved the highest profit margin (47.78%), while Classic cards generated the highest revenue (₹21.46M) but the lowest profit margin (25.47%), indicating lower cost efficiency.
* The portfolio recorded a 15.23% delinquency rate, with 571 customers in the 90+ DPD bucket representing the highest credit risk segment requiring immediate attention.
* Travel accounted for ₹638M (approximately 55% of total portfolio spend), making it the highest spending category, while city-wise profitability remained relatively consistent across all locations.
## Business Recommendations
* 1. Optimize Classic Card Cashback Strategy - Reduce cashback on low-margin categories while maintaining attractive rewards on high-value spending categories to reduce revenue leakage.
* Expected Impact: Improve profitability by reducing unnecessary cashback costs.

* 2. Upgrade High-Value Classic Customers - Identify high-spending Classic cardholders and promote Gold cards to improve long-term portfolio profitability through a more efficient reward structure.

* 3. Launch Early Delinquency Intervention - Implement automated payment reminders, EMI restructuring, and proactive customer outreach for Watchlist customers before they migrate into higher DPD buckets.

* 4. Review Platinum Fee Waiver Policy - Restrict fee waivers to eligible customer scenarios to reduce unnecessary revenue leakage without impacting customer retention.

* 5. Focus Customer Acquisition on Spending Behaviour - Prioritize acquisition campaigns targeting profitable spending patterns rather than geographic location to improve overall portfolio quality.

## Skills Demonstrated
* SQL (Joins, CTEs, Window Functions, Aggregations, Subqueries)
* Data Cleaning & Validation
* Business KPI Development
* Financial & Portfolio Analysis
* Customer Segmentation
* Revenue Leakage Analysis
* Risk & Delinquency Analysis
* Power BI Dashboard Development
* Data Storytelling
* Business Recommendation Framework

## Credit Card Term Glossary
| Term       | Description       |
| -------------- | -------------- |
|Balance Transfer|A balance transfer enables the transfer of the balance of one credit card to another. The percentage shown in the table is the interest rate p.a. which applies to the balance transfer, the length of time which the interest rate is valid for, and then the interest rate which it reverts to.|
|Sign up Bonus Points|A reward offered when you open a credit card. Eligibility conditions apply, see the provider's website for full details.|
|0% balance transfer offers|A balance transfer is offered at 0% for a limited period. After which point a higher interest will be applied. Other fees and charges as well as conditions and limits may apply.|
|Reward Program|The Reward Program is available directly with Airline Provider(s) or points are able to be transferred. Conditions may apply.|
|Profile|The type of credit card a consumer would like to compare.|
|Balance Transfer Fee|The fee charged for a balance transfer to a card. This can be a set dollar amount or a percentage of the balance being transferred. Other fees and charges may apply.|
|Monthly Spend|The estimated amount of money a consumer will spend on their credit card per month|
|Points never expire|The rewards points accrued on the card will never expire. Conditions may apply and can be subject to change.|
|Apply in full online|The card account can be opened in full online. This includes ID verification, uploading supporting documentation, and approval.|
|24hr Online Approval|The average approval time, when the card is applied for online, is within 24 hours. Conditions may apply.|
|Interest free days|The maximum number of days from the purchase date before interest will start being charged. Conditions may apply.|
|Features|Available features of a credit cards product.|
|Special Offers|Special offers are available on the credit card. Conditions and eligibility requirements may apply.|
|0% additional card holders|The Credit Card does not charge an annual fee on additional card holders. Limits may apply.|
|$0 late payment fee|The Credit Card does not charge a late payment fee if the minimum payment is not made by the due date. Conditions may apply.|
|0% currency conversion fee|The Credit Card does not charge a foreign currency conversion fee when making a purchase in another currency. Other fees and charges may apply.|
|No annual fee|The credit card has no annual fee. Conditions may apply.|
|0% purchase rate offers|An introductory rate of 0% is offered for a limited time, then will revert to a higher rate. Other fees and charges as well as conditions and limits may apply.|
|Introductory purchase rate offers|A lower introductory rate on new purchases is offered for new members for a limited time, then will revert to a higher rate. Conditions may apply.|
|Points uncapped|There is no limit which points no longer accrue for a given period.|
|Redeem points for cash|Points earned with the Rewards Program can be redeemed for cash or credit.|
|Partner Airlines|Partnered airlines which allow the transfer of rewards points to frequent flyer points.|
|Fraud detection available|The Credit Card has systems which pick up suspicious spending. Refer to provider for further details.|
|Redeem points at point of sale|Points earned with the Rewards Program can be redeemed at Point of Sale.|
|Annual fee|The Credit Card standard annual fee that has been calculated based on spend amount entered. Other fees may apply.|
|Purchase rate p.a.|The interest rate per annum which applies to regular purchases. Where promotional purchase rates are applicable we will show the introductory purchase rate p.a. and the period it’s valid for (if applicable) then the regular purchase rate p.a. which it reverts to. Rates are updated daily.|
|Balance transfer rate p.a.|The interest rate per annum which applies to the balance transfer, the length of time which the interest rate is valid for, the interest rate which the card reverts to, then the fee for the balance transfer, if applicable. Conditions and limits may apply.|
|First year annual fee|The total annualised fee charged in the first year of holding the card, including any automatic first-year fee waivers or reductions and, if applicable, rewards program fees. Fee waivers or reductions based on spend thresholds may also apply, and fees may change after the first year.|
|Reward Points per $1|The rate at which points are earned for each dollar spent. Points shown in the table reflect the card's default rewards program and are based on regular spend, if applicable. The name of the points earned is displayed in the subtext, and points may be converted to partnered rewards programs where eligible. See the provider's website for full details.|
|Delinquency|It occurs when a credit card holder failed to make at least the minimum payment on time|
|Profitability|The ability to generate revenue that exceeds its expenses.|
|Revenue Contributor|The driver(s) of Revenue including transaction say interchange, credit say interest income, and credit card usage etc.|
|Revenue Leakage|The money has been earned but loss thereafter due to a lack of awareness.|
|Customer Segment|A customer segment is a district group of customers who share similar characteristics, behaviors, or needs.|

