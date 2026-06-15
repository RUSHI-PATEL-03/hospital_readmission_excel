# 📊 Hospital Readmission Risk Analysis — Excel Dashboard

> **Same dataset. Different lens. Built for decision-makers, not just analysts.**

[![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=flat-square&logo=microsoft-excel)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Charts](https://img.shields.io/badge/Charts-5%20Visualizations-blue?style=flat-square)]()
[![Slicers](https://img.shields.io/badge/Slicers-4%20Dynamic%20Filters-orange?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)]()

---

## 📌 Project Overview

This project takes the same 25,000 patient hospital readmission dataset analyzed in SQL and rebuilds it as a **fully interactive Excel dashboard** - the kind a hospital operations manager or clinical director would actually use.

While the SQL project answered *"what does the data say?"*, this dashboard answers *"how do we show it to someone who doesn't write SQL?"*

🔗 **Related Project:** [Hospital Readmission SQL Analysis](https://github.com/RUSHI-PATEL-03/hospital_readmission_sql)

---

## 🖥️ Dashboard Preview

![Dashboard Preview]([visuals/dashboard_preview.png](https://github.com/RUSHI-PATEL-03/hospital_readmission_excel/blob/main/visuals/Hospital%20Readmission%20Dashboard.png))

---

## 🎯 What This Dashboard Does

- **Filters dynamically** -> click any slicer to instantly filter all 5 charts
- **Highlights risk** -> red = danger, green = safe, gradient in between
- **Tells 5 different stories** -> each chart uses a different format for a reason
- **Works for non-technical viewers** -> no SQL, no code, just insights

---

## 📊 5 Charts — 5 Different Stories

| Chart | Type | Key Finding |
|---|---|---|
| Readmission by Age Group | Clustered Bar (gradient) | 80–90 age group → 49.6% readmission |
| Readmission by Medical Specialty | Combo Bar + Line | Family Practice has highest rate at 49.5% |
| Readmission vs Medication Volume | Line with Markers | Risk peaks at 21–30 medications (52.4%) |
| Readmission by Visit History | Horizontal Bar | Inpatient-dominant patients → 59.9% |
| Diabetes Treatment Risk Groups | Gradient Horizontal Bar | Ignored high glucose → 58.9% readmission |

---

## 🧠 Excel Skills Demonstrated
✅ PivotTables — multi-field analysis with calculated averages

✅ Slicers — 4 dynamic filters with cross-chart Report Connections

✅ COUNTIFS / AVERAGEIFS / MAXIFS — formula-based analysis sheet

✅ Nested IF / IFS / AND — CASE WHEN logic rebuilt in Excel

✅ Combo Charts — dual-axis bar + line visualization

✅ Conditional Formatting — color-scale risk heatmaps

✅ KPI Cards — shape-linked metric displays

✅ Dashboard Design — dark theme, no-fill charts, professional layout

✅ Structured Table References — [@column] syntax throughout

✅ Data Cleaning Workflow — Raw → Working copy → Analysis → Dashboard

