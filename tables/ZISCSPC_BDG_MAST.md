# ZISCSPC_BDG_MAST
**Description:** Incentive Management : Badge Master
**Total Fields:** 16
**Key Fields:** MANDT, PROG_ID, BADGE_CODE

## Programs Using This Table
- `ziscs0832`
- `ziscspc_eec_action_badges`
- `ziscspc_insert_badge==========ft`
- `ziscspc_insert_game_result====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `BADGE_CODE` | CHAR | 4 | 🔑 | Badge Code |
| 4 | `INCENTIVE_ID` | CHAR | 10 |  | Incentive ID |
| 5 | `BADGE_TYPE` | CHAR | 5 |  | Badge Type |
| 6 | `BADGE_NEXT` | CHAR | 4 |  | Next Badge |
| 7 | `REWARDS_BADGE` | CHAR | 4 |  | Rewards Badge |
| 8 | `PRE_SORT_KEY` | NUMC | 4 |  | Pre sort of badge |
| 9 | `VALID_FROM` | DATS | 8 |  | Date valid from |
| 10 | `VALID_TO` | DATS | 8 |  | Date valid to |
| 11 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 12 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 13 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 14 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 15 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 16 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
