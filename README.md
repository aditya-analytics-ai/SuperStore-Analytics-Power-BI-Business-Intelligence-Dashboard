# SuperStore Analytics – Power BI Business Intelligence Dashboard
An interactive Business Intelligence Command Center built in Power BI on the Sample Superstore dataset — featuring 3 fully linked dashboards covering Customer, Product, and Time Series analysis.

## Project Structure
├── Sample_Superstore.csv       # Raw source data
├── Bi_analysis.pbix            # Power BI report file (all dashboards)
└── README.md

## Project Overview
This Power BI report provides unified analytics across sales, products, customers, and operations. It includes a custom Home Page that acts as a navigation hub, allowing users to jump directly into any of the 3 dashboards.

"Unified analytics across sales, products, customers, and operations."


## Data Preparation (Power BI)
The following cleaning steps were performed inside Power BI (Power Query):
StepWhat was doneColumn renamingStandardized column names (spaces removed)Date formattingConverted Order_Date and Ship_Date to proper Date typePostal code fixFormatted Postal_Code as text with leading zerosDuplicate removalRemoved duplicate rows on Order_ID + Product_IDRedundant column removalDropped Row_ID and Country columnsCalculated columnsCreated Days_to_Ship = Ship_Date - Order_DateDate hierarchyExtracted Order_Year, Order_Month, Order_Quarter

## Dashboards
Home Page – Navigation Hub
A branded landing page titled "Business Intelligence Command Center" with 3 clickable buttons for navigating between dashboards:

## Customer Centric Dashboard
## Product Centric Dashboard
## Time Series Dashboard


## Dashboard 1 – Customer Centric
KPI Cards:
MetricValueTotal Customers32Repeat Customer Rate53.13%Avg Order Value444.90Total Orders32
Visuals & Filters:
VisualDescriptionSales & Profit by SegmentGrouped bar — Consumer, Home Office, CorporateCount of Order_ID by SegmentPie chart — Consumer 68.75%, Corporate 21.88%, Home Office 9.38%Top 5 Customers by ProfitHorizontal bar — Maria Etezadi leads at 1.34KSales & Profit by RegionBar chart — South leads with 9.3K salesCustomer Loyalty: Order FrequencyHistogram showing repeat buying behaviorTop 5 States by SalesKentucky leads at 4.4KFiltersState · Product Name · Year/Month · Region (Map)

## Dashboard 2 – Product Centric
KPI Cards:
MetricValueTotal Products6Total Revenue343.88Profit Margin %31.08%Top CategoryOffice Supplies
Visuals & Filters:
VisualDescriptionTotal Sales & Profit by CategoryGrouped bar by categoryProfit Margin by CategoryBar chart showing margin % per categoryTotal Profit by Sub-CategoryHorizontal bar — Appliances highlightedTotal Sales by Sub-CategoryHorizontal bar — Appliances at 344Category, Discount & ProfitScatter plot showing discount vs profit impactFiltersCategory · Sub-Category · Product Name · Year/Month · Region · Segment

## Dashboard 3 – Time Series
KPI Cards:
MetricValueTotal Sales2.30MOverall Growth %51.37%Peak MonthNovemberAvg Ship Time3.96 days
Visuals & Filters:
VisualDescriptionYearly Sales & ProfitBar chart — 484K (2014) → 733K (2017) growthYoY Growth % by YearBar chart — 2016 was peak growth year (~28%)Seasonality: Avg Sales per Order by MonthMonthly bar — March & January peakAvg Ship Time by Ship ModeStandard Class 5.0 days → Same Day 0.0 daysMonthly Sales & Profit Trend with Rolling AverageDual-axis line chart with 3M rolling average overlayFiltersRegion · State · Year/Month · Category · Ship Mode

## Key Business Insights

✅ Consumer segment dominates with 68.75% of all orders
✅ South region leads in total sales; East has lowest revenue
✅ 53% repeat customer rate — strong customer retention
✅ Office Supplies is the top category with 31.08% profit margin
✅ Higher discounts directly reduce profit (visible in scatter plot)
✅ Sales grew from 484K → 733K between 2014 and 2017 (51.37% growth)
✅ November is the peak sales month — Q4 seasonal demand spike
✅ First Class shipping averages just 2.2 days vs Standard Class at 5.0 days


## Tools Used
ToolPurposePower BI DesktopDashboard creation & data modelingPower QueryData cleaning & transformationDAXCalculated columns & KPI measuresSample Superstore DatasetSource data

# Author
Adityamohan Singh

GitHub: @your-username
LinkedIn: your-linkedin
