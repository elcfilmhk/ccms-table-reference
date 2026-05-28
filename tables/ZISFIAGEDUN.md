# ZISFIAGEDUN
**Description:** Dunning reminder letter for ageing account table
**Total Fields:** 6
**Key Fields:** MANDT, VKONT, BATCHDATE

## Programs Using This Table
- `zisfi0170`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `BATCHDATE` | DATS | 8 | 🔑 | Batch run date |
| 4 | `OVERDUE` | CURR | 13 |  | Overdue Charge |
| 5 | `DUE_DATE` | DATS | 8 |  | Due Date |
| 6 | `BATPRT_DATE` | DATS | 8 |  | Batch print Date |
