# ZISBICUSTBILL
**Description:** Installation with Migrated customer Bill date
**Total Fields:** 6
**Key Fields:** MANDT, ANLAGE

## Programs Using This Table
- `zisbiinstgrp`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `VERTRAG` | CHAR | 10 |  | Contract |
| 5 | `PORTION` | CHAR | 8 |  | Alternative portion |
| 6 | `CUST_BILL_DATE` | CHAR | 2 |  | Customer Requested Bill date |
