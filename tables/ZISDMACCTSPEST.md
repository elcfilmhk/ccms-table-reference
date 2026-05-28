# ZISDMACCTSPEST
**Description:** Account specific estimation
**Total Fields:** 7
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zisdm0255`
- `zisdm0256`
- `zisdm0321`
- `zisdm0322`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `BAPERTYP` | CHAR | 1 |  | Base period category |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 7 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
