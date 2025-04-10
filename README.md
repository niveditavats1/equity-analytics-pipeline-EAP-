# Equity Analytics Pipeline (EAP)

The Equity Analytics Pipeline (EAP) is a reproducible data pipeline built to integrate daily stock price data (CRSP or equivalent), quarterly financial data (Compustat), and Fama/French factor models. This system computes and aligns firm-level quarterly returns with financial statements and supports automated updates to support investment research and reporting.

## 🔧 Features
- Automated data ingestion for CRSP, Compustat, and Fama/French factors
- SQL-based data storage and transformations
- Quarterly return calculation and alignment with financial data
- Designed for reproducibility and scalability

## 📁 Project Structure
```
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── exploratory_analysis.ipynb
├── sql/
│   ├── create_tables.sql
│   ├── update_crsp_daily.sql
│   ├── update_compustat.sql
│   └── merge_returns_financials.sql
├── scripts/
│   ├── fetch_crsp.py
│   ├── fetch_compustat.py
│   └── calculate_returns.py
├── requirements.txt
├── README.md
└── LICENSE
```

## 🔄 Update Schedule
- CRSP Daily Data: Updated Daily
- Compustat Financials: Updated Quarterly
- Fama/French Factors: Updated Monthly

## 📚 Reference
Based on *Tidy Finance with Python* (2024) by Scheuch et al.
