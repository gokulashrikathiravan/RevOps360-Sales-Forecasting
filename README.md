# RevOps360 — Sales Pipeline & Revenue Forecasting Suite

## Project Overview
RevOps360 unifies CRM pipeline data and builds a forecasting layer to help 
sales leadership plan weekly and monthly revenue with confidence, instead 
of relying on raw, unweighted pipeline numbers.

## Dataset
**Source:** CRM Sales Opportunities (Maven Analytics, via Kaggle)
**Records:** 8,800 opportunities across 4 linked tables
**Period:** October 2016 – December 2017

Files:
- `sales_pipeline.csv` — opportunity-level data (stage, dates, value)
- `accounts.csv` — company sector, revenue, location
- `products.csv` — product catalog and pricing
- `sales_teams.csv` — sales agents, managers, regional offices

## Key Findings
- **Win Rate:** 63.2% (Won ÷ Won+Lost)
- **Average Deal Size:** $2,361
- **Average Sales Cycle:** 51.8 days
- **Weighted Pipeline Forecast:** $2,511,870 (vs $4,956,861 raw — raw pipeline 
  overstates realistic revenue by ~49%)
- **Sales agent performance gap:** 15.4 percentage points between top and 
  bottom performers — flagged for coaching
- **Win rate declined** from 82% (2016 Q4) to 60% (2017 Q3) as deal volume scaled 6x

## Project Phases
1. **Data Foundation** — cleaned CRM data, built KPI definitions
2. **Pipeline Analytics** — funnel conversion, cohort analysis, bottleneck detection
3. **Forecasting Layer** — weighted forecast model, variance tracking, scenario planning
4. **Executive Dashboard** — region/team drill-down, alerts, board summary report


## Repository Structure
data/        - raw CRM dataset (4 CSV files)
notebooks/   - full analysis code (Python/Pandas)
reports/     - executive dashboard and board summary PDF
docs/        - KPI dictionary and metric definitions

## Tools Used
Python, Pandas, Matplotlib, Google Colab

## Prepared By
Business Analytics Intern
