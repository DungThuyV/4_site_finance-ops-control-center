# 4_site_finance-ops-control-center
A Finance Operations Control Center for reconciliation, exception management and financial analysis.
# Finance Operations Control Center

**A web-based finance operations tool for automated payment reconciliation, 
exception management, and financial analytics.**

🔗 [Live Demo](https://dungthuyv.github.io/4_site_finance-ops-control-center/)

---

## Overview

A simulated Finance Operations Control Center built to demonstrate 
reconciliation, exception management, financial analysis, and process 
automation skills — reflecting real-world workflows used by Finance 
Operations teams at banks, fintech companies, and MNCs.

Upload your own bank statement and internal ledger CSV files, and the 
tool automatically matches transactions, classifies exceptions, 
quantifies financial exposure, and generates downloadable reports.

---

## Business problem solved

Finance Operations teams spend significant time manually reconciling 
bank statements against internal ledgers — identifying mismatches, 
missing entries, and unresolved exceptions. This tool automates that 
process end-to-end, reducing manual effort and improving accuracy.

---

## Features

**Reconciliation engine**
- Upload bank.csv and ledger.csv
- Automatic transaction matching by date and amount
- Classifies exceptions: Missing in bank, Missing in ledger, Amount mismatch
- Calculates financial exposure from unmatched transactions

**Exception management**
- Exception register with unique IDs
- Filter by exception type
- One-click resolve workflow
- Real-time status tracking

**Analytics dashboard**
- Monthly transaction volume trend
- Reconciliation rate by month
- Exception breakdown by type
- Financial exposure summary

**Export**
- Full reconciliation report (CSV)
- Exceptions-only report (CSV)
- Matched transactions report (CSV)

---

## Tech stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript (vanilla) |
| Data processing | Client-side CSV parsing and matching logic |
| Visualization | Custom bar charts |
| Deployment | GitHub Pages |

---

## CSV format

```csv
id, date, description, amount
B001, 2024-01-05, Vendor A payment, 15000
B002, 2024-01-08, Client X invoice, 32000
```

Date format: YYYY-MM-DD  
Amount: numeric only (no $ or commas)

---

## Reconciliation logic
Bank statement + Internal ledger
↓
Match by date + amount (exact)
↓
┌─────────────┬──────────────────┬─────────────────┐
│ Matched │ Amount mismatch │ Missing entry │
│ ✓ Cleared │ ⚠ Flag for review│ ✗ Investigate │
└─────────────┴──────────────────┴─────────────────┘
↓
Calculate financial exposure
↓
Generate exception register + export report
---

## Skills demonstrated

- **Financial Operations** — transaction reconciliation, ledger matching, 
  exception handling, financial exposure calculation
- **Data Analytics** — reconciliation rate, exception rate, trend analysis, 
  root-cause classification
- **Process Automation** — automated matching logic, exception flagging, 
  report generation
- **Technical** — JavaScript, CSV processing, data visualization, 
  GitHub Pages deployment

---

## Portfolio context

This project is part of a banking and finance operations portfolio 
demonstrating SQL, data analytics, and process automation skills.

**Other projects:**
- [Banking Transaction Monitoring & Automation](https://github.com/DungThuyV/banking-transaction-monitoring-automation)
- [Transaction Fraud Detection Analytics](https://github.com/DungThuyV/transaction-fraud-detection-analytics)
- [Payment Reconciliation Dashboard](https://github.com/DungThuyV/1_payment-reconciliation-dashboard)

---

*Built by Dung Vo · 2026 · [GitHub Portfolio](https://github.com/DungThuyV)*
