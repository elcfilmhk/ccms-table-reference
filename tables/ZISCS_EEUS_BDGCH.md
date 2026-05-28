# ZISCS_EEUS_BDGCH
**Description:** EEUS Budget Period per Child
**Total Fields:** 12
**Key Fields:** MANDT, ELIG_CUST_TYPE, START_DATE, END_DATE

## Programs Using This Table
- `ziscs0524`
- `ziscs0724`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ELIG_CUST_TYPE` | CHAR | 1 | 🔑 | Eligible Customer Type |
| 3 | `START_DATE` | DATS | 8 | 🔑 | Effective Start Date |
| 4 | `END_DATE` | DATS | 8 | 🔑 | Effective END Date |
| 5 | `RESERVED_FUND` | CURR | 13 |  | Total Fund ($m) |
| 6 | `UTILISED_BUDGET` | CURR | 13 |  | Utilised Budget ($m) |
| 7 | `BALANCE_BUDGET` | CURR | 13 |  | Balance Budget ($m) |
| 8 | `INDICATOR_FLG` | CHAR | 1 |  | Flag |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 12 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
