# ZISSDADDCA
**Description:** Additional CA for the sales quotation/order
**Total Fields:** 15
**Key Fields:** MANDT, QUOTATION_NO, SALES_ORDER_NO, CA_NO

## Programs Using This Table
- `zissd00114`
- `zsdsodl05`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `QUOTATION_NO` | CHAR | 10 | 🔑 | Quotation No |
| 3 | `SALES_ORDER_NO` | CHAR | 10 | 🔑 | Sales Order No |
| 4 | `CA_NO` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `CREATE_DATE` | DATS | 8 |  | Create date |
| 6 | `CREATE_TIME` | TIMS | 6 |  | Create time |
| 7 | `CREATE_BY` | CHAR | 12 |  | Create by |
| 8 | `UPDATE_DATE` | DATS | 8 |  | Last update date |
| 9 | `UPDATE_TIME` | TIMS | 6 |  | Last update time |
| 10 | `UPDATE_BY` | CHAR | 12 |  | Last updated by |
| 11 | `MAIN_CA` | CHAR | 1 |  | Main CA |
| 12 | `DIFF_CO` | CHAR | 1 |  | Diff. Connection Object |
| 13 | `VALID_FROM` | DATS | 8 |  | Valid From |
| 14 | `VALID_TO` | DATS | 8 |  | Valid To |
| 15 | `REASON` | CHAR | 30 |  | Reason |
