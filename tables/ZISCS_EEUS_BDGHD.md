# ZISCS_EEUS_BDGHD
**Description:** EEUS Budget Period Header
**Total Fields:** 11
**Key Fields:** MANDT, ELIG_CUST_TYPE, START_DATE, END_DATE

## Programs Using This Table
- `ziscs0724`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ELIG_CUST_TYPE` | CHAR | 1 | 🔑 | Eligible Customer Type |
| 3 | `START_DATE` | DATS | 8 | 🔑 | Effective Start Date |
| 4 | `END_DATE` | DATS | 8 | 🔑 | Effective END Date |
| 5 | `EEUS_SCHEME_END` | DATS | 8 |  | EEUS Scheme end date |
| 6 | `TOT_FUND_ALLOC` | CURR | 13 |  | Total Fund ($m) |
| 7 | `INDICATOR_FLG` | CHAR | 1 |  | Flag |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 11 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
