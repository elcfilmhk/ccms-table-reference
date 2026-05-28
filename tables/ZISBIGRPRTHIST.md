# ZISBIGRPRTHIST
**Description:** Group Bill Account Print History
**Total Fields:** 6
**Key Fields:** MANDT, ERDAT, VKONT, OPBEL

## Programs Using This Table
- `zisbi0100`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 5 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 6 | `PRINTED` | CHAR | 1 |  | Is Printed? |
