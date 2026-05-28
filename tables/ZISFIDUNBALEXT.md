# ZISFIDUNBALEXT
**Description:** Dunning Balance Extraction
**Total Fields:** 11
**Key Fields:** MANDT, RUN_MONTH, VKONT, DUE_DATE, BALANCE_TYPE

## Programs Using This Table
- `zisfi0272`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUN_MONTH` | CHAR | 6 | 🔑 | Report Month |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `DUE_DATE` | DATS | 8 | 🔑 | Dunning Due Date |
| 5 | `BALANCE_TYPE` | CHAR | 2 | 🔑 | Balance Type |
| 6 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 7 | `MAHNV` | CHAR | 2 |  | Dunning Procedure |
| 8 | `BETRW` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 9 | `RUN_DATE` | DATS | 8 |  | Run Date |
| 10 | `RUN_TIME` | TIMS | 6 |  | Run Time |
| 11 | `WAERS` | CUKY | 5 |  | Transaction Currency |
