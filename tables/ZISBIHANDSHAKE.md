# ZISBIHANDSHAKE
**Description:** Table for handshake of data loading
**Total Fields:** 5
**Key Fields:** MANDT, ZEXTRACTOR

## Programs Using This Table
- `zisbi0207`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZEXTRACTOR` | CHAR | 30 | 🔑 | DataSource (OSOA/OSOD) |
| 3 | `LAST_RUN_DATE` | DATS | 8 |  | Last Run Date |
| 4 | `LAST_RUN_TIME` | TIMS | 6 |  | Last Run Time |
| 5 | `BATCH_RUN_DATE` | DATS | 8 |  | Batch Run Date |
