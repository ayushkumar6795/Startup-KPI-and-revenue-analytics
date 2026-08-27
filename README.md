# Startup KPI and Revenue Analytics

A collection of financial analysis projects built from public company data. Each project pairs a formula-linked Excel dashboard with a written report, so the numbers and the narrative come from the same source rather than being put together separately.

## Current project: Cloudflare, Inc. (NYSE: NET)

A five-year financial review of Cloudflare covering FY2021 through FY2025, built from the company's own press releases, earnings call transcripts, and SEC 10-K filings, cross-checked against third-party standardized financial data.

**Files in this repo:**

- `Cloudflare_Excel_Dashboard.xlsx`, a three-tab Excel workbook (Raw Data, Calculated KPIs, Dashboard). Every chart and KPI card on the Dashboard tab pulls live from the Raw Data tab through the Calculated KPIs tab, so changing a source number updates the entire model automatically. Nothing on the dashboard is a hardcoded value.
- `Cloudflare_Financial_Review.pdf`, a written report covering revenue growth, gross margin, operating leverage, cash flow, customer retention, geographic mix, and forward-looking indicators (RPO), plus a section flagging the two things in the data that don't fit a clean improvement story: a gross margin dip and a widened operating loss in FY2025.

**What the analysis covers:**

- Revenue and profitability trends, FY2021 to FY2025
- Gross margin and operating expense ratio (R&D, SG&A) as a share of revenue
- Free cash flow and operating cash flow, including the shift from cash-burning to cash-generating
- Customer growth, large-customer concentration, and net dollar retention
- Geographic revenue mix across the US, EMEA, and APAC
- Remaining performance obligations (RPO) as a forward-looking bookings indicator
- Five-year CAGR across revenue, customer count, and free cash flow

**Sources used:** Cloudflare Q4/FY press releases and earnings call transcripts (2021-2025), SEC EDGAR 10-K filings (CIK 1477333), and StockAnalysis.com / S&P Global standardized financials, used to cross-check figures where multiple sources were available.

## Notes

This is a self-directed analysis project, not commissioned or sponsored by Cloudflare. It's meant to demonstrate financial modeling, data reconciliation across sources, and analytical writing, not to serve as investment advice or a recommendation on the stock.

More company case studies may be added to this repo over time, following the same format: one dashboard, one report, per company.
