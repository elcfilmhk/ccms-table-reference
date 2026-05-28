# ZISCSPC_TEAM_HD
**Description:** Team mission header
**Total Fields:** 10
**Key Fields:** MANDT, PROG_ID, TEAM_ID

## Programs Using This Table
- `z_pc_team_create==============ft`
- `z_pc_team_get_details=========ft`
- `z_pc_team_invite==============ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `TEAM_ID` | NUMC | 10 | 🔑 | Team ID |
| 4 | `TEAM_NAME` | CHAR | 50 |  | Team Name |
| 5 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 6 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 7 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 8 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 9 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 10 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
