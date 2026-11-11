# Procurement Spend Analysis

Power BI dashboard analyzing procurement spend across vendors, categories, locations, and time periods.

## 📌 Problem

Understanding where procurement money goes, which vendors dominate spend, and how spending changes over time, to support better sourcing decisions.

## 📂 Data

- **Source:** Procurement invoice data
- **Size:** 326K+ invoice line items
- **Tables:** Invoice Line Item, Invoice, Vendor, Location, Item, Currency, ExchangeRate

## 🧱 Data Model

Star schema with Invoice Line Item as the fact table, connected to the dimension tables above.

## 📊 Dashboard Pages

1. **Executive Overview**: high-level KPIs and spend summary
2. **Vendor Analysis**: vendor ranking and concentration risk
3. **Category & Item Analysis**: spend breakdown by category and item
4. **Time Intelligence**: YoY and period comparisons

## 🔑 Key Measures

- 60+ DAX measures covering time intelligence, concentration risk, net spend, and vendor/category/location analysis
- Net spend calculated after discounts
- Top 5 vendor concentration: **~13.57%** of total spend

## 🛠️ Tools

Power BI, DAX, Power Query

## 📷 Preview



<img src="Screenshot%202026-10-08%20002821.png" width="700" alt="Procurement Spend Analysis Dashboard">



## 📁 Files

- `Ahmed Said Founder Spend Analysis.pbix`: Power BI file# Procurement-Spend-Analysis
