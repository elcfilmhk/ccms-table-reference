# ZISBICHILDCNT
**Description:** Aditional child bill count during creation of group bill
**Total Fields:** 8
**Key Fields:** MANDT, BATCHDATE, VKONT, OPBEL_CHL, ABWVK, OPBEL_PAR

## Programs Using This Table
- `zisbi0089`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCHDATE` | DATS | 8 | 🔑 | Batch run date |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `OPBEL_CHL` | CHAR | 12 | 🔑 | Number of print document |
| 5 | `ABWVK` | CHAR | 12 | 🔑 | Alternative contract account for collective bills |
| 6 | `OPBEL_PAR` | CHAR | 12 | 🔑 | Print document for collective bill |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `CREATE_TIME` | TIMS | 6 |  | Create time |
