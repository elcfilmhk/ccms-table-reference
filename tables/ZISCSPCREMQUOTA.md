# ZISCSPCREMQUOTA
**Description:** Remaining Quota for CLP Choice
**Total Fields:** 14
**Key Fields:** _none_

## Programs Using This Table
- `z_iscspcchoicequotacalc=======ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `PROG_ID` | CHAR | 8 |  | Programme ID |
| 3 | `BEN_ID` | CHAR | 2 |  | Beneficiary ID |
| 4 | `VOTE_CNT` | CHAR | 10 |  | Quota |
| 5 | `VOTE_PCT` | DEC | 7 |  | Quota Perecentage |
| 6 | `PRIORITY_Q` | CHAR | 10 |  | Quota |
| 7 | `ACTUAL_Q` | CHAR | 10 |  | Quota |
| 8 | `REM_QUOTA` | CHAR | 10 |  | Quota |
| 9 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 10 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 11 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 12 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 13 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 14 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
