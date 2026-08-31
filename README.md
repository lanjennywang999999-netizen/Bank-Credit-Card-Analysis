# Bank-Credit-Card-Portfolio-P&L-Analysis

## Project Overview
This BI project is to demonstrate the performance of a simulated bank credit card dataset from financial perspective, risk management perspective and R&D perspective. It not only displays each key metric and also identify the key contributor(s) to profitability and loss using product, customer, merchant detail, and spending pattern etc. Besides, a research literature is reviwed and artificial neural network is adopted in the default data model for next default prediction. Finally, a data-driven approach is provided to address real world business problems. 

## Business Problem
Commercial bank experienced increased cash flow stress; the transaction volumes and # of cardholders are increasing steadily, offseting the cashback expenses, rewards costs, fee waivers, and delinquency. All the evidences point to an imbalanced growth between overall revenue and portfilio returns.

Management asks:
* Which income cateogory drives the revenue most?
* Where is the revenue leakage?
* Which cohorts are most profitablity?
* Which state/city has most/lowest profitability?
* How does default payment affect the profitability?
* What is probability of default payment in a future state?
* From risk management, can we group all the customers into three categories: Retained, Monitored, Risky?

## Analysis break-down and Objectives
* Conduct Portfolio level profitablity and performance analytics to access revenue, cost and margin.
* Identify key revenue and cost drivers and quantify their impact on portfolio profitability.
* Analyse revenue leakage across fee waviers, rewards and other incentives.
* Segment profitability and performance by customer, card product, and behavioural characteristics.
* Monitor portfolio health, delinquency trends, and emerging credit risk indicators.
* Develop interactive executive dashboards to translate complex analytics into actionable business insights.
* Provide data-driven recommendations to optimise profitability, improve revenue capture, and mitigate portfolio risk.

## Techniques, Tools amd Skills
* R (Joins, Window Functions, Aggregations, Subqueries, Mutation)
* R Package Development for repeated usage & potential scalability
* Data Cleaning & Validation
* Business Data Models Development
* Financial & Portfolio Analysis
* Customer Segmentation
* Revenue Profitability and Leakage Analysis
* Risk & Delinquency Analysis
* Business Intelligence Dashboard Development
* Data Storytelling
* Business Insights and Recommendation Framework
  
## About Datasets
### Source
* UCI Machine Learning Repository
* Hugging Face
### Data Set Information
This simulated dataset provides credit card transaction details including the demographics of customers, merchants, transaction datetime, amount, Is fraud flag, and also client default payments and bill statements.

* Customers	30,000
* Analysis Period	6 Months
* Transactions	300,000+
* Tables	5
* Dashboard Pages	4  

### Attributes Information
This analysis employed a binary variable in default data model, default payments (No=0/Yes=1) as response variable, and the rest variables are used as explanation variables.
### Data Model
* Cardholders
* Transactions
* Billing
* Delinquency
* Defaults

## Approach
The analysis was completed across five business areas:
1. Portfolio Profitability
    * Revenue Performance
    * Cost Structure
    * Net Profit
    * Profit Margin
    * Monthly Profitability Trends
2. Product & Customer Profitability
    * Card Type Performance
    * Income Segment Analysis
    * Customer Profitability
    * Geographic Profitability
    * Segment-level Profitability
3. Revenue Leakage
    * Cashback Costs
    * Rewards Costs
    * Fee Waivers
    * Revenue Leakage
    * Leakage Ratio
4. Portfolio Risk
    * Delinquency Trends
    * Outstanding Balance Exposure
    * Credit Utilization
    * Risk Concentration
    * Overall Portfolio Health
5. Customer Spending Behavior
    * Spending Category Analysis
    * Transaction Trends
    * Customer Value Analysis
    * Category-level Spend
    * Customer Spending Patterns

## Dashboard Pages (TBA)
* Page 1 — Executive Portfolio Overview - 
Provides an executive summary of portfolio performance including revenue, profit, profit margin, revenue composition, product profitability, and delinquency KPIs.
<img width="903" height="506" alt="Executive" src="https://github.com/lanjennywang999999-netizen/Bank-Credit-Card-Analysis/blob/main/Executive.png" />


* Page 2 — Product Profitability & Revenue Leakage
Analyzes profitability across Classic, Gold, and Platinum cards while identifying major revenue leakage from cashback, rewards, and fee waivers.
<img width="903" height="512" alt="Product" src="https://github.com/lanjennywang999999-netizen/Bank-Credit-Card-Analysis/blob/main/Product.png" />

 * Page 3 — Risk & Delinquency
Evaluates delinquency movement across DPD buckets, outstanding balance exposure, and customer risk concentration.
<img width="876" height="488" alt="Risk" src="https://github.com/lanjennywang999999-netizen/Bank-Credit-Card-Analysis/blob/main/Risk.png" />

*  Page 4 — Portfolio Health Tracking and Customer Behavior
Analyzes portfolio health distribution, watchlist customers, high-risk accounts, and credit utilization.
<img width="894" height="501" alt="Protfolio" src="https://github.com/lanjennywang999999-netizen/Bank-Credit-Card-Analysis/blob/main/Portfolio.png" />


## Key Business Findings and Insights
* The portfolio generated $48M revenue and $12M profit at a 24.11% margin.
* Interchange revenue is the largest revenue contributor (43%), while rewards point remains the biggest profitability leak. 
* Platinum and Gold cards deliver the same high margin (34%), while classic card shows strong relationship with outstanding bal. 
* The portfolio maintains a 13.90% delinquency rate requiring ongoing risk monitoring.
* Rewards accounts for the majority of revenue leakage across all card products and largely concentrated along eastern coast.
* The portfolio has $238.21M avg. in outstanding exposure, and highest average exposure sits at 6th day. 
* A total of 8.3K customers are in the 2nd DPD category, bring around $3.6M profits. 
* Classic cardholders contribute the largest share of delinquent accounts and require focused monitoring.
* Metro tends to have higher delinquency rate than regions.
* ~ 6.7K cardholders are predicted to default potentially next month with est. $863M credit limit totally.

## Business Recommendations
* 1. Optimize Classic Card Cashback Strategy - Reduce cashback on low-margin categories while maintaining attractive rewards on high-value spending categories to reduce revenue leakage.
* Expected Impact: Improve profitability by reducing unnecessary cashback costs.

* 2. Upgrade High-Value Classic Customers - Identify high-spending Classic cardholders and promote Gold cards to improve long-term portfolio profitability through a more efficient reward structure.

* 3. Launch Early Delinquency Intervention - Implement automated payment reminders, EMI restructuring, and proactive customer outreach for Watchlist customers before they migrate into higher DPD buckets.

* 4. Review Platinum Fee Waiver Policy - Restrict fee waivers to eligible customer scenarios to reduce unnecessary revenue leakage without impacting customer retention.

* 5. Focus Customer Acquisition on Spending Behavior - Prioritize acquisition campaigns targeting profitable spending patterns rather than geographic location to improve overall portfolio quality.

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

