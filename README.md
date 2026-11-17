# 📊 E-Commerce Sales, Logistics & Customer Intelligence — Excel Final Project

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1B365D,50:0E6251,100:1E8449&height=200&section=header&text=E-Commerce%20Sales%20Dashboard&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=End-to-End%20Excel%20Sales%2C%20Logistics%20and%20Customer%20Analytics&descSize=18&descAlignY=62" alt="Project Banner" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TOOL-MICROSOFT_EXCEL-1E8449?style=for-the-badge" alt="Tool" />
  <img src="https://img.shields.io/badge/DOMAIN-E--COMMERCE_ANALYTICS-1B5E91?style=for-the-badge" alt="Domain" />
  <img src="https://img.shields.io/badge/RECORDS-40%2C000-D68910?style=for-the-badge" alt="Records" />
  <img src="https://img.shields.io/badge/STATUS-COMPLETED-1E8449?style=for-the-badge" alt="Status" />
</p>

---

## 🎥 Project Demo

Watch the project demonstration to explore the interactive slicers, dynamic formulas, predictive models, and dashboard visuals.

<p align="center">
  🔗 <b>Project Demo Video:</b> <a href="YOUR_GOOGLE_DRIVE_LINK_HERE">▶️ Watch on Google Drive</a>
</p>

---

## 🎯 Project Overview & Key Findings

This end-to-end **Business Intelligence & Data Analytics** workbook transforms **40,000 raw e-commerce transactions (2019–2024)** across five Indian delivery regions into an automated KPI engine, predictive regression model, What-If scenario simulator, and executive dashboard.

- 💰 **Strong Revenue & Profitability:** Generated **₹ 137.69 Cr** in Gross Sales, **₹ 83.63 Cr** in Net Revenue, and **₹ 22.74 Cr** in Net Profit (**27.19%** overall margin), with **36,796 (92.0%)** profitable orders.
- 🌍 **Regional Dominance:** **East (₹ 30.15 Cr)** and **South (₹ 24.93 Cr)** contribute **65.9%** of total revenue, while **Central (₹ 1.99 Cr)** represents the highest untapped growth opportunity.
- 📱 **Category Leaders:** **Mobile Phone (₹ 5.13 Cr)** leads net revenue, followed by **Cloth (₹ 3.54 Cr)**, **Watch (₹ 3.20 Cr)**, and **Laptop (₹ 3.08 Cr)**.
- 🚚 **Logistics Bottleneck:** Average delivery lead time stands at **17.8 days**, with **35.5% undelivered orders** nearly matching **35.9% delivered orders**—highlighting a major profit recovery lever.
- 📈 **Predictive & What-If Insights:** Linear regression confirms a strong relationship between marketing price and order revenue (**R² = 0.67**, **r = 0.82**, **Slope = 1.113**), while Scenario Manager projects net profit ranging from **₹ 11.67 Cr (Worst Case)** to **₹ 36.32 Cr (Best Case)**.

---

## 🗂️ Workbook Architecture (8 Structured Sheets)

| Sheet Name | Core Purpose & Analytical Implementation |
| :--- | :--- |
| **`E-commerce_Raw_Dataset`** | Original raw transactional dataset (`40,000 rows × 25 columns`) with noisy text, mixed date formats, and missing values. |
| **`Cleaned_Data`** | Standardized dataset (`TRIM`, `PROPER`, date formatting) with engineered **`Order_Year`** column (`2019–2024`). |
| **`Formula_Analysis`** | Automated KPI cards, regional & delivery breakdowns, Top-10 sub-categories, interactive lookup engine (`VLOOKUP`, `HLOOKUP`, `INDEX + MATCH`), and dynamic Top-N simulator. |
| **`Predictive_&_WhatIf`** | Profit Simulator using **Scenario Manager** (Base, Best, Worst Cases) and **Linear Regression** (`SLOPE`, `INTERCEPT`, `RSQ`, `CORREL`). |
| **`Pivot_Analysis`** | Five multi-dimensional Pivot Tables synchronized to a single data cache (`Cleaned_Data!$A$1:$Z$40001`). |
| **`Charts`** | Static analytical visuals covering customer feedback, delivery status share, region revenue vs. profit margin combo chart, and gender-wise regional sales. |
| **`Dashboard`** | Gridless interactive executive dashboard with **5 live KPI cards**, **3 connected Slicers**, and **5 Pivot Charts**. |
| **`Executive_Summary`** | Structured management summary covering scope, benchmarks, visual insights, methodology, and strategic recommendations. |

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1B5E91,50:117A65,100:1E8449&height=120&section=header&text=Output%20Screenshots&fontSize=34&fontColor=ffffff&fontAlignY=52" alt="Output Screenshots" />
</p>

