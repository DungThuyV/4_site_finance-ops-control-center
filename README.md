# Finance Operations Control Center

**A web-based Finance Operations platform integrating reconciliation, 
settlement monitoring, exception management, fee validation, 
invoice matching, and financial analytics.**

🔗 [Live Demo](https://dungthuyv.github.io/4_site_finance-ops-control-center/)
📁 [GitHub](https://github.com/DungThuyV/4_site_finance-ops-control-center)

---

## Overview

Designed and built to simulate real-world Finance Operations workflows — 
bringing six core functions into a single operational platform. Built to 
reflect the daily responsibilities of Finance Operations, Reconciliation, 
and Payment Operations teams at banks, fintech companies, and MNCs.

> *"I designed and developed a Finance Operations Control Center that 
> automates reconciliation, settlement monitoring, exception management, 
> fee validation, payment matching, and operational analytics into a 
> single workflow."*

---

## Modules

### Module 1 — Reconciliation Engine
- Upload bank statement + internal ledger (CSV)
- Automatic transaction matching by date and amount
- Supports 5 reconciliation types: Transaction, Settlement, Invoice, Vendor, Fee
- Classifies exceptions: Matched, Amount Mismatch, Missing in Bank/Ledger
- Calculates total financial exposure

### Module 2 — Exception Management
- Exception register with unique IDs and severity levels (High/Medium/Low)
- Full workflow: Open → Investigating → Resolved
- Assign owner, document root cause, add resolution notes
- Timestamp tracking on every status change

### Module 3 — Settlement Monitoring
- Expected vs actual settlement comparison
- Breakdown by: fees, refunds, chargebacks, FX differences, adjustments
- Provider-level settlement rate analysis
- Auto-flag providers below 98% settlement rate threshold

### Module 4 — Fee & Tariff Validation
- Upload contract tariff table (provider, transaction type, agreed rate)
- Compare expected vs actual fees charged
- Calculate fee variance per provider
- Flag unauthorized overcharging

### Module 5 — Invoice & Payment Matching
- Match invoices against payments
- Classify: Paid, Partial payment, Late, Overdue, Current
- Calculate DSO (Days Sales Outstanding) and collection rate
- AR Aging analysis: 0-30, 31-60, 61-90, 90+ days buckets

### Module 6 — Analytics, Controls & Reports
- **Performance dashboard**: reconciliation rate, exception rate, 
  settlement accuracy, outstanding amount
- **Financial Exposure**: breakdown by exception type
- **Data Quality**: 4 automated checks (duplicates, amounts, 
  dates, required fields)
- **Audit Trail**: automatic logging of all user actions with timestamps
- **Export**: CSV reports for reconciliation, exceptions, 
  invoices, and fees

---

## Business value

| Without this tool | With this tool |
|---|---|
| Manual Excel reconciliation (2-3 hrs/month) | Automated matching in seconds |
| Exceptions tracked in email threads | Structured register with owner & resolution |
| Settlement variances discovered late | Real-time monitoring with auto-flags |
| Fee overcharging undetected | Automated contract vs actual validation |
| AR aging done manually | Instant aging buckets and DSO |
| No audit trail | Every action logged with timestamp |

---

## Tech stack

| | |
|---|---|
| Frontend | HTML5, CSS3, JavaScript (vanilla) |
| Data processing | Client-side CSV parsing & matching engine |
| Deployment | GitHub Pages (free, no backend required) |
| Data privacy | All processing in-browser — no data uploaded to any server |

---

## CSV format

```csv
id, date, description, amount
TXN001, 2024-01-05, Vendor A payment, 15000
TXN002, 2024-01-08, Client X invoice, 32000
```
Date: YYYY-MM-DD | Amount: numeric only

---

## Skills demonstrated

**Financial Operations**
Transaction reconciliation · Settlement monitoring · Exception management · 
Fee governance · Invoice matching · AR aging · Audit compliance

**Data Analytics**
Reconciliation rate · Exception rate · Financial exposure · 
Trend analysis · Root-cause classification · DSO calculation

**Process Automation**
Automated matching logic · Exception flagging · Severity scoring · 
Workflow management · Report generation

**Technical**
JavaScript · CSV processing · Data validation · 
Client-side architecture · GitHub Pages deployment

---

## Portfolio

Part of a Finance & Banking Operations analytics portfolio:

| Project | Tools | Focus |
|---|---|---|
| [Finance Ops Control Center](https://github.com/DungThuyV/4_site_finance-ops-control-center) | JavaScript, HTML | Operations automation |
| [Banking Transaction Monitoring](https://github.com/DungThuyV/banking-transaction-monitoring-automation) | MySQL, Looker Studio | Revenue analytics |
| [Fraud Detection Analytics](https://github.com/DungThuyV/transaction-fraud-detection-analytics) | MySQL | Financial crime |
| [Payment Reconciliation Dashboard](https://github.com/DungThuyV/1_payment-reconciliation-dashboard) | Excel, MySQL | Reconciliation |

---

*Built by Dung Vo · Finance & Banking Operations · 2026*  
*[github.com/DungThuyV](https://github.com/DungThuyV)*
