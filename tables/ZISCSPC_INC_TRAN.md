# ZISCSPC_INC_TRAN
**Description:** Incentive Transaction Table
**Total Fields:** 17
**Key Fields:** MANDT, ROW_ID

## Programs Using This Table
- `ziscs0813`
- `ziscs0832`
- `ziscspc_eec_action_badges`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ROW_ID` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 3 | `PROG_ID` | CHAR | 8 |  | Programme ID |
| 4 | `BP` | CHAR | 17 |  | Partner number |
| 5 | `CA` | CHAR | 12 |  | Contract Account Number |
| 6 | `INCENTIVE_TYPE` | CHAR | 10 |  | Incentive Type |
| 7 | `INCENTIVE_CODE` | CHAR | 4 |  | Incentive Code |
| 8 | `INCENTIVE` | CHAR | 10 |  | Incentive 1 |
| 9 | `UNIT` | NUMC | 3 |  | Incentive Unit |
| 10 | `INC_RECV_DATE` | DATS | 8 |  | Incentive Date |
| 11 | `ACTIVATION_STATUS` | CHAR | 1 |  | Activate Tips |
| 12 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 13 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 14 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 15 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 16 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 17 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
