# ZISMDCHGDEVICE
**Description:** Device & Register Group Change Log
**Total Fields:** 8
**Key Fields:** MANDT, DATUM, UZEIT, TCODE, GERAET

## Programs Using This Table
- `zismd0011`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATUM` | DATS | 8 | 🔑 | System Date |
| 3 | `UZEIT` | TIMS | 6 | 🔑 | System Time |
| 4 | `TCODE` | CHAR | 20 | 🔑 | Transaction Code |
| 5 | `GERAET` | CHAR | 18 | 🔑 | Serial Number |
| 6 | `ZWGRUPPE` | CHAR | 8 |  | Register Group |
| 7 | `PRCIND` | CHAR | 1 |  | Processed Indicator |
| 8 | `PRCDT` | DATS | 8 |  | Processed Date |
