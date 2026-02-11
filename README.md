# E-Commerce Growth & Funnel Analysis

## Overview
This project focuses on analyzing an e-commerce business to understand conversion funnel performance, campaign ROI, product revenue, refunds, and customer behavior using SQL and Power BI. The goal is to turn raw data into clear, actionable business insights.

---

## Problem Statement
The business has fragmented data across website sessions, orders, and marketing campaigns, which makes it difficult to:
- Identify where users drop off in the conversion funnel  
- Understand which campaigns generate the highest revenue  
- Measure revenue loss due to refunds  
- Analyze new vs repeat customer behavior  

This results in revenue leakage, inefficient marketing spend, and low customer retention.

---

## Tools Used
- PostgreSQL (SQL: Joins, CTEs, Aggregations, Window Functions)
- Power BI (Data Visualization & Dashboarding)

---

## Data Overview
- ~400,000+ records across 6 tables  
- Tables used:  
  - website_sessions  
  - website_pageviews  
  - products  
  - orders  
  - order_items  
  - order_item_refunds  
- Data Type: Simulated e-commerce transactional data (Maven Analytics)

---

## Key Analyses
- Website conversion funnel analysis  
- Campaign performance and ROI analysis  
- Monthly revenue and order trend analysis  
- Product sales and refund analysis  
- New vs repeat customer analysis  

---

## Key Insights
- Only ~6.8% of sessions convert into orders, showing major funnel drop-offs  
- Non-brand campaigns drive most of the revenue  
- Revenue is highly dependent on a single product  
- Some top-selling products also cause high refund losses  
- Over 95% of revenue comes from new customers, showing low customer retention  

---

## Outcome
This project highlights conversion issues, revenue risks, and growth opportunities, and demonstrates how data analysis can support better marketing, product, and business decisions.
