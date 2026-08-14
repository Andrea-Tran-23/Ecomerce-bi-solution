# Ecomerce-bi-solution
Business Intelligence solution analysing ecommerce sales performance, customer behaviour, product profitability and returns using Power BI.
# Ecommerce BI Analytics Solution


## Project Overview

This project develops a Business Intelligence solution to analyse ecommerce sales performance, customer behaviour, marketing performance, product profitability and return patterns.

The objective is to transform raw transaction data into actionable insights to support data-driven business decisions.


## Business Objectives

This project aims to answer the following business questions:

1. How is the overall sales performance over time?
2. Which product categories have the best performance and potential development opportunities?
3. Which customer segments contribute the most value?
4. Which marketing channels are most effective?
5. What factors contribute to product returns and customer churn rate?
6. How promotional activities and discounts campaigns contribute to business performance?
7. How the product returns affects to the overall business performance?

## Dataset Information

Source:
Kaggle Ecommerce Transaction Dataset

Period:
January 2010 - June 2011

Market:
United Kingdom


The dataset contains: 600.000+ records with 

- Transaction details
- Customer information
- Product information
- Marketing attributes
- Sales and cost information


## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Excel


## Data Preparation

Key data transformation steps:

- Converted data types
- Removed duplicate records
- Handled missing CustomerID values
- Identified returned products using negative quantities
- Created calculated fields for customer analysis


## Data Model

<img width="1038" height="627" alt="Screenshot 2026-08-13 at 15 48 23" src="https://github.com/user-attachments/assets/c1912a3b-637e-49ad-8b6d-a2eeafcb3534" />

The solution follows a star schema approach.

Fact Table:

- Fact_Sales


Dimension Tables:

- Dim_Date
- Dim_Product
- Dim_Customer
- Dim_Payment


## Key DAX Measures

Important business measures include:

- Total Revenue
- Total Profit
- Profit Margin
- Churn Rate
- Return Rate
- Returned Product Cost


## Report Structure


### Executive Overview

Provides high-level business performance:

- Revenue: The business generated $10.72 million in total revenue.
- Profit: Reached $4.32 million in total profit.
- Profit Margin: 40.29% with 34,000 orders from Jan 2010 to Jun 2011.
- Sales trend: peak season in March, May-Jun and November. November reached the highest point, generated 2 times higher in profit and revenue compared to the others 2 peak seasons .
- Churn rate: 63.78% - relatively high, indicating a significant customer retention challenge.
- Return rate: 10.03% - one in ten purchased products was returned.


### Sale Analysis

- Revenue: Toys and Clothing are the strongest-performing categories, generating the highest sales volume.
- Total Order: the monthly order pattern shows consistent seasonal trends.
- Return rate: Toys, kitchen and Electronic have high return rate (higher than the overall return rate - 10.03%).

  
### Product Analysis

- Product performance: strong product profitability, with an overall profit margin of approximately 40%.
- Category contribution: Toys, Stationery and Clothing contribute the most in the number of products sold.
- Cost performance: Toys generated the highest total return production cost due to its high return volume, while Clothing generated a similar level of return cost despite substantially fewer returned units.

### Customer Analysis

- Customer segments: The customer population is concentrated within the 21–60 age range, with the 21–40 age group representing the largest customer segment.
- Age groups over-60s are the third-largest segment with $2.59M — 24% of revenue and  lowest churn of any age group (60.72%) - the most retainable segment.


### Marketing Analysis:

- Marketing channels: Marketing performance is relatively balanced across acquisition channels. Email generating the highest revenue (approximately $2.6M) and profit (approximately $1.0M).
- Churn rate: Referral recording the highest churn rate (65.63%) and Email the lowest (61.17%).
- Promotion and Discount apply: Profit margin is flat - 40.16% to 40.79% across all groups. Discounts and promotions not only cost nothing in profit margin but also contribute more in profit and revenue.

## Key Insights

- Revenue reached $10.72M with a profit margin of 40.29%.
- Peak seasons: March, May-June and November.
- Stationery as a growth opportunity, demonstrated a strong balance between sales volume, revenue generation, low production cost, and low returns, making it a potential category for further investment.
- Kitchen requires further investigation as it records the second-highest number of returns despite having a lower sales volume.
- Upper 60 age group is valuable customer segment with lowest churn rate and contribute the third highest to revenue.
- More promotions and discounts should be run as positively contribute to profit and revenue.


## Dashboard Preview

<img width="973" height="547" alt="Screenshot 2026-08-10 at 18 52 17" src="https://github.com/user-attachments/assets/1e02f827-0612-47c5-b33f-931dabac71ca" />

<img width="1128" height="634" alt="Screenshot 2026-08-10 at 19 00 13" src="https://github.com/user-attachments/assets/7727423e-d800-4e6f-8b5c-c706dacb2ff3" />

<img width="1126" height="636" alt="Screenshot 2026-08-10 at 19 02 03" src="https://github.com/user-attachments/assets/98bb1007-b0d4-4deb-80b6-cb8dea36e4d2" />

<img width="1127" height="633" alt="Screenshot 2026-08-10 at 19 02 35" src="https://github.com/user-attachments/assets/2f563750-2563-4493-ac60-f77656b98b51" />


## Author

Andrea Tran

Master of Business Analytics
University of Wollongong
