# ZISCS_PC_INVITE
**Description:** Power Connect Invitation email
**Total Fields:** 14
**Key Fields:** MANDT, PROG_ID, CANUMBER

## Programs Using This Table
- `ziscs0807`
- `ziscs0807_test_radica`
- `ziscspc_comm_frmwrk_trigger===ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `CANUMBER` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `EMAILID` | CHAR | 100 |  | Customer Email ID |
| 5 | `CONTACT` | CHAR | 8 |  | Contact Number |
| 6 | `TOKEN` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
| 7 | `REMCOUNT` | NUMC | 2 |  | Reminder Counter for email trigger |
| 8 | `STATUS` | CHAR | 1 |  | Status for Customer Registration |
| 9 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 10 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 11 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 12 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 13 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 14 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
