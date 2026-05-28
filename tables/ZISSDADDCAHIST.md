# ZISSDADDCAHIST
**Description:** History table of Additional CA for the sales quotation/order
**Total Fields:** 11
**Key Fields:** MANDT, QUOTATION_NO, SALES_ORDER_NO, CA_NO, CHANGE_TMST, CHANGE_BY

## Programs Using This Table
- `zissd00114`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `QUOTATION_NO` | CHAR | 10 | 🔑 | Quotation No |
| 3 | `SALES_ORDER_NO` | CHAR | 10 | 🔑 | Sales Order No |
| 4 | `CA_NO` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `CHANGE_TMST` | CHAR | 14 | 🔑 | Created timestamp |
| 6 | `CHANGE_BY` | CHAR | 12 | 🔑 | Create by |
| 7 | `MAIN_CA` | CHAR | 1 |  | Main CA |
| 8 | `DIFF_CO` | CHAR | 1 |  | Diff. Connection Object |
| 9 | `VALID_FROM` | DATS | 8 |  | Valid From |
| 10 | `VALID_TO` | DATS | 8 |  | Valid To |
| 11 | `REASON` | CHAR | 30 |  | Reason |
