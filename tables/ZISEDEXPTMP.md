# ZISEDEXPTMP
**Description:** EDM - Temp. export table for job split
**Total Fields:** 5
**Key Fields:** MANDT, AUTOKEY

## Programs Using This Table
- `zised0016`
- `zised0023`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUTOKEY` | NUMC | 10 | 🔑 | Numeric Character Field, Length 10 |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `FROMDATE` | DATS | 8 |  | From-Date |
| 5 | `TODATE` | DATS | 8 |  | To-Date |
