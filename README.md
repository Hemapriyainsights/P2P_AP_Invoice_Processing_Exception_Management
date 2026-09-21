# P2P AP Invoice Processing & Exception Management

## Project Overview
A practical Procure-to-Pay (P2P) Accounts Payable invoice processing simulation based on SAP S/4HANA-aligned concepts.

## Objective
To simulate invoice validation, 2-way and 3-way matching, exception management, reconciliation, and payment-readiness checks.

## P2P Workflow
Purchase Requisition → Purchase Order → Goods Receipt → Supplier Invoice → 2-Way / 3-Way Matching → Exception Management → Reconciliation → Payment Processing

## Dataset
- 100 vendors
- 1,000 purchase orders
- 1,000 goods receipts
- 1,000 supplier invoices

## Matching Logic
### 2-Way Matching
Compares:
- Purchase Order
- Supplier Invoice

Checks quantity and unit price.

### 3-Way Matching
Compares:
- Purchase Order
- Goods Receipt
- Supplier Invoice

Checks whether ordered, received, and invoiced quantities and prices are consistent before payment.

## Exception Management
The project identifies invoice exceptions including:
- Price mismatch
- Quantity mismatch

Exceptions are routed for investigation before payment processing.

## Reconciliation & KPIs
- Total invoices: 1,000
- Matched invoices: 800
- Exception invoices: 200
- Exception rate: 20%
- Ready for payment: 800

## Tools
- Google Sheets
- Microsoft Excel
- SAP S/4HANA concepts
- Basic SQL

## Key Learning
This project demonstrates practical understanding of:
- Procure-to-Pay operations
- Accounts Payable
- Invoice processing
- 2-way and 3-way matching
- Exception management
- Reconciliation
- Payment readiness

## My Role
Designed the P2P invoice processing workflow, analyzed matching results, identified exceptions, performed reconciliation, and created the operational KPI dashboard.

## Disclaimer
This is a simulated project created for learning and portfolio demonstration. It does not represent production experience with SAP.

## Project Structure

- `P2P_AP_Invoice_Processing_Exception_Management.xlsx` — Complete project workbook containing the dataset, invoice matching, exception management, reconciliation, KPI analysis, and README documentation.