### 1. Interactive Executive Dashboard (`Dashboard`)
![Interactive Executive Dashboard](screenshots/01-interactive-dashboard.png)

### 2. Dynamic Formula & Lookup Engine (`Formula_Analysis`)
![Formula Analysis](screenshots/02-formula-analysis.png)

### 3. Predictive Regression & Scenario Modeling (`Predictive_&_WhatIf`)
![Predictive and What-If Analysis](screenshots/03-predictive-whatif.png)

### 4. Executive Management Summary (`Executive_Summary`)
![Executive Summary](screenshots/04-executive-summary.png)

---

## 🛠️ Excel Skills & Technical Methods Applied

- **Data Cleaning & Feature Engineering:** `TRIM`, `PROPER`, `CLEAN`, standardized date parsing, and `Order_Year` extraction.
- **Advanced Functions:** `SUMIFS`, `COUNTIFS`, `AVERAGEIFS`, `VLOOKUP`, `HLOOKUP`, `INDEX + MATCH`, `LARGE`, `MEDIAN`, `SUMPRODUCT`, and `IFERROR`.
- **Statistical & Scenario Modeling:** Linear Regression (`SLOPE`, `INTERCEPT`, `RSQ`, `CORREL`) and Excel **Scenario Manager** sensitivity modeling.
- **Interactive BI Design:** Multi-Pivot Table synchronization, Slicer `Report Connections`, Combo Charts, Doughnut/Pie Charts, Horizontal Bar Charts, and custom KPI Cards.

---

## 💡 Business Conclusion & Strategic Recommendations

The analysis demonstrates strong unit economics (**27.19% overall profit margin** across **92.0% profitable orders**), while pinpointing critical operational and regional levers to unlock additional growth:

1. **Optimize Last-Mile Logistics (Recover ₹ 4–5 Cr Profit):** With **35.5% of orders undelivered** and an average transit time of **17.8 days**, onboarding faster regional courier partners and enforcing strict delivery SLAs is the highest-priority operational fix.
2. **Scale High-Revenue Electronics & Apparel:** Prioritize inventory allocation and targeted campaigns around top-performing categories (**Mobile Phone**, **Cloth**, **Watch**, and **Laptop**) while auditing discounting on the **3,182 loss-making orders**.
3. **Expand Central Region Market Share:** Replicate the fulfillment and pricing playbook from **East (₹ 30.15 Cr)** and **South (₹ 24.93 Cr)** in **Central (₹ 1.99 Cr)** to capture untapped regional demand.

---

## 🚀 Future Enhancements (Next-Stage Roadmap)

- **Automated ETL with Power Query:** Replace manual formula-based cleaning with repeatable Power Query pipelines for one-click monthly data refreshes.
- **Power BI Executive Migration:** Extend the dashboard into **Microsoft Power BI** using DAX measures, drill-through state-level maps, and automated row-level security.
- **Database & Python Integration:** Connect the cleaned dataset directly to a **PostgreSQL** warehouse and run Python (`scikit-learn`) customer churn and delivery-delay risk scoring models.

---
