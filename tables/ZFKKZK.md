# ZFKKZK
**Description:** Transfer structure:Header data (payment lot transfer)
**Total Fields:** 27
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0023`
- `zisfi0133`
- `zisfi0160`
- `zisfi0163`
- `zisfi0196`
- `zisfi0209`
- `zisfi0222`
- `zisfi0233`
- `zisfi0252`
- `zisfi0318`
- `zisfi0323`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `STYPE` | CHAR | 1 |  | Record Type for Payment Lot Transfer |
| 2 | `TBNAM` | CHAR | 30 |  | Table Name |
| 3 | `KEYZ1` | CHAR | 12 |  | Payment Lot |
| 4 | `KEYZ2` | CHAR | 40 |  | Search Term for Payment Lot |
| 5 | `FIKEY` | CHAR | 12 |  | Reconciliation Key for General Ledger |
| 6 | `BVRKO` | CHAR | 10 |  | Bank clearing account |
| 7 | `BUKRS` | CHAR | 4 |  | Company Code |
| 8 | `GSBER` | CHAR | 4 |  | Business Area |
| 9 | `BLART` | CHAR | 2 |  | Document Type |
| 10 | `WAERS` | CUKY | 5 |  | Currency Key |
| 11 | `KURSF` | CHAR | 10 |  | Exchange Rate (Batch Input) |
| 12 | `BUDAT` | CHAR | 8 |  | Posting Date in Document (Batch Input) |
| 13 | `BLDAT` | CHAR | 8 |  | Document date (batch input) |
| 14 | `VALUT` | CHAR | 8 |  | Value date (batch input) |
| 15 | `XEIPH` | CHAR | 1 |  | Create Line Item in General Ledger |
| 16 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 17 | `XEBOK` | CHAR | 1 |  | Single Posting of Payment Already Completed |
| 18 | `XPOSA` | CHAR | 1 |  | Items Must Not Be Entered Manually |
| 19 | `XSCHS` | CHAR | 1 |  | Check Lot |
| 20 | `INFOF` | CHAR | 50 |  | Additional information |
| 21 | `KTSUS` | CHAR | 15 |  | Specified Debit Total (Batch Input) |
| 22 | `KTSUH` | CHAR | 15 |  | Specified Credit Total |
| 23 | `KSUMP` | NUMC | 6 |  | Specified Number of Items |
| 24 | `XCRDS` | CHAR | 1 |  | Payment card lot |
| 25 | `XZAUS` | CHAR | 1 |  | Lot for Payment Orders |
| 26 | `CCZAH` | CHAR | 1 |  | Processing Card Payment |
| 27 | `XNSEB` | CHAR | 1 |  | Do Not Create Posting for Check Deposit |
