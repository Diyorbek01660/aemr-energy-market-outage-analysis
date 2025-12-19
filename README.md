# AEMR Energy Market Outage Analysis

## Project Overview
This project analyzes American Energy Market Regulator (AEMR) outage data to assess generator reliability, outage severity, and operational risk across the U.S. energy market using Python and Tableau.

Rather than relying solely on outage frequency, this analysis incorporates outage duration and severity indicators to surface generators and participants that present elevated reliability risk.

---

## Business Problem
Energy regulators and market participants require better visibility into which generators pose the greatest operational risk. High-frequency outages are not always the most severe, and low-frequency events can still cause major system disruption.

This project focuses on identifying high-risk generators and outage patterns to support improved reliability monitoring and regulatory oversight.

---

## Objective
- Identify generators with the highest operational risk
- Analyze outage severity and duration patterns
- Highlight market participants contributing disproportionately to reliability issues
- Support data-driven regulatory and operational decisions

---

## Data
- Source: American Energy Market Regulator (AEMR)
- Records: 10,000+ outage events
- Key Fields:
  - Market Participant
  - Generator
  - Outage Type
  - Outage Duration
  - Outage Severity
  - Event Date

---

## Methodology
- Cleaned and standardized outage records using Python
- Engineered outage severity and duration metrics
- Aggregated outage data by generator and market participant
- Applied SQL-style logic using Pandas (CTEs, CASE logic, aggregations)
- Built interactive Tableau dashboards to visualize reliability risk

---

## Dashboard Features (Tableau)
- Generator-level outage severity and duration analysis
- Market participant risk ranking
- Interactive filters by outage type and time period
- Drill-down views to identify recurring outage drivers

---

## Key Insights
- A small subset of generators account for a disproportionate share of severe outages
- High-frequency outages are not always the highest risk
- Severity-weighted analysis provides clearer reliability signals than raw outage counts

---

## Tools Used
- Python (Pandas, NumPy)
- Jupyter Notebook
- Tableau
- SQL-style analytics logic

---

## Outcome
Delivered a combined Python and Tableau analysis highlighting high-risk generators and outage patterns, supporting improved energy reliability monitoring and regulatory insight.
