# Renewals Strategy & Operations
### Salesforce — Strategy & Operations Sr Analyst | 2025

An end-to-end renewals analytics dashboard simulating a 
Salesforce CRM environment — covering weekly forecast 
performance, renewal lifecycle funnel, ARR by region and 
customer segment, and operating unit performance tracking.

## Dashboard Overview

<img width="2096" height="1428" alt="Image 7-9-26 at 1 40 PM" src="https://github.com/user-attachments/assets/b785085b-fc54-44eb-9743-497f1d853ce4" />


🔗 [View on Tableau Public](https://public.tableau.com/views/MarketingAnalyticsCommandCenterSalesforce/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## What This Dashboard Covers

| Section | What It Shows |
|--------|---------------|
| Forecast Performance | Monthly forecasted vs actual ARR trend across FY2025 |
| Renewal Lifecycle | Stage-by-stage funnel from Eligible to Renewed — 91.4% renewal rate |
| Renewal Portfolio Mix | ARR distribution across Enterprise, Strategic, Mid Market, SMB, Commercial |
| Renewal ARR by Region | Performance across North America, EMEA, APAC, LATAM, Public Sector |
| Renewal ARR by Segment | Pipeline and priority by customer segment |
| Renewal Performance Index | Operating unit performance scoring across key renewal metrics |
| Renewal Rate Trend | 6-month renewal rate trend by customer segment |

---

## KPI Summary

| KPI | Value | How It's Calculated |
|-----|-------|-------------------|
| Renewal ARR | $18.4M | Sum of renewed ARR across all segments |
| Renewal Accounts | 8,340 | Total renewal eligible accounts |
| Renewal Rate | 91.4% | Renewed Accounts / Eligible Accounts |
| Forecast Accuracy | 96.2% | 1 − ABS(Forecast − Actual) / Actual |
| Target Attainment | 109% | Actual ARR / Annual Target ARR |

---

## Data Sources

This dashboard uses a **synthetic enterprise SaaS renewals 
dataset** built to simulate a Salesforce CRM environment. 
All data is fictional and does not represent proprietary 
Salesforce data.

Benchmark assumptions are consistent with published enterprise 
SaaS industry standards:
- Renewal rate range for mature enterprise SaaS: 85–95%
- Forecast accuracy target: 95%+
- High performer gross retention: 90%+

---

## Tech Stack

| Tool | How It Was Used |
|------|----------------|
| SQL | Data extraction, joins, aggregations, validation queries |
| Snowflake | Data warehouse querying and transformation |
| Tableau Prep | Data cleaning, schema standardization, transformation flows |
| Tableau Public | Dashboard design, calculated fields, dual axis, parameters |
| Python (pandas) | Exploratory analysis and data structuring |
| CSV | Synthetic data sources |

---

## Business Context

This dashboard is designed to support the core responsibilities 
of a Renewals Strategy & Operations function:

**Weekly forecasting process**
The Forecast Performance trend tracks forecasted vs actual ARR 
monthly — enabling weekly forecast calls and operating unit 
reviews with leadership.

**Attrition and retention forecasting**
The Renewal Lifecycle funnel shows where accounts drop off 
at each stage — from Eligible through Contacted, Engaged, 
Renewal Discussion, Negotiation, to Renewed. A 91.4% renewal 
rate reflects a mature CSM-led renewals motion.

**Customer segmentation and propensity analysis**
Renewal ARR by Customer Segment shows which segments — 
Enterprise, Strategic, Mid Market, SMB, Commercial — drive 
the highest ARR and which carry the highest churn risk.

**Operating unit performance against targets**
The Renewal Performance Index tracks key metrics across 
operating units — Forecast Accuracy, Gross Retention, 
Renewal Coverage — giving leadership a consolidated 
performance view across regions and segments.

**Executive presentation**
KPI tiles at the top of the dashboard are designed for 
executive-level consumption — five headline metrics 
answerable in ten seconds without needing to read a chart.

---

## Dashboard Design Decisions

**Why synthetic data?**
Built to demonstrate SQL, Snowflake, Tableau, and KPI design 
skills in a renewals and forecasting context without using 
proprietary data. Every metric is mathematically consistent 
and defensible against enterprise SaaS benchmarks.

**Stakeholder design principle**
Every chart was designed around a business decision, not 
around data availability. The question asked for each section: 
"What action should a Renewals or Sales leader take after 
seeing this?" If the answer wasn't obvious, the chart 
wasn't done.

**Why these KPIs?**
Renewal Rate, Forecast Accuracy, and Target Attainment are 
the three metrics a VP of Renewals checks first. They answer: 
are we retaining revenue, are we predicting it accurately, 
and are we hitting our number?

---

## How I Built It — End to End

1. **Defined business questions** — what decisions does a 
   Renewals S&O team make weekly?
2. **Designed synthetic dataset** — mathematically consistent 
   renewal lifecycle, ARR by segment, regional performance
3. **Validated all KPIs** — renewal rate, forecast accuracy, 
   and target attainment all reconcile to the same base numbers
4. **Built 7 individual sheets** in Tableau — each answering 
   one specific business question
5. **Assembled dashboard** with KPI tile row, tiled layout, 
   consistent color palette
6. **Applied design standards** — business-language labels, 
   removed gridlines, custom tooltips, executive-ready formatting
7. **Added synthetic data disclaimer** in footer for 
   transparency
