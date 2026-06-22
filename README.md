# Titan Company Ltd — Financial Statement Analysis & Forecasting Model

## Overview
This project is a multi-year financial analysis of **Titan Company Ltd** (FY2017–FY2026), built entirely in Excel. It consolidates raw financial statement data, validates and structures it for analysis, and uses it to build a forward-looking forecasting model.

The goal of the project was twofold:
1. Build a clean, accurate, and auditable financial dataset (data integrity first).
2. Use that dataset to derive meaningful business insight through ratio analysis and forecasting.

## Data Source
- Raw financial statements (Profit & Loss, Balance Sheet, Cash Flow) sourced from **Screener.in**.
- Data was cross-checked against reported figures for consistency before being used in any downstream calculation, to ensure accuracy and reliability of the dataset — a core principle of good data management.

## Project Structure
| Sheet | Purpose |
|---|---|
| `Profit & Loss` | Standardized 10-year income statement (Sales, Expenses, Operating Profit, PBT, etc.) |
| `Balance Sheet` | Standardized 10-year balance sheet (Equity, Reserves, Borrowings, Net Block, etc.) |
| `Cash Flow` | Operating, investing, and financing cash flows |
| `Quarters` | Quarterly performance breakdown |
| `Historical FS` | Full historical financial statement detail (data backbone of the model) |
| `Ratio Analysis` | Growth, profitability, and trend ratios (Sales Growth, EBITDA Growth, Net Profit Growth, etc.) with mean/median benchmarks |
| `Forecasting` | Weighted historical-growth model projecting Sales, EBITDA, and EPS, with **Best Case** and **Worst Case** scenarios |
| `Data Sheet` | Underlying raw data used to feed the above calculations |

## Methodology
1. **Data validation:** Verified that figures across statements reconcile (e.g. Net Profit flows correctly from P&L into Balance Sheet reserves) before building any formulas on top of the data — to avoid propagating errors downstream.
2. **Ratio analysis:** Calculated YoY growth rates for Sales, EBITDA, EBIT, Net Profit, and Dividends across a 9-year window, then derived mean and median benchmarks to smooth out one-off volatility (e.g. the COVID-impacted FY2021 dip).
3. **Forecasting model:** Built a weighted trend model that assigns increasing weight to more recent years' growth rates, used to project Sales, EBITDA, and EPS forward, with explicit Best Case and Worst Case bands to reflect a realistic range rather than a single point estimate.

## Key Insights
- Titan's revenue grew from ₹13,260.83 Cr (FY2017) to ₹60,456 Cr (FY2025), a multi-year compounding growth story.
- Profitability growth has been more volatile than topline growth — Net Profit Growth swung from -40.7% (FY2021) to +154.5% (FY2022), highlighting sensitivity to external shocks (e.g. COVID-19).
- The forecasting model projects FY2026 EBITDA in a range bounded by a Best Case and Worst Case scenario, rather than a single deterministic figure — reflecting real-world forecasting uncertainty.

## Skills Demonstrated
- Data accuracy, validation, and reconciliation across multiple financial statements
- Structured data organization for analysis (data management fundamentals)
- Ratio and trend analysis
- Scenario-based financial forecasting
- Advanced Excel (formulas, structured multi-sheet models)

---
*Data sourced from Screener.in. This is an independent analysis project for skill demonstration purposes and is not investment advice.*
