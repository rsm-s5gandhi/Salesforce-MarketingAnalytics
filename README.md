# Marketing Analytics Command Center
### Salesforce Planning & Strategy — 2025

An end-to-end marketing analytics dashboard — automated reporting, cross-system data harmonization, 
KPI standardization, and real-time visibility for marketing teams.

## Dashboard Overview
<img width="2798" height="1898" alt="Salesforce Marketing Analytics Dashboard" src="https://github.com/user-attachments/assets/f42d30ad-f32b-491d-8d05-3866ccd23069" />

🔗 [View on Tableau Public](https://public.tableau.com/views/MarketingAnalyticsCommandCenterSalesforce/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## What This Dashboard Covers

| Section | What It Shows |
|--------|---------------|
| Campaign Performance | Monthly MQL, Pipeline, and Spend trends across 2025 |
| Full Funnel Conversion | Stage-by-stage drop-off from Impression to Closed Won |
| Channel ROI | Return on spend by channel — benchmarked to HubSpot 2025 B2B data |
| Lead Source Mix | MQL distribution by channel origin |
| SMB Segmentation | Pipeline and conversion rate by SMB segment — 5M+ records |
| SMB Trend | 6-month conversion rate trend by segment |
| SF SOM Benchmarks | Real stats from Salesforce State of Marketing 10th Edition |

---

## Data Sources

All benchmark data is sourced directly from publicly available 
industry reports:

- **Salesforce State of Marketing — 10th Edition**
  Surveyed Oct–Nov 2025 · 4,450 marketing decision makers · 29 countries
- **HubSpot State of Marketing 2025**
  B2B channel ROI rankings and conversion rate benchmarks

Pipeline, MQL, and segmentation figures reflect realistic 
mid-market B2B marketing org performance consistent with 
published benchmarks.

---

## Tech Stack

| Tool | How It Was Used |
|------|----------------|
| SQL | Data extraction, joins, aggregations, validation logic |
| Tableau Prep | Data cleaning, transformation, standardization flows |
| Tableau Public | Dashboard design, LOD expressions, dual axis, parameters |
| Python (pandas) | Exploratory data analysis and data structuring |
| CSV / Excel | Raw data sources and benchmark inputs |

---

## Dashboard Design Decisions

**Why these KPIs?**
The five headline KPIs — Pipeline Generated, Total MQLs, 
Conversion Rate, Cost Per Lead, and Blended ROI — map directly 
to the metrics a Marketing Planning & Strategy team tracks 
weekly. They answer the question a CMO asks first: are we 
growing efficiently?

**Why benchmark against SF SOM + HubSpot?**
Dashboards built on internal data alone lack context. Grounding 
channel ROI and conversion benchmarks in the Salesforce 10th 
Edition State of Marketing report (4,450 marketers surveyed) 
gives marketing leadership a frame of reference for whether 
performance is above or below industry standard.

**Why SMB segmentation?**
Not all pipeline is equal. The SMB segmentation view shows 
which customer segments are generating the highest return — 
Tech/SaaS and Healthcare lead at 5.2% and 4.1% conversion 
respectively — enabling marketing teams to prioritize budget 
allocation toward highest-impact segments.

**Stakeholder design principle**
Every chart was designed around a business decision, not around 
data availability. The question I asked for each section: 
"What action should a marketing leader take after seeing this?" 
If the answer wasn't obvious, the chart wasn't done.

---

## Key Stats From the Data
*(Salesforce State of Marketing 10th Edition — 2025)*

- **75%** of marketers have adopted AI — but **84%** still run generic campaigns
- **33%** still rely on fully manual attribution — this dashboard eliminates that
- **31%** are satisfied with data unification — unified pipelines are the differentiator
- **72%** of high performers analyze marketing performance in real time
- Teams with unified data are **42%** more likely to respond to customers promptly

---

## How I Built It — End to End

1. **Identified business questions** — what decisions should this dashboard enable?
2. **Sourced benchmark data** from Salesforce SOM 10th Ed + HubSpot 2025
3. **Structured CSVs** with clean schema, consistent naming, source attribution
4. **Connected data sources** in Tableau Public
5. **Built 7 individual sheets** — each answering one specific business question
6. **Assembled dashboard** with KPI tile row, tiled layout, consistent formatting
7. **Applied design standards** — consistent color palette, removed gridlines, 
   business-language labels, custom tooltips
