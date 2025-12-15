
# Sales Performance & Customer Segmentation Dashboard (YoY Analysis)
link:https://public.tableau.com/app/profile/suriya.raj4719/viz/Book1_17604986820510/Salesdashboard#2

 
 ## Project Overview

This project focuses on building an interactive Tableau dashboard to analyze Year-over-Year (YoY) sales performance and customer behavior using a pre-cleaned, ready-made dataset.

The goal is to enable business users to quickly compare current vs previous year performance, identify key growth drivers, and understand customer value through intuitive, self-service dashboards.



## Business Objective

Sales and business stakeholders need a clear YoY performance view to answer:

-How are sales, profit, and quantity changing year over year?

-Which products and customers contribute most to revenue?

-How does customer behavior vary across segments and time?

-Where should leadership focus to improve growth and profitability?


 ## Data Source

The project uses a ready-made analytical dataset with a star-schema structure:

Fact Table: Sales transactions
(Sales, Profit, Quantity, Order Date, Product ID, Customer ID)

Dimension Tables:

Products (Category, Subcategory, Product Name)

Customers (Segment, Geography, Demographics)

No external data cleaning or ETL was performed.
The dataset was assumed to be clean and analysis-ready.



## Analytical Approach

The project follows a BI dashboarding workflow commonly used in analytics teams:

-Understanding Business Requirements

-Defined KPIs required for YoY analysis

-Identified stakeholder questions around growth and customers

-Metric Design in Tableau

-Created YoY calculations (CY vs PY)

-Built growth rate metrics

-Designed customer lifetime sales measures

-Dashboard Development

-Implemented dynamic year selection using Tableau parameters

-Used FIXED LOD expressions for consistent KPIs

-Built interactive charts and filters

-Designed navigation between dashboards

-Interpreted trends across time, products, and customers

-Focused on business impact rather than visual complexity



## Key Metrics & KPIs

The dashboards highlight decision-critical metrics:

### YoY Performance KPIs

-Total Sales (Current Year vs Previous Year)

-Total Profit (Current Year vs Previous Year)

-Total Quantity (Current Year vs Previous Year)

-YoY Growth %


### Customer Metrics

-Customer Lifetime Sales

-Customer Segmentation (VIP / Regular / New)

-Top Customers by Revenue

-Quantity Contribution by Segment

## Dashboard Structure

 ### 1.Sales Dashboard

Focuses on overall business performance and trends.

Key Visuals:

YoY KPI summary cards

Sales trend over time (CY vs PY)

Monthly profit comparison

Top products by sales and profit

Quantity by segment

Business Value:
Helps leadership monitor growth, seasonality, and product contribution.

## 2️.Customer Dashboard

Focuses on customer value and segmentation.

Key Visuals:

Customer segmentation breakdown

Customer lifetime sales

Top customers by revenue

Customer distribution by segment and geography

Business Value:
Supports customer prioritization and retention strategies.


 
 ## 3.Interactivity & UX Features

Dynamic Year Parameter
Users can select any year as the “current year” for YoY comparison.

Interactive Filtering
All charts can be used as filters to explore deeper insights.

Navigation Buttons
Easy switching between Sales and Customer dashboards.

Clean, Executive-Friendly Layout
Designed for fast consumption and clarity.



## Tools Used : Tableau

Tableau Public — Dashboarding, calculations, parameters, LODs

GitHub — Project documentation and portfolio hosting
