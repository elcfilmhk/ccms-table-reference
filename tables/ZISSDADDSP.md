# ZISSDADDSP
**Description:** Additional Sales Person
**Total Fields:** 10
**Key Fields:** MANDT, QUOTATION_NO, SALES_ORDER_NO, SALES_PERSON

## Programs Using This Table
- `zsdsodl05`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `QUOTATION_NO` | CHAR | 10 | 🔑 | Quotation No |
| 3 | `SALES_ORDER_NO` | CHAR | 10 | 🔑 | Sales Order No |
| 4 | `SALES_PERSON` | CHAR | 20 | 🔑 | Sales person |
| 5 | `CREATE_DATE` | DATS | 8 |  | Create date |
| 6 | `CREATE_TIME` | TIMS | 6 |  | Create time |
| 7 | `CREATE_BY` | CHAR | 12 |  | Create by |
| 8 | `UPDATE_DATE` | DATS | 8 |  | Last update date |
| 9 | `UPDATE_TIME` | TIMS | 6 |  | Last update time |
| 10 | `UPDATE_BY` | CHAR | 12 |  | Last updated by |
