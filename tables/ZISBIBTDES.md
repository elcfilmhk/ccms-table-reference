# ZISBIBTDES
**Description:** Special handle batches with descriptions
**Total Fields:** 13
**Key Fields:** MANDT, VALID_FROM, VALID_TO, COUNTER

## Programs Using This Table
- `zisbi0005`
- `zisbi0010`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VALID_FROM` | DATS | 8 | 🔑 | Valid From Date |
| 3 | `VALID_TO` | DATS | 8 | 🔑 | Valid To Date |
| 4 | `COUNTER` | NUMC | 5 | 🔑 | Counter for table ZISBIBTDES |
| 5 | `BATCH_NUM1` | NUMC | 10 |  | Batch Number |
| 6 | `BATCH_NUM2` | NUMC | 10 |  | Batch Number |
| 7 | `BATCH_NUM3` | NUMC | 10 |  | Batch Number |
| 8 | `BATCH_NUM4` | NUMC | 10 |  | Batch Number |
| 9 | `BATCH_NUM5` | NUMC | 10 |  | Batch Number |
| 10 | `INS_DESC1` | CHAR | 50 |  | The bill insert description |
| 11 | `INS_DESC2` | CHAR | 50 |  | The bill insert description |
| 12 | `INS_DESC3` | CHAR | 50 |  | The bill insert description |
| 13 | `INS_DESC4` | CHAR | 50 |  | The bill insert description |
