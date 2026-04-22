# Healthcare Claims & Operations Dashboard

---

## Problem Statement

This dashboard helps healthcare management teams understand claims processing, financial performance, and operational efficiency across departments. It enables hospitals and health networks to identify denial patterns, track recovery rates, and pinpoint departments that require process improvement.

By analyzing claims data across multiple dimensions — department, insurer, visit type, and time period — the dashboard helps COOs and CFOs make data-driven decisions. If denial rates are high or recovery rates are low in specific departments, management can prioritize targeted interventions to improve revenue cycle performance.

---

## Steps Followed

- **Step 1:** Designed and embedded a synthetic dataset of 275 healthcare claims records covering Jan 2024 – Mar 2025 across 5 locations (Hyderabad, Secunderabad, Vijayawada, Visakhapatnam, Warangal).
- **Step 2:** Built the full dashboard in a single self-contained HTML file using Chart.js for all visualizations.
- **Step 3:** Implemented interactive filters for Year, Quarter, Location, Department, Insurance Provider, Visit Type, and Gender.
- **Step 4:** Created dynamic KPI cards that update in real-time based on active filters:
  - Total Claims
  - Total Claim Amount
  - Paid Amount
  - Denial Rate
  - Average Recovery Rate
- **Step 5:** Added automated insight banners that surface the top denial reason and the lowest-performing department dynamically.
- **Step 6:** Built the following charts (all filter-responsive):
  - Monthly Revenue: Claimed vs Paid (Line Chart)
  - Claim Status Breakdown (Donut Chart)
  - Denial Reasons — excluding N/A (Horizontal Bar)
  - Claims by Department — Claimed vs Paid (Clustered Bar)
  - Revenue by Insurance Provider — Claimed vs Unpaid (Stacked Bar)
  - Claims by Visit Type with Avg Claim Overlay (Combo Chart)
- **Step 7:** Built a Department Performance Scorecard table showing Claims, Avg Claim, Denial %, Recovery %, and Avg Length of Stay (LOS) with color-coded badges.
- **Step 8:** Applied a professional dark theme with cyan/green/red/amber color coding throughout.

---

## Key Features

- ✅ Fully interactive filters — all charts and KPIs update dynamically
- ✅ Single-file HTML — no backend or external data source required
- ✅ CFO & COO edition — designed for executive-level decision-making
- ✅ Color-coded badges for instant performance assessment
- ✅ Auto-generated insights surface the most critical issues per filter state

---

## Tech Stack

- **HTML5 / CSS3 / Vanilla JavaScript**
- **Chart.js 4.4.1** — for all charts and visualizations
- **Google Fonts** — Space Grotesk + JetBrains Mono

---

## Dashboard Snapshot

> *(Add a screenshot of the dashboard here after deploying)*

---

## Live Demo

🔗 [View Live Dashboard](https://mitesh3621.github.io/Data-Analyst-Project-3/healthcare_dashboard.html)

---

## KPIs Overview

| KPI | Value |
|---|---|
| Total Claims | 275 |
| Total Claim Amount | ₹120.7L |
| Total Paid Amount | ₹71.0L |
| Denial Rate | 22.9% |
| Average Recovery Rate | 64.6% |

---

## Department Performance Scorecard

| Department | Claims | Denial % | Recovery % | Avg LOS |
|---|---|---|---|---|
| Cardiology | High volume | Moderate | Good | ~4.2d |
| Emergency | High volume | High | 57.8% ⚠️ | ~3.8d |
| Neurology | Moderate | Low | Good | ~5.1d |
| Orthopedics | Moderate | Moderate | Good | ~5.6d |
| Pediatrics | Moderate | Low | High | ~2.9d |
| General Medicine | Moderate | Moderate | Good | ~3.5d |

---

## Insights

1. **Emergency dept has the lowest recovery rate (57.8%)** — ₹9.8L in unpaid claims at risk.
2. **"Not Specified" is the top denial reason** — accounts for 74.3% of all denied claims, indicating a documentation process gap.
3. **Inpatient claims carry the highest average claim value** vs Outpatient and Emergency.
4. **Star Health and HDFC Ergo** are the largest insurance revenue contributors.
5. **Cardiology generates the highest total claimed amount** across all departments.

---

## Conclusion

This dashboard provides a complete revenue cycle and operational view for a multi-location health network. It helps finance and operations leadership identify high-denial departments, optimize insurer negotiations, and improve claim recovery rates for better financial sustainability.

---

## About

**Data Analyst Portfolio Project 2**  
Built by Mitesh | B.Tech CSE (AI/ML) | Guru Nanak Institute of Technology, Hyderabad
