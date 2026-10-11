# Sales Performance Analytics — Power BI

## Project Overview
An interactive Power BI dashboard designed to help senior management analyse sales revenue, profitability, regional performance, and product performance.

## Business Objectives
- Measure total sales revenue and profit.
- Compare revenue across regions.
- Identify top-revenue and loss-making products.
- Analyse monthly sales trends.
- Evaluate profit margin and negative-profit transactions.

## Tools Used
- Microsoft Power BI
- DAX
- Power Query
- Microsoft Excel

## Key Performance Indicators
- Total Revenue
- Total Profit
- Profit Margin %
- Negative Profit Rows

## Data Quality
The initial audit covered 21 columns and 10,194 reported data rows. No blank values or duplicate Row IDs were identified in the initial checks. Numeric columns and date fields were also inspected.

## Data Model
The report uses an Orders table and a Calendar table connected through Order Date to support time-based analysis.

## Business Insights
- Regional revenue differs across regions.
- Product revenue and profitability vary, highlighting products that warrant further investigation.
- Negative-profit transactions should be investigated to understand the impact of discounts and product costs.

*These are initial observations; quantify and validate the findings against the final report before presenting them as conclusions.*

## Limitations
Profit margin is calculated as total profit divided by total sales. Net profit margin is not reported because sufficient expense and tax data is unavailable.

## Project Structure
- `powerbi/` — Power BI report
- `screenshots/` — Dashboard screenshots
- `data/` — Dataset source and access instructions

## Power BI Report

[Download the Power BI report](./Project%201_Sales_Performance_Analysis/powerbi/Sales_Performance_Analytics.pbix)

## Dashboard Preview



## Author
Data Analytics Portfolio Project
