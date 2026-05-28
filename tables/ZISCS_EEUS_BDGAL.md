# ZISCS_EEUS_BDGAL
**Description:** EEUS Budget Allocation
**Total Fields:** 12
**Key Fields:** MANDT, ELIG_CUST_TYPE, YEAR_ALLOCAT, START_DATE

## Programs Using This Table
- `ziscs0724`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ELIG_CUST_TYPE` | CHAR | 1 | 🔑 | Eligible Customer Type |
| 3 | `YEAR_ALLOCAT` | CHAR | 1 | 🔑 | Allocating Year |
| 4 | `START_DATE` | DATS | 8 | 🔑 | Effective Start Date |
| 5 | `END_DATE` | DATS | 8 |  | Effective END Date |
| 6 | `BUD_ALOC_PERC` | NUMC | 3 |  | Budget allocation % by customer type |
| 7 | `REMARK` | CHAR | 50 |  | Remark |
| 8 | `INDICATOR_FLG` | CHAR | 1 |  | Flag |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 12 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
