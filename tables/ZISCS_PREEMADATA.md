# ZISCS_PREEMADATA
**Description:** Customer Email and Program Data
**Total Fields:** 15
**Key Fields:** MANDT, PROG_ID, CA_NO

## Programs Using This Table
- `ziscs1032`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `CA_NO` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `CEMAIL` | CHAR | 100 |  | Customer Email ID |
| 5 | `CNTNUMBER` | NUMC | 8 |  | Contact Number |
| 6 | `REMCOUNT` | NUMC | 2 |  | Reminder Counter for email trigger |
| 7 | `TOKEN` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
| 8 | `VALID_DATE` | DATS | 8 |  | Validity End Date |
| 9 | `STATUS` | CHAR | 1 |  | Status for Customer Registration |
| 10 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 11 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 12 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 13 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 14 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 15 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
