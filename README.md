Automated 3-Statement Model: Tata Motors (2016-2025)
Executive Summary
This project is a comprehensive financial reconstruction of Tata Motors Passenger Vehicles Ltd. It transforms raw financial exports into a professional-grade, interlinked 3-statement model. The architecture is designed to handle 10 years of historical data while allowing for real-time scenario testing through dynamic forecasting.

Technical Highlights
Robust Data Plumbing: Built a dedicated 'Data Sheet' that acts as a central repository. I used SUMIF and IFERROR logic to automate the flow of raw data into the Financial Statements, eliminating manual entry errors.

Interlinked Logic: * Income Statement: Tracks the journey from Sales (₹2.73L Cr in 2016 to ₹4.39L Cr in 2025) down to PAT.

Balance Sheet: Fully balanced 10-year historical record (2016-2025).

Cash Flow Statement: Built using the indirect method, reconciling operational cash flow (which reached a peak of ₹67,915 Cr in 2024).

Dynamic Forecasting: The model supports forecasting via both absolute amount inputs and YoY percentage growth drivers.

Key Data Insights Captured
Revenue Volatility: Captured the -13.5% dip in 2020 and the massive 24.2% recovery in 2023.

Expense Analysis: Granular tracking of Raw Material Costs and Employee Benefit Expenses across a decade.

Asset Management: Detailed historical view of Inventory and Receivables trends relative to Sales growth.

How to Audit the Model
Inputs: All assumptions are clearly highlighted in Blue as per industry standards.

Mapping: Check the Financials sheet to see how SUMIF pulls data dynamically from the Data Sheet.

Integrity: The model includes a "Check" line to ensure the Balance Sheet always equates to zero (Assets - Liabilities - Equity = 0).
