# 📊 Excel-AtliQ-hardwares-Sales-Finance-Reports

![Excel](https://img.shields.io/badge/Tool-Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/ETL-Power%20Query-F2C811?style=flat)
![Power Pivot](https://img.shields.io/badge/Modeling-Power%20Pivot-0078D4?style=flat)
![DAX](https://img.shields.io/badge/Measures-DAX-F25022?style=flat)
![Domain](https://img.shields.io/badge/Domain-Sales%20%26%20Finance-2C2C2A?style=flat)

---

## 🧩 What This Project Is About

AtliQ Hardwares sells computer hardware across **23 global markets**. This project builds a full Sales & Finance reporting system in Excel — covering **3 fiscal years (2019–2021)** — to answer the questions a real business analyst would face:

- Where is the revenue coming from?
- Why is profitability declining despite rapid growth?
- Which markets are falling short of targets — and by how much?

> **The goal wasn't just to build reports — it was to find the story inside the numbers.**

---

## 📈 The Numbers at a Glance

| Metric | 2019 | 2020 | 2021 |
|---|---|---|---|
| Net Sales | $87.5M | $196.7M | $598.9M |
| COGS | $51.2M | $123.4M | $380.7M |
| Gross Margin | $36.2M | $73.3M | $218.2M |
| GM % | 41.4% | 37.3% | 36.4% |

> 📌 Revenue grew **~3x in 2 years** — but gross margin % fell every single year. That's the tension this project investigates.

---

## 🔍 Key Business Findings

### 1. Revenue is exploding — but profitability isn't keeping up

Sales tripled from $87.5M (2019) to $598.9M (2021), which looks incredible on the surface. But gross margin % declined from **41.4% → 37.3% → 36.4%** over the same period. That widening gap between growth and profitability is the most important signal in this data.

---

### 2. High revenue ≠ high profitability

| Market | Net Sales (2021) | GM % |
|---|---|---|
| India | $161.3M | 32.0% |
| New Zealand | $11.4M | **48.2%** |
| Japan | $7.9M | **46.5%** |
| United Kingdom | $34.2M | **45.1%** |
| Germany | $12.0M | 26.2% ⚠️ |

India drives the most revenue, but its margin is only **32%**. Smaller markets like New Zealand and Japan are far more profitable per dollar — a key insight for resource allocation decisions.

---

### 3. Every market missed its 2021 target

The company fell short of its sales target by **−$54.9M (−9.2%)** overall. No single market hit its number.

| Worst Misses | Target Gap |
|---|---|
| Poland | −18.1% |
| Canada | −14.5% |
| Spain | −14.1% |

> This isn't a one-market problem — it points to something systemic in planning or execution.

---

### 4. India's revenue is heavily customer-concentrated

| Customer | 2021 Sales |
|---|---|
| Amazon | $23.0M |
| AtliQ Exclusive | $18.4M |
| Flipkart | $9.9M |

The top 2 customers account for **~26% of India's total revenue** — a concentration risk worth flagging in any real business review.

---

### 5. Seasonal patterns are visible in monthly data

FY 2021 monthly sales ranged from **$41.5M (Jun) to $78.1M (Dec)**, with consistent peaks in **Q2 (Oct–Dec)** — suggesting strong seasonality that can inform inventory and campaign planning.

---

## 📄 Reports Built

| Report | Description |
|---|---|
| 📋 P&L by Fiscal Year | Net Sales, COGS, Gross Margin across FY 2019–2021 |
| 📅 P&L by Months | Monthly breakdown with quarter view & YoY growth % |
| 🌍 P&L by Markets | Market-level profitability with GM% comparison |
| 🎯 Market Performance vs Target | All 23 markets — target gap & % miss |
| 👥 Customer Performance Report | 3-year customer sales (India market) |

---

## 🛠️ How It Was Built

```
Raw Data → Power Query (Clean & Transform) → Power Pivot (Data Model) → DAX (KPIs) → Pivot Tables (Reports)
```

| Layer | Tool | Purpose |
|---|---|---|
| Data Ingestion | Excel + Power Query | Import, clean, and shape raw sales data |
| Data Modeling | Power Pivot | Build relationships across customers, markets, products, dates |
| Calculations | DAX | Net Sales, COGS, GM%, YoY variance measures |
| Reporting | Pivot Tables | Final report layout with business-ready formatting |

---

## 💡 Skills This Project Demonstrates

- ✅ Translating business questions into data queries
- ✅ Multi-table data modeling (star schema in Power Pivot)
- ✅ Financial statement analysis (P&L structure)
- ✅ Variance analysis — actual vs target
- ✅ DAX for custom KPIs and time-intelligence measures
- ✅ Storytelling with data — insight-first, not just reporting
- ✅ Excel for enterprise-scale datasets

---

## 🔗 Project Files

| File | Link |
|---|---|
| Customer Performance Report | [View →](https://github.com/Indhu1711/Excel-AtliQ-hardwares-Sales-Finance-Reports/blob/main/Customer%20Performance%20Report.pdf) |
| Market Performance vs Target | [View →](https://github.com/Indhu1711/Excel-AtliQ-hardwares-Sales-Finance-Reports/blob/main/Market%20Performance%20vs%20Target.pdf) |
| P&L by Fiscal Year | [View →](https://github.com/Indhu1711/Excel-AtliQ-hardwares-Sales-Finance-Reports/blob/main/P%20%26%20L%20statement%20by%20Fiscal%20Year.pdf) |
| P&L by Months | [View →](https://github.com/Indhu1711/Excel-AtliQ-hardwares-Sales-Finance-Reports/blob/main/P%20%26%20L%20by%20Months.pdf) |
| P&L by Markets | [View →](https://github.com/Indhu1711/Excel-AtliQ-hardwares-Sales-Finance-Reports/blob/main/P%20%26%20L%20for%20Markets.pdf) |

---

> 📝 All values in USD. Fiscal year runs **Sep → Aug**. Data covers FY 2019–2021.
