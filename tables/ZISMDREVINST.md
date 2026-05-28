# ZISMDREVINST
**Description:** Meter Movement Change (Installation reversal)
**Total Fields:** 7
**Key Fields:** MANDT, DATUM, UZEIT, TCODE, GERAETNEU

## Programs Using This Table
- `zisem0003`
- `zismd0011`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATUM` | DATS | 8 | 🔑 | System Date |
| 3 | `UZEIT` | TIMS | 6 | 🔑 | System Time |
| 4 | `TCODE` | CHAR | 20 | 🔑 | Transaction Code |
| 5 | `GERAETNEU` | CHAR | 18 | 🔑 | New device |
| 6 | `ANLAGE` | CHAR | 10 |  | Installation |
| 7 | `EADAT` | DATS | 8 |  | Activity Date |
