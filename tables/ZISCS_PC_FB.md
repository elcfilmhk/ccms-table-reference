# ZISCS_PC_FB
**Description:** Power Connect Facebook Leads
**Total Fields:** 12
**Key Fields:** MANDT, PROG_ID, EMAIL

## Programs Using This Table
- `ziscs1033`
- `ziscs1034`
- `ziscspc_comm_frmwrk_trigger===ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `EMAIL` | CHAR | 50 | 🔑 | Correspondence email |
| 4 | `TOKEN` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
| 5 | `REMCOUNT` | NUMC | 2 |  | Reminder Counter for email trigger |
| 6 | `STATUS` | CHAR | 1 |  | Status for Customer Registration |
| 7 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 8 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 9 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 10 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 11 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 12 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
