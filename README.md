# 📊 Sales & Financial Analysis – AtliQ Hardware

## 📌 Project Overview
This project focuses on **Sales and Financial Performance Analysis** for **AtliQ Hardware** using historical sales data.  
The analysis was carried out in **Microsoft Excel**, and the insights were exported as **PDF reports** for easy consumption.

All PDF files in this repository are **generated directly from the Excel workbook**, which contains the complete dataset, calculations, pivot tables, and dashboards.

---

## 🎯 Objectives
- Analyze **net sales performance** across fiscal years (2019–2021)
- Evaluate **profitability** using Gross Margin and GM%
- Perform **customer-wise and market-wise analysis**
- Compare **actual performance vs targets**
- Identify growth trends and business insights

---
## 🗃️ Data Files Description

The project follows a **star-schema–like structure**, with one fact table and multiple dimension tables to support sales and financial analysis.

### 📄 Fact Tables

- **fact_sales_monthly.csv**  
  Contains monthly sales transaction data at a granular level.  
  Key details include:
  - Date (Month, Fiscal Year)
  - Product, Customer, and Market references
  - Sales quantity and revenue metrics  
  This table serves as the core transactional dataset for time-based sales analysis.

- **fact_sales_monthly_with_cost.csv**  
  An enriched version of the monthly sales data that includes cost information.  
  Additional metrics include:
  - Cost of Goods Sold (COGS)
  - Gross Margin
  - Gross Margin Percentage (GM%)  
  This file is primarily used for **profitability and P&L analysis**.

---

### 📁 Dimension Tables

- **dim_customer.csv**  
  Contains customer master data used for customer-wise analysis.  
  Typical attributes include:
  - Customer name
  - Customer type (e.g., Retailer, Distributor, Online)
  - Associated market or region

- **dim_market.csv**  
  Holds geographical and market-related information.  
  Used to analyse sales performance across:
  - Countries
  - Regions
  - Sub-zones

- **dim_product.csv**  
  Contains product-level master data.  
  Key attributes include:
  - Product name
  - Product category and segment
  - Division  
  Enables product-wise and category-level analysis.

---

### 📊 Usage in Analysis
- **Fact tables** provide measurable metrics such as sales, cost, and margin.
- **Dimension tables** provide descriptive context for slicing and dicing the data by:
  - Time
  - Customer
  - Market
  - Product
---

## 📑 Report Descriptions

- **Sales Report.pdf**  
  Overall customer-wise net sales performance.

- **India_sales.pdf**  
  Customer-level sales analysis specific to the Indian market.

- **Market Performance.pdf**  
  Country-wise performance compared against targets.

- **Net Sales Performance.pdf**  
  Global customer-wise sales growth with YoY comparison.

- **P&L.pdf**  
  Profit & Loss summary by fiscal year.

- **P&L by Months.pdf**  
  Monthly and quarterly Profit & Loss analysis.

- **P&L for markets.pdf**  
  Market-wise profitability and gross margin analysis.

- **GM%(sub_zone).pdf**  
  Gross Margin % trends across sub-zones and quarters.

---

## 🛠️ Tools & Techniques
- **Microsoft Excel**
  - Pivot Tables & Charts
  - Financial formulas
  - Conditional formatting
- **Data Analysis Techniques**
  - Year-over-Year (YoY) growth
  - Profitability analysis
  - Target vs Actual comparison
  - Market & customer segmentation

---

## 📈 Key Insights
- Strong **revenue growth** observed from 2019 to 2021
- **Gross Margin % decline** despite increasing net sales
- India and USA emerged as **top-performing markets**
- Several markets missed targets, indicating scope for optimization

---

## 🚀 How to Use
1. Open **Sales report.xlsx** to explore the complete analysis.
2. Review the **PDF reports** for summarized insights and visual dashboards.
---


