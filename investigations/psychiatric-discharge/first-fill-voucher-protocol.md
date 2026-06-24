# FIRST-FILL VOUCHER PROTOCOL WORKFLOW

**Purpose:** To establish a standard billing clearing mechanism that prevents transitional post-discharge medication claims from hitting hospital cash-flow lines.

## 1. The Operational Friction Point
Hospitals refuse to open uncompensated outpatient medication pipelines due to delayed verification tracking. Pharmacies require immediate assurance of payment at the point of sale.

## 2. The Clearinghouse Clearing Loop Architecture

[Hospital Discharge Coord.] ➔ Generates Standardized 15-Day Digital Voucher
              │
              ▼
[Regional Pharmacy Network] ➔ Scans Unified Transitional Clearing Code: "IA-HF385"
              │
              ▼
[ASO Risk Pool Ledger] ➔ Bypasses Hospital Accounts Receivable; Settles Bill Direct

## 3. Standardized Voucher Structural Data Parameters
Every transitional voucher issued must strictly contain the following structural data tags to maintain absolute data integrity and prevent fraudulent claims:
* `VOUCHER-ID`: `[ASO-Region-Code]-[Year]-[Sequential-Number]`
* `CLEARING-BIN`: Dedicated state-approved routing number for the Iowa Regional Risk Pool.
* `RX-CLASS-RESTRICTION`: Limited strictly to psychiatric medications prescribed during the acute inpatient window.
* `EXPIRATION-WINDOW`: Hard-coded to self-terminate fifteen (15) days post-issuance.
