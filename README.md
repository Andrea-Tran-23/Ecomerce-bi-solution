# Ecomerce-bi-solution
Business Intelligence solution analysing ecommerce sales performance, customer behaviour, product profitability and returns using Power BI.
# Ecommerce BI Analytics Solution


## Project Overview

This project develops a Business Intelligence solution to analyse ecommerce sales performance, customer behaviour, marketing performance, product profitability and return patterns.

The objective is to transform raw transaction data into actionable insights to support data-driven business decisions.


## Business Objectives

This project aims to answer the following business questions:

- How is the overall sales performance over time?
- Which product categories generate the highest revenue and profit?
- Which product categories have potential development opportunities?
- Which customer segments contribute the most value?
- Which marketing channels are most effective?
- What factors contribute to product returns?


## Dataset Information

Source:
Kaggle Ecommerce Transaction Dataset

Period:
January 2010 - June 2011

Market:
United Kingdom


The dataset contains:

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

- Revenue
- Profit
- Profit Margin
- Sales trend
- Category performance


### Sale Analysis

Analyses:
- Profit and Profit Margin by Product Categories
- Total Order
- Return rate

  
### Customer Analysis

Analyses:

- Customer segments
- Age groups
- Marketing channels
- Customer churn


### Product Analysis

Analyses:

- Product performance
- Category contribution
- Return behaviour


## Key Insights

Examples:

- Revenue reached $10.72M with a profit margin of 40.29%.
- Clothing generated strong revenue despite lower sales volume, indicating higher product value.
- Product returns represented 23.11% of sold products, creating significant operational costs.
- Customer churn remains an important retention challenge.


## Dashboard Preview

<img width="973" height="547" alt="Screenshot 2026-08-10 at 18 52 17" src="https://github.com/user-attachments/assets/1e02f827-0612-47c5-b33f-931dabac71ca" />



## Author

Andrea Tran

Master of Business Analytics
University of Wollongong
