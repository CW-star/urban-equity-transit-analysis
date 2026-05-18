# Urban Equity & Transit Access Analysis

## Project Overview
A spatial equity analysis of Chicago's 40 community areas examining the relationship 
between household income and access to public transit (CTA rail and bus stops). 
The goal: identify which neighborhoods are underserved — high transit need, low transit 
access — and produce data-driven policy recommendations the city can act on.

## Business Questions Answered
1. Is there a measurable correlation between income and transit access in Chicago?
2. Which neighborhoods have the highest transit need but the lowest access?
3. How does transit access differ between the North/Central, West Side, and South Side?
4. Where should the city prioritize new transit investment?

## Tools Used
- **Python** — pandas, numpy, matplotlib, geopandas
- **Data** — ACS 2021 5-year estimates (US Census Bureau) + CTA stop counts
- **Analysis** — Correlation analysis, transit gap scoring, investment priority matrix

## Key Findings

1. **r = 0.92 correlation** between income and transit access — nearly perfect linear relationship
2. **4x transit gap** — high income areas average 15 CTA stops vs 3.6 for low income areas
3. **20 of 40 neighborhoods** classified as Invest Now — high need, low access
4. **Fuller Park, Englewood, West Englewood** — $20-22K median income, only 2 CTA stops, 46-52% no-vehicle households
5. **North/Central averages 11.8 stops** vs West Side (4.4) and South Side (4.0) — a 3x geographic disparity

## Charts
- `chart_01` — Transit access vs income overview + correlation + KPI panel
- `chart_02` — Transit equity bubble chart + top 15 underserved neighborhoods
- `chart_03` — Zone comparison: stops, income distribution, no-vehicle households
- `chart_04` — Investment priority matrix + 4 policy recommendations

## Project Structure
urban-equity-transit-analysis/
│
├── notebooks/    # Python analysis notebook
├── visuals/      # All 4 charts
└── data/         # Data source references

## Status
✅ Complete — Spatial Analysis + 4 Python Visualizations + Policy Recommendations

## Author
Cynthia Wanjiku Ng'ang'a | Business Analytics Graduate Student
https://www.linkedin.com/in/cynthia-ng%E2%80%99ang%E2%80%99a-b3b764350/
