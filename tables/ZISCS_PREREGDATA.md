# ZISCS_PREREGDATA
**Description:** Customer Pre-Registration Data
**Total Fields:** 16
**Key Fields:** MANDT, PROG_ID, RECORD_ID

## Programs Using This Table
- `ziscs0806`
- `ziscs1031`
- `ziscs_pc_cust_prereg==========ft`
- `ziscspc_comm_frmwrk_trigger===ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `RECORD_ID` | NUMC | 10 | 🔑 | Record ID |
| 4 | `CEMAIL` | CHAR | 100 |  | Customer Email ID |
| 5 | `CNTNUMBER` | CHAR | 8 |  | Contact Number |
| 6 | `CA_NO` | CHAR | 12 |  | Contract Account Number |
| 7 | `REMCOUNT` | NUMC | 2 |  | Reminder Counter for email trigger |
| 8 | `TOKEN` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
| 9 | `VALID_DATE` | DATS | 8 |  | Validity End Date |
| 10 | `STATUS` | CHAR | 1 |  | Status for Customer Registration |
| 11 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 12 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 13 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 14 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 15 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 16 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
