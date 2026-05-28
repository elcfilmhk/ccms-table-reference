# ZISFIWAIVEOSDEP
**Description:** Log: waive outstanding security deposit
**Total Fields:** 8
**Key Fields:** MANDT, BATCHDATE, SECURITY, OPBEL

## Programs Using This Table
- `zisfi0126afr`
- `zisfi0126bfb`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCHDATE` | DATS | 8 | 🔑 | Batch run date |
| 3 | `SECURITY` | CHAR | 12 | 🔑 | Security Deposit |
| 4 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `INV_REV_DATE` | DATS | 8 |  | Final Invoice Reversed Date |
| 7 | `REQUEST` | CURR | 11 |  | Requested Amount for Security Deposit |
| 8 | `WAIVE` | CURR | 13 |  | Deposit Amount Waived |
