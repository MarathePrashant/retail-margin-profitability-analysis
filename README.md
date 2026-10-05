# 📊 Retail Sales & Gross Profitability Analysis

[![Excel](https://img.shields.io/badge/Excel-Advanced%20Modeling-217346?style=flat-square\&logo=microsoftexcel)](#)
[![Power Query](https://img.shields.io/badge/Power_Query-Automated_ETL-orange?style=flat-square)](#)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)](#)

## 📌 Executive Summary & Business Problem

Strong sales revenue does not always translate into strong profitability. Promotional discounts, low-value orders, and shipping costs can significantly reduce margins even when overall sales remain high.

This project analyzes multi-region retail transactions to identify profit-draining product segments, evaluate the impact of discounting and shipping costs, and establish practical thresholds for improving order-level profitability.

## 🛠️ Data Pipeline & Technical Approach

* **Power Query ETL:** Built a repeatable data-cleaning workflow to ingest transaction data, remove duplicates, handle missing values, and standardize regional and transactional fields.
* **Excel Data Modeling:** Used advanced Excel functions such as `XLOOKUP`, `INDEX/MATCH`, `SUMIFS`, and conditional logic to calculate `Gross Margin (%)`, `Unit Shipping Cost`, and `Effective Net Profit`.
* **Business Analysis:** Evaluated sales, discounts, shipping costs, product categories, and regional performance to identify profitability drivers.
* **Interactive Dashboard:** Developed a dashboard using Pivot Tables, timeline slicers, conditional formatting, heatmaps, and category-level profitability scorecards.

## 📂 Project Structure

```text
├── data/               # Raw and cleaned transaction datasets
├── models/             # Excel workbook containing calculations and dashboard
├── visuals/            # Dashboard screenshots and analytical views
└── README.md           # Business case study, methodology, and insights
```

## 📊 Key Business Insights

* **Discount Impact:** Higher discount levels significantly reduced order profitability, demonstrating the need to balance sales volume with contribution margin.
* **Category Margin Differences:** Technology generated strong sales volume but operated at a lower margin compared with higher-margin categories such as Office Supplies.
* **Shipping Cost Impact:** Free or subsidized shipping on low-value orders reduced unit-level profitability, highlighting the importance of minimum order thresholds.
* **Profitability Drivers:** Order value, discount percentage, product category, and shipping cost were key factors influencing effective net profitability.

## 💡 Strategic Business Recommendations

* **Discount Guardrails:** Establish predefined discount thresholds and require additional approval for promotions that could materially reduce contribution margins.
* **Minimum Order Thresholds:** Introduce a minimum cart value for free shipping to protect order-level economics.
* **Product Mix Optimization:** Increase promotional focus on higher-margin categories while carefully managing discounts on lower-margin products.
* **Profitability Monitoring:** Track sales, discount, shipping cost, and margin KPIs together rather than evaluating revenue in isolation.

## 🚀 How to Explore This Project

1. **Open the Excel Model:** Download the `.xlsx` workbook from `/models` and open it in Microsoft Excel to explore the calculations, Pivot Tables, slicers, and dashboard.
2. **Review the Data Transformation:** Examine the Power Query workflow to understand the data-cleaning and preparation process.
3. **Review the Calculations:** Inspect the calculation tables and formulas used for margin, shipping cost, discount, and profitability analysis.
4. **Explore the Dashboard:** Use the interactive filters and Pivot Tables to analyze performance across categories, regions, and other business dimensions.

## 👤 Author

**Prashant Marathe**

* **LinkedIn:** https://www.linkedin.com/in/prashantmarathe17
* **Portfolio:** https://prashant-marathe.framer.website/
* **Email:** [p04747391@gmail.com](mailto:p04747391@gmail.com)
* **Location:** Pune, Maharashtra, India
