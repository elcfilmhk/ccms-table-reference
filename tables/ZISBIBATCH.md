# ZISBIBATCH
**Description:** Bill Batching
**Total Fields:** 7
**Key Fields:** MANDT, BATCH_NO

## Programs Using This Table
- `zis_batch_insert_message======ft`
- `zis_new_batch_criteria========ft`
- `zisbi0005`
- `zisbi0010`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCH_NO` | NUMC | 10 | 🔑 | Batch Number |
| 3 | `DESCRIPTION` | CHAR | 50 |  | Description |
| 4 | `VALID_FROM` | DATS | 8 |  | Valid From Date |
| 5 | `VALID_TO` | DATS | 8 |  | Valid To Date |
| 6 | `PRIORITY` | NUMC | 6 |  | Priority |
| 7 | `DISPLOC` | CHAR | 10 |  | Dispatch Location |
