# ZISMWALERTCOUNT
**Description:** Middleware job alert counter
**Total Fields:** 5
**Key Fields:** MANDT, TRANS_ID

## Programs Using This Table
- `ziscrm0035`
- `ziscrm0053`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TRANS_ID` | CHAR | 20 | 🔑 | Middle ware error transaction id |
| 3 | `ERRCOUNT` | NUMC | 2 |  | Error count |
| 4 | `ERRORDATE` | DATS | 8 |  | Date |
| 5 | `SKIP` | CHAR | 1 |  | Single-Character Flag |
