# ZISFIRECONA
**Description:** Reconciliation Header data
**Total Fields:** 34
**Key Fields:** MANDT, KEYZ1, RDATE, OFFIC_EX

## Programs Using This Table
- `zisfi0313`
- `zisfi0318`
- `zisfi0319`
- `zisfi0323`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `KEYZ1` | CHAR | 12 | 🔑 | Payment Lot |
| 3 | `RDATE` | CHAR | 8 | 🔑 | Date in CHAR Format |
| 4 | `OFFIC_EX` | CHAR | 35 | 🔑 | External ID of Branch or Agent |
| 5 | `SUCCESS` | CHAR | 1 |  | Validation result 1: True 0: False |
| 6 | `ERROR_CODE` | CHAR | 3 |  | Error Code |
| 7 | `STYPE` | CHAR | 1 |  | Record Type for Payment Lot Transfer |
| 8 | `TBNAM` | CHAR | 30 |  | Table Name |
| 9 | `KEYZ2` | CHAR | 40 |  | Search Term for Payment Lot |
| 10 | `FIKEY` | CHAR | 12 |  | Reconciliation Key for General Ledger |
| 11 | `BVRKO` | CHAR | 10 |  | Bank clearing account |
| 12 | `BUKRS` | CHAR | 4 |  | Company Code |
| 13 | `GSBER` | CHAR | 4 |  | Business Area |
| 14 | `BLART` | CHAR | 2 |  | Document Type |
| 15 | `WAERS` | CUKY | 5 |  | Currency Key |
| 16 | `KURSF` | CHAR | 10 |  | Exchange Rate (Batch Input) |
| 17 | `BUDAT` | CHAR | 8 |  | Posting Date in Document (Batch Input) |
| 18 | `BLDAT` | CHAR | 8 |  | Document date (batch input) |
| 19 | `VALUT` | CHAR | 8 |  | Value date (batch input) |
| 20 | `XEIPH` | CHAR | 1 |  | Create Line Item in General Ledger |
| 21 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 22 | `XEBOK` | CHAR | 1 |  | Single Posting of Payment Already Completed |
| 23 | `XPOSA` | CHAR | 1 |  | Items Must Not Be Entered Manually |
| 24 | `XSCHS` | CHAR | 1 |  | Check Lot |
| 25 | `INFOF` | CHAR | 50 |  | Additional information |
| 26 | `KTSUS` | CHAR | 15 |  | Specified Debit Total (Batch Input) |
| 27 | `KTSUH` | CHAR | 15 |  | Specified Credit Total |
| 28 | `KSUMP` | NUMC | 6 |  | Specified Number of Items |
| 29 | `XCRDS` | CHAR | 1 |  | Payment card lot |
| 30 | `XZAUS` | CHAR | 1 |  | Lot for Payment Orders |
| 31 | `CCZAH` | CHAR | 1 |  | Processing Card Payment |
| 32 | `XNSEB` | CHAR | 1 |  | Do Not Create Posting for Check Deposit |
| 33 | `ZHANC` | CHAR | 1 |  | Handling Charge Posted |
| 34 | `ZTIMESTAMP` | CHAR | 14 |  | Time Stamp |
