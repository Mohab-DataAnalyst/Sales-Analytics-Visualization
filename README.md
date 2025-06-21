![Logo](https://s33892.pcdn.co/wp-content/uploads/2020/07/A-sales-professional-draw-growth-graph-of-his-business-1200x385.jpg)

# 📊 Sales Profitability and Revenue Trends Dashboard (Power BI)

This interactive Power BI dashboard project focuses on analyzing sales profitability, tracking revenue performance, and evaluating sales reps' effectiveness over time. The project uses clean visuals, dynamic filters, and a star schema data model to provide meaningful insights for decision-makers.

## 📁 Project Overview

The dashboard focuses on:
- **Average Daily Gross Profit by Product and SalesRep**
- **Gross Profit Trends Across Fiscal Periods**
- **Revenue vs 12-Month Rolling Revenue Trends**
- **Revenue Breakdown by Product and Representative**

### ⚙️ Data Model

The model follows a star schema and consists of:
- **Transactions Table** (Fact): Captures revenue, gross profit, COGS, discounts, units sold, and key calculated metrics.
- **Date Table** (Dimension): Enables time intelligence using fiscal year, quarter, and month.
- **Product Table** (Dimension): Contains product-level details such as category, supplier, and retail price.
- **SalesReps Table** (Dimension): Holds sales rep data including region.

All relationships are one-to-many and optimized for efficient filtering and cross-report interactions.

### 📈 Key Visuals

- **Avg Daily Gross Profit Report**:
  - Bar chart of Avg Daily Gross Profit by Product
  - Line chart of Gross Profit trend across Fiscal Periods
  - Avg Daily Gross Profit by Sales Representative
  - KPIs showing:
    - Total Revenue
    - Total COGS
    - Gross Profit
    - Gross Profit %

- **Revenue Breakdown by Product and Representative**:
  - Bar chart of Revenue by Product
  - Matrix displaying Avg Daily Revenue by SalesRep and Product

- **Revenue vs 12-Month Rolling Revenue Trends**:
  - Line graph comparing Avg Revenue vs 12-Month Rolling Avg Revenue
  - Matrix with Avg Daily Revenue, Avg Revenue, and 12-Month Rolling Avg Revenue by Year and Month
  - Year Slicer for interactive analysis

- **Comprehensive Fiscal Period Analysis**:
  - Bar chart of Total Gross Profit by Fiscal Period
  - Line graph of Avg Daily Gross Profit by Fiscal Period
  - Matrix with detailed product-level KPIs: % Gross Profit, Avg Daily Gross Profit, Total Units, Revenue, COGS, and Gross Profit
  - Region slicer for focused regional insights

### 🧠 Skills Demonstrated
- Power BI Data Modeling & Star Schema Design
- DAX for custom metrics and time-based calculations
- Rolling Average & Fiscal Analysis
- Interactive Dashboards with Drillthroughs and Slicers
- KPI Visualization & Trend Analysis

---

## 🖥️ Dashboard Snapshots
<p align="center">
  <img src="https://github.com/Mohab-DataAnalyst/Sales-Performance-and-Customer-Trends-Visualization/blob/main/Sales%20Data%20Model.PNG?raw=true" width="800" height="500"/>
  <img src="https://github.com/Mohab-DataAnalyst/Sales-Performance-and-Customer-Trends-Visualization/blob/main/sales%20report.PNG?raw=true" width="800" height="500"/>
  <img src="https://github.com/Mohab-DataAnalyst/Sales-Performance-and-Customer-Trends-Visualization/blob/main/customer%20&%20sales%20trends.PNG?raw=true" width="800" height="500"/>
</p>
---

## 📌 Insights Extracted
- Top-performing products and sales reps by Avg Daily Gross Profit
- Fiscal periods showing highest gross profitability
- 12-month rolling averages that help smooth seasonal revenue fluctuations
- Direct revenue contribution by individual products and representatives

---

## 📎 Acknowledgements
- This project was inspired by [@ExcelIsFun.](https://youtu.be/nBu1Bqa1jjs?si=FyWBH1msXKctGrWT)
- Dataset in description [here.](https://youtu.be/nBu1Bqa1jjs?si=FyWBH1msXKctGrWT)
## ✍️ Author
- 👤 [@Mohab-DataAnalyst](https://github.com/Mohab-DataAnalyst)

