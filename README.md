# SaaS Sales Data Analysis

## Introduction
This project provides a comprehensive data analysis for a fictitious B2B SaaS company specializing in sales and marketing software.  
As a Data Analyst, the goal is to leverage transactional data to provide actionable, data-driven insights to company stakeholders.

## Business Problem
The company aims to maximize profitability and optimize its sales strategy by gaining a deeper understanding of its operational performance.  
Key objectives include identifying which customer segments, products, and geographical regions drive sales and profit, as well as quantifying the impact of discounting on profitability.

## Business Questions
1. **Profitability & Segment Analysis**: Which customer segments (SMB, Strategic, Enterprise) are the most profitable, and how does this profitability compare across regions (AMER, EMEA, APAC)?
2. **Product Performance**: Which product categories generate the highest revenue and quantity sold? Are these top-selling products also the most profitable?
3. **Pricing Strategy & Hypothesis Testing**: Is there a statistically significant difference in average profit when customers receive a discount compared to when they do not?

## Dataset
The analysis uses the `SaaS-Sales.csv` dataset, which contains transactional sales data.  
[Dataset source](https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales)

Key columns include:
- **Order ID**: Unique order identifier  
- **Order Date**: Transaction date  
- **Region / Subregion**: Customer geography  
- **Segment**: Customer segment (Enterprise, SMB, Strategic)  
- **Product**: SaaS product sold  
- **Sales, Quantity, Discount, Profit**: Transactional performance metrics  

## Analysis Workflow
1. Data Preparation and Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Statistical Analysis (hypothesis testing on discount vs. profit)  
4. Visualization (Python & Tableau)  
5. Insights and Recommendations  

## Repository Structure
- `capstone_project_2.ipynb` : Jupyter Notebook containing the complete analysis  
- `README.md` : Project documentation
