# ZISDHMRUPC
**Description:** MRU and PackID configuration
**Total Fields:** 14
**Key Fields:** MANDT, MAIN_MRU, MONTH_TYPE

## Programs Using This Table
- `zisdh0021`
- `zisdh0023`
- `zisdm0409`
- `zrdm_dr_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MAIN_MRU` | CHAR | 8 | 🔑 | Main MRU |
| 3 | `MONTH_TYPE` | CHAR | 1 | 🔑 | Meter Reading Month Type |
| 4 | `PACK_ID` | CHAR | 20 |  | Pack ID |
| 5 | `ROUTE_TYPE` | CHAR | 3 |  | Route Type |
| 6 | `DIFF_LEVEL` | INT1 | 3 |  | Difficulty level of route |
| 7 | `READ_TIME` | DEC | 4 |  | Average read time in minutes |
| 8 | `.INCLUDE` | &nbsp; | 0 |  | Administrative data |
| 9 | `CREATION_DATE` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `CREATION_TIME` | TIMS | 6 |  | Creation time |
| 11 | `CREATED_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `CHANGE_DATE` | DATS | 8 |  | Date of Last Change |
| 13 | `CHANGE_TIME` | TIMS | 6 |  | Change time |
| 14 | `CHANGE_BY` | CHAR | 12 |  | Name of person who changed object |
