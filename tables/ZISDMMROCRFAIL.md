# ZISDMMROCRFAIL
**Description:** MRO failed to create log table
**Total Fields:** 7
**Key Fields:** MANDT, ABLEINH, EQUNR, ZWNUMMER, ADATSOLL

## Programs Using This Table
- `zisdm0345`
- `zisdm0346`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLEINH` | CHAR | 8 | 🔑 | Meter Reading Unit |
| 3 | `EQUNR` | CHAR | 18 | 🔑 | Equipment Number |
| 4 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 5 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 6 | `ZUORDDAT` | DATS | 8 |  | Meter reading allocation date |
| 7 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
