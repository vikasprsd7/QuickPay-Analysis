# Project Overview
This case study focuses on analyzing payment transaction data to evaluate merchant performance and financial risk. The primary goal was to transform raw, fragmented transaction logs into actionable business insights regarding revenue, disputes (chargebacks), and regional risk profiles.

## The Workflow
The project followed a structured data engineering and analysis pipeline:

## Data Cleaning & Normalization:

- Standardized merchant names (removing inconsistent spacing and casing).

- Handled missing values and synchronized currency exchange rates.

## Enrichment:

- Calculated transaction values in a base currency (USD) for unified reporting.

- Flagged high-risk and high-value transactions based on risk scores and transaction amounts.

## Aggregation & Analysis:

- Used **SQL** for complex querying (identifying top merchants, calculating chargeback percentages, and monitoring daily success rates,etc.).

- Used **Python (Pandas)** to bucket data by dimensions: Time, Region, Payment Method, and Merchant Category.

Final Output:

Generated summary reports and CSV files to provide stakeholders with a clear view of health metrics (GMV, Chargeback Rates, and Failure Trends).
