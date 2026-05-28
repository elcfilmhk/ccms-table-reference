# ZISBIMCAMP
**Description:** Table for new Marketing Insert
**Total Fields:** 7
**Key Fields:** MANDT, TBLFG, CAMPCODE, VKONT, FMDAT, TODAT

## Programs Using This Table
- `zisbi0058`
- `zisbi0059`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TBLFG` | CHAR | 1 | 🔑 | Table flag |
| 3 | `CAMPCODE` | NUMC | 5 | 🔑 | Campaign code |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `FMDAT` | DATS | 8 | 🔑 | Date |
| 6 | `TODAT` | DATS | 8 | 🔑 | Date |
| 7 | `SELFG` | CHAR | 1 |  | Selection Flag |
