# 📊 AdventureWorks Financial Sales Dashboard (Power BI)

## 🖼️ Dashboard Preview

### Page 1 — Executive Summary


![Executive Summary](page1_executive_summary.png)



### Page 2 — Regional Sales Analysis


![Regional Map](page2_regional_map.png)



### Page 3 — Product Performance Analysis


![Product Deep Dive](page3_product_deep_dive.png)



## 📋 Project Overview
An interactive 3-page Power BI dashboard built on the 
AdventureWorks dataset to analyze financial sales performance 
across products, regions, and time periods.

## 🗓️ Project Date
June 2026

## 📊 Key KPIs
| Metric | Value |
|--------|-------|
| Total Revenue | $9.82M |
| Total Orders | 10K |
| Total Profit | $4.12M |
| Profit Margin % | 42% |
| Total Returns | 2K |

## 📑 Dashboard Pages

### Page 1 — Executive Summary
- 5 KPI cards (Revenue, Orders, Profit, Margin, Returns)
- Top Products bar chart
- Monthly Revenue trend line chart (2015-2017)

### Page 2 — Regional Sales Analysis
- Interactive world map with revenue bubbles
- Revenue by Country bar chart
- Coverage: USA, Canada, UK, France, Germany, Australia

### Page 3 — Product Performance Analysis
- Top Products by Revenue bar chart
- Revenue by Category donut chart (Bikes 94.86%)
- Product Returns analysis stacked bar chart

## 🔍 Key Insights
- **Mountain-200** is the highest revenue product
- **Bikes** dominate with **94.86%** of total revenue
- Revenue shows consistent **upward trend** from 2015-2017
- **Water Bottle** has highest return rate
- All 6 countries show similar revenue distribution

## 🛠️ Tools & Technologies
- Microsoft Power BI Desktop
- Power Query (ETL & data transformation)
- DAX (KPI measures & calculations)
- Total Revenue = SUMX(Sales, Quantity * LOOKUPVALUE(Price))
Total Orders = DISTINCTCOUNT(OrderNumber)
Total Profit = Revenue - Cost
Profit Margin % = DIVIDE(Profit, Revenue)
Total Returns = COUNT(ReturnQuantity)

- Data Modeling (6 related tables)

## ⚙️ DAX Measures
Total Revenue = SUMX(Sales, Quantity * LOOKUPVALUE(Price))
Total Orders = DISTINCTCOUNT(OrderNumber)
Total Profit = Revenue - Cost
Profit Margin % = DIVIDE(Profit, Revenue)
Total Returns = COUNT(ReturnQuantity)
