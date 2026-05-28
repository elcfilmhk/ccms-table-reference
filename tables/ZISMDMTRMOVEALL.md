# ZISMDMTRMOVEALL
**Description:** Meter Movement Change Log
**Total Fields:** 8
**Key Fields:** MANDT, DATUM, UZEIT, TCODE, GERAETALT, GERAETNEU

## Programs Using This Table
- `zismd0011`
- `zismd0040`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATUM` | DATS | 8 | 🔑 | System Date |
| 3 | `UZEIT` | TIMS | 6 | 🔑 | System Time |
| 4 | `TCODE` | CHAR | 20 | 🔑 | Transaction Code |
| 5 | `GERAETALT` | CHAR | 18 | 🔑 | Old device |
| 6 | `GERAETNEU` | CHAR | 18 | 🔑 | New device |
| 7 | `ANLAGE` | CHAR | 10 |  | Installation |
| 8 | `EADAT` | DATS | 8 |  | Activity Date |
