# ZISCSPC_TEAM_MIS
**Description:** Team mission details
**Total Fields:** 17
**Key Fields:** MANDT, PROG_ID, TEAM_ID, EMAILID

## Programs Using This Table
- `z_pc_team_change==============ft`
- `z_pc_team_create==============ft`
- `z_pc_team_get_details=========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `TEAM_ID` | NUMC | 10 | 🔑 | Team ID |
| 4 | `EMAILID` | CHAR | 100 | 🔑 | Customer Email ID |
| 5 | `CANUMBER` | CHAR | 12 |  | Contract Account Number |
| 6 | `ROLE` | CHAR | 1 |  | Team Role |
| 7 | `ALIAS_NAME` | CHAR | 40 |  | User Alias |
| 8 | `TOKEN` | RAW | 16 |  | Globally Unique Identifier |
| 9 | `JOINING_STATUS` | CHAR | 1 |  | Joining Status |
| 10 | `MISSION_STATUS` | CHAR | 1 |  | Misson Status |
| 11 | `COMPLETION_DATE` | DATS | 8 |  | Completion Date |
| 12 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 13 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 14 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 15 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 16 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 17 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
