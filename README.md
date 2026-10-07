# 📊 Retail Sales & Gross Profitability Analysis

> **End-to-end Excel analytics project using Power Query, advanced Excel formulas, PivotTables, and interactive dashboards to identify profitability drivers, discount impact, shipping-cost leakage, and margin improvement opportunities.**

## 📌 Business Problem

Strong sales revenue does not always translate into strong profitability.

Discounting, shipping costs, low-value orders, and product mix can significantly reduce order-level margins even when overall sales remain strong.

This project analyzes retail transactions to understand:

* Sales and profitability performance
* Discount impact on margins
* Shipping-cost impact
* Product-category profitability
* Regional performance
* Order-level profit drivers
* Opportunities to improve gross profitability

---

## 🎯 Project Objectives

The analysis focuses on five key areas:

1. **Sales Performance** — evaluate revenue across categories and regions.
2. **Profitability Analysis** — identify products and segments generating stronger margins.
3. **Discount Analysis** — quantify the effect of discounting on profitability.
4. **Shipping Cost Analysis** — identify orders where logistics costs erode margins.
5. **Business Recommendations** — develop practical actions to improve order economics.

---

## 🛠️ Tech Stack

| Area                  | Tools                           |
| --------------------- | ------------------------------- |
| Spreadsheet Analytics | Microsoft Excel                 |
| ETL                   | Power Query                     |
| Data Cleaning         | Power Query                     |
| Lookup / Logic        | XLOOKUP, INDEX/MATCH, IF        |
| Aggregation           | SUMIFS                          |
| Data Analysis         | PivotTables                     |
| Visualization         | Excel Dashboard                 |
| Reporting             | Interactive Dashboard           |
| Business Analytics    | Profitability / Margin Analysis |

---

## 🔄 End-to-End Analytics Workflow

```text id="n6tq5m"
Raw Retail Transactions
        ↓
Power Query ETL
        ↓
Data Cleaning & Validation
        ↓
Data Standardization
        ↓
Calculated Metrics
        ↓
PivotTable Analysis
        ↓
KPI Development
        ↓
Interactive Dashboard
        ↓
Profitability Diagnostics
        ↓
Business Recommendations
```

---

## 🧹 Data Preparation

Power Query was used to create a repeatable data-preparation workflow covering:

* Duplicate removal
* Missing-value handling
* Data-type standardization
* Regional field standardization
* Transaction-level data preparation
* Calculation-ready dataset creation

The goal was to create a consistent analytical dataset before building Excel calculations and dashboards.

---

## 🧮 Key Calculations

The Excel model uses formulas including:

* `XLOOKUP`
* `INDEX/MATCH`
* `SUMIFS`
* Conditional logic

These calculations support metrics such as:

* **Gross Margin (%)**
* **Unit Shipping Cost**
* **Effective Net Profit**
* Discount impact
* Order-level profitability

---

## 📈 Key KPIs

The dashboard focuses on:

* Total Sales
* Total Profit
* Gross Margin %
* Average Order Value
* Discount %
* Shipping Cost
* Unit Shipping Cost
* Effective Net Profit
* Category Profitability
* Regional Profitability

---

## 🔍 Key Business Questions

### Sales & Profitability

* Which categories generate the strongest margins?
* Which categories generate high sales but comparatively weak profitability?
* Which regions perform best from a profit perspective?

### Discounting

* How does discount percentage affect order profitability?
* At what point do discounts begin to materially reduce margins?
* Which categories are most sensitive to discounting?

### Shipping

* How much does shipping cost reduce order-level profitability?
* Are low-value orders disproportionately affected by shipping?
* Could minimum-order thresholds improve profitability?

---

## 💡 Key Business Insights

### 1. Discount Impact

Higher discount levels reduced order profitability, demonstrating that revenue growth alone is not sufficient for evaluating commercial performance.

**Business implication:**
Discount strategies should be evaluated against contribution margin rather than sales volume alone.

### 2. Category Margin Differences

Technology generated strong sales volume but operated at a lower margin compared with higher-margin categories such as Office Supplies.

**Business implication:**
Category strategy should balance revenue contribution with margin contribution.

### 3. Shipping-Cost Leakage

Free or subsidized shipping on low-value orders reduced unit-level profitability.

**Business implication:**
Shipping economics should be considered when defining free-shipping policies.

### 4. Core Profitability Drivers

Order value, discount percentage, product category, and shipping cost were key factors influencing effective net profitability.

**Business implication:**
Profitability dashboards should combine revenue, discounts, logistics costs, and margin KPIs rather than monitoring sales alone.

---

## 💼 Business Recommendations

### 🔹 1. Establish Discount Guardrails

Define discount thresholds and require additional review for promotions that could materially reduce contribution margins.

### 🔹 2. Introduce Minimum Order Thresholds

Set a minimum cart value for free shipping where appropriate to protect order-level economics.

### 🔹 3. Optimize Product Mix

Increase promotional focus on higher-margin categories while carefully managing discounts on lower-margin products.

### 🔹 4. Monitor Profitability Holistically

Track:

**Sales → Discount → Shipping Cost → Net Profit → Margin**

rather than evaluating revenue in isolation.

### 🔹 5. Build Order-Level Profitability Monitoring

Flag orders where:

* Discount is unusually high
* Shipping cost is disproportionately large
* Effective profit falls below a defined threshold

This can support faster commercial decision-making.

---

## 📊 Interactive Excel Dashboard

The dashboard uses:

* PivotTables
* Timeline slicers
* Conditional formatting
* Heatmaps
* Category-level profitability scorecards
* Interactive filtering

The workbook can be used to analyze performance across categories, regions, and other business dimensions.

**Excel workbook:** `Sales Dashboard.xlsx`

---

## 🧠 Skills Demonstrated

* Microsoft Excel
* Power Query
* Data Cleaning
* ETL
* XLOOKUP
* INDEX/MATCH
* SUMIFS
* PivotTables
* Interactive Dashboards
* KPI Development
* Profitability Analysis
* Gross Margin Analysis
* Discount Analysis
* Shipping Cost Analysis
* Business Analytics
* Data Visualization
* Business Recommendations

---

## 📂 Project Structure

```text id="6x6m7r"
retail-margin-profitability-analysis/
│
├── data/
│   └── retail_transactions.xlsx
│
├── models/
│   └── Sales_Dashboard.xlsx
│
├── visuals/
│   └── dashboard-overview.png
│
└── README.md
```

> **Important:** Create these folders and move the existing workbook and screenshot before using this structure. Do not leave the README describing folders that do not exist.

---

## 🚀 Business Value

This project demonstrates how Excel can be used as a complete analytics solution—not simply for basic reporting.

The analysis helps businesses:

* Identify profit-draining segments
* Evaluate discount effectiveness
* Understand shipping-cost leakage
* Compare category margins
* Monitor regional profitability
* Improve promotional decisions
* Establish profitability guardrails
* Make data-driven commercial decisions

---

## 👤 Author

**Prashant Marathe**

B.Tech — Artificial Intelligence & Data Science

**Target Roles:** Data Analyst | BI Analyst | Business Analyst

📍 Pune, Maharashtra, India

* [LinkedIn](https://www.linkedin.com/in/prashantmarathe17)
* [Portfolio](https://prashant-marathe.framer.website/)
* [GitHub](https://github.com/MarathePrashant)
* Email: [p04747391@gmail.com](mailto:p04747391@gmail.com)
