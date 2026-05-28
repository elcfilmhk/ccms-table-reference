# ZISBIESPRT
**Description:** Explanatory statement
**Total Fields:** 12
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0065`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `COLL_TOTAL` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 5 | `CHILD_TOTAL` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 6 | `ES_PRINTED` | CHAR | 1 |  | Is Printed? |
| 7 | `CATCH_DIFF` | CHAR | 1 |  | Catch Difference |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `BATCH_DATE` | DATS | 8 |  | Batch run date |
| 10 | `AEDAT` | DATS | 8 |  | Submit Date |
| 11 | `AETIME` | TIMS | 6 |  | Submit Time |
| 12 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
