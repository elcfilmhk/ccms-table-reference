# ZISBISENTOUTTD
**Description:** Transmission and Loss (T&D) and Sentout Maintenenace
**Total Fields:** 10
**Key Fields:** MANDT, PERIOD

## Programs Using This Table
- `zisbi0109`
- `zisfi0083_m2`
- `zisfi0083_m2t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PERIOD` | CHAR | 6 | 🔑 | Date - YearMonth (YYYYMM) |
| 3 | `TDLOSS` | DEC | 8 |  | TD Loss |
| 4 | `SENTOUT` | DEC | 12 |  | Sentout Figures |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERTIM` | TIMS | 6 |  | Create time |
| 8 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 10 | `AETIM` | TIMS | 6 |  | Changed At |
