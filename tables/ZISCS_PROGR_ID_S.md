# ZISCS_PROGR_ID_S
**Description:** BAPI structure for ZISCS_PROGR_ID tble
**Total Fields:** 15
**Key Fields:** _none_

## Programs Using This Table
- `ziscspc_bapi_progr_id=========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `PROG_ID` | CHAR | 8 |  | Programme ID |
| 3 | `PROG_DESC` | CHAR | 30 |  | Programme Description |
| 4 | `VALID_FROM` | DATS | 8 |  | Programme Valid From |
| 5 | `VALID_UPTO` | DATS | 8 |  | Programme Valid Upto |
| 6 | `NGO_EDIT_LOCK_DATE` | DATS | 8 |  | NGO Edit Lock Date |
| 7 | `QUOTA` | CHAR | 10 |  | Quota |
| 8 | `QUOTA_HIDE` | CHAR | 1 |  | Quota Hide |
| 9 | `NGO_MASK` | CHAR | 1 |  | NGO Mask |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `ERZET` | TIMS | 6 |  | Entry time |
| 13 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 14 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 15 | `AEZET` | TIMS | 6 |  | Time last change was made |
