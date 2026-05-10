# 📊 SEA In-Market Sales Dashboard — Power BI Enhancement
**embecta · 7 Markets · 2026**

> Sample/anonymised data used in all screenshots. Real market data is confidential.

---

## The Problem

| Market | Monthly Opens | Status |
|---|---|---|
| Philippines | 124 (52%) | ✅ Active |
| Malaysia & Vietnam | 70 (30%) | ⚠️ Low |
| Singapore & Thailand | 31 (13%) | ❌ Inactive |
| Indonesia | 9 (3%) | ❌ Almost ignored |

**354 opens vs 600 expected. 50% of opens from just 5 users — 3 were not even sales staff.**

The dashboard existed. Nobody used it.

---

## The Shift

```
BEFORE  →  Monthly report. Review what happened.
AFTER   →  Weekly run rate. Act on what's happening now.
```

---

## What Was Built

### 🔹 Product Category Growth vs Market
*Is the business growing faster or slower than the market?*

![Product Category](screenshots/product_category_growth.png)

> Pen Needles actual −18.1% vs market +13.2% → losing share, not just declining

---

### 🔹 Sales Rep Weekly Tracking + Run Rate
*Who needs support before month-end — not after?*

![Weekly](screenshots/sales_rep_weekly.png)

> Feb W1: 273% of target → Feb W3: 40.5% → flag and act in the same month

![Run Rate](screenshots/sales_rep_runrate.png)

---

### 🔹 Customer-Level Run Rate
*Which accounts are at risk right now?*

![Customer Table](screenshots/customer_run_rate.png)

> Last order date + orders this month vs 6M average → tells reps exactly where to push

---

### 🔹 New Launch Dashboard (BGM)
*Campaign performance in one place — no more manual spreadsheets*

![BGM Launch](screenshots/new_launch_bgm.png)

---

## Technical Work

| Layer | Detail |
|---|---|
| **Data sources** | Excel files from 7 markets in different formats — standardised via Power Query |
| **DAX measures** | Run rate · Gap-to-target · Customer status (New/Lost/Regained) · R12M market growth |
| **Access control** | Row-level security — BLs see all markets, reps see only their own data |
| **Automation** | MIDAS Dataflow integration for market growth data — removed manual updates |

---

## Views Added / Enhanced

| # | View | Type |
|---|---|---|
| 1 | Overall Sales Performance | Retained |
| 2 | Quantity + Category Growth vs Market | Enhanced |
| 3 | Sales Rep Weekly + Run Rate | **New** |
| 4 | Account Summary + Customer Run Rate | **New** |
| 5 | Cluster Summary (MBR) — automated | Enhanced |
| 6 | Overall Contribution + Product Line | Enhanced |
| 7 | New Launch Campaign (BGM) | **New** |

---

## Stack

`Power BI` · `DAX` · `Power Query (M)` · `Excel` · `MIDAS Dataflow` · `Pitcher`

---

## 🔗 More Projects

[🔋 Time Series Forecasting — R](https://github.com/thaotracy-sg/electric-power-co2-forecasting-europe) · [📱 Panel Data Analysis — R](https://github.com/thaotracy-sg/game-app-panel-analysis) · [🌿 Logit Model — R](https://github.com/thaotracy-sg/sustainable-brand-logit-analysis) · [🛒 SQL + R Pipeline](https://github.com/thaotracy-sg/sql-r-customer-survey-pipeline)

---
*Tracy Nguyen · embecta Business Support Intern · Dec 2025 – Apr 2026*
