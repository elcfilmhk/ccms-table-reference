# ZBATMTAB01D
**Description:** Transport Management Log
**Total Fields:** 11
**Key Fields:** MANDT, BATCH_NO, TRANS_SEQ

## Programs Using This Table
- `zbatme001d`
- `zbatme005d`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCH_NO` | NUMC | 10 | 🔑 | Batch number |
| 3 | `TRANS_SEQ` | NUMC | 10 | 🔑 | Transport sequence within the same transport batch |
| 4 | `BATCH_IND` | CHAR | 1 |  | Batch dependence indicator |
| 5 | `REMARK` | CHAR | 40 |  | Remark |
| 6 | `TRKORR` | CHAR | 20 |  | Request/Task |
| 7 | `OWNER` | CHAR | 12 |  | Owner of a Request or Task |
| 8 | `REIMPORT` | CHAR | 1 |  | Transport re-import indicator |
| 9 | `IMPLEMENTER` | CHAR | 12 |  | Last Changed by |
| 10 | `IMPORT_DATE` | DATS | 8 |  | Last Changed On |
| 11 | `IMPORT_TIME` | TIMS | 6 |  | Last changed at |
