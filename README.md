Tata Motors 3-Statement Financial Model (2016-2025)
Project Overview
This repository contains a fully dynamic, 10-year historical and projected financial model for Tata Motors Limited. The model integrates the three core financial statements—Income Statement, Balance Sheet, and Cash Flow Statement—ensuring that all accounting linkages are maintained automatically.

The goal of this project was to bridge the gap between raw financial data and actionable equity research analysis by building a scalable Excel framework.

Data Source & Architecture
Primary Source: Historical data (FY2016 - FY2025) sourced from Screener.in.

Data Plumbing: Built a dedicated "Data Sheet" to house raw exports. I used SUMIF and IFERROR formulas to map raw line items to the main financial statements. This ensures that the model remains "break-proof" even if the raw data structure changes slightly.

Standardization: Cleaned and reclassified various "Other" line items to ensure the Balance Sheet balances and the Cash Flow Statement accurately reflects the indirect method.

Key Features
10-Year Depth: Provides a decade of historical context to identify long-term margin trends and capital allocation patterns.

Dynamic Projections: Forecasting is driven by both absolute sales amounts and percentage growth assumptions.

Interlinked Statements: * Net Income flows from the P&L to Retained Earnings on the Balance Sheet.

The Cash Flow Statement (Indirect Method) reconciles Net Income to the Ending Cash Balance.

The Ending Cash Balance links back to the Balance Sheet, completing the circular logic.

Visual Formatting: Applied institutional formatting standards. Key line items (EBITDA, Net Profit, Total Assets) are highlighted for quick readability.

How to Use the Model
Assumptions: Go to the main sheet and look for cells formatted in Blue (Standard finance practice for inputs).

Scenario Analysis: Change the Sales Growth % or Expense Margins to see the real-time impact on the projected Cash Flow and Balance Sheet health.

Audit: You can trace any number back to the "Data Sheet" to see exactly how the SUMIF logic aggregates the raw numbers.
