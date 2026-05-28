# ZISCS_RWD_PROG
**Description:** Table for Rewarde Programmes
**Total Fields:** 10
**Key Fields:** MANDT, PROG_ID, VKONT, REWARD_PROG

## Programs Using This Table
- `ziscs0835`
- `ziscspc_check_reward==========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `REWARD_PROG` | CHAR | 1 | 🔑 | Rewarde Programme |
| 5 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 6 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 7 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 8 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 9 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 10 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
