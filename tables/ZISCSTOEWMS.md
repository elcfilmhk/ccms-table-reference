# ZISCSTOEWMS
**Description:** CCMS-EWMS Service Order Information
**Total Fields:** 3
**Key Fields:** MANDT, AUFNR, CHG_DATE

## Programs Using This Table
- `ziscs0002`
- `ziscs0186`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `CHG_DATE` | DATS | 8 | 🔑 | Date |
