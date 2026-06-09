# ERP: Data Extraction

Structure and analyze data from ERP systems used in real estate and industrial operations.

## Supported Platforms
Yardi (predominant in real estate), MRI Software, SAP, JD Edwards, NetSuite, AppFolio, RealPage

## Primary Use Cases
- General ledger pulls for month-end financial close
- Rent roll and lease data extraction
- Accounts payable/receivable aging analysis
- Property-level P&L statements
- Fixed asset inventory tracking

## Extraction Workflow

1. **Report identification** — Determine data type needed and source system
2. **Data cleaning** — Remove embedded headers, standardize dates (YYYY-MM-DD), normalize debit/credit entries, flag duplicates
3. **Structural organization** — Output cleaned data with summaries, exception lists, analysis-ready tables
4. **Analysis** — Variance reporting, aging bucket analysis, delinquency tracking, cash flow bridges

## Output Deliverables
- Structured data table with clear headers
- Exception report documenting data quality issues
- 3–5 point summary highlighting significant variances or action items

## Platform Notes
- **Yardi**: Use property codes as joining fields
- **SAP**: Map cost centers carefully
- **MRI**: Account for multiple accounting books
