# ZISCS_PRIO_QUOTA
**Description:** Beneficiary Quota based on voting data
**Total Fields:** 15
**Key Fields:** MANDT, PROG_ID, BEN_ID

## Programs Using This Table
- `z_iscspc_subsidy_lock_fail====ft`
- `ziscs0815`
- `ziscs0815_01`
- `ziscs0828`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `BEN_ID` | CHAR | 2 | 🔑 | Beneficiary ID |
| 4 | `VOTE_CNT` | NUMC | 8 |  | Voting Count |
| 5 | `VOTE_PCT` | DEC | 7 |  | Quota Perecentage |
| 6 | `PRIORITY_Q` | CHAR | 10 |  | Quota |
| 7 | `ACTUAL_Q` | CHAR | 10 |  | Quota |
| 8 | `PRIORITY_Q1` | CHAR | 10 |  | Quota |
| 9 | `CLP_CHOICE` | CHAR | 10 |  | Quota |
| 10 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 11 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 12 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 13 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 14 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 15 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
