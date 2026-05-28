# ZIS_ADL_TRANS
**Description:** Automated Domeo Account Linkage (ADL)
**Total Fields:** 16
**Key Fields:** MANDT, TRANS_ID

## Programs Using This Table
- `ziscs0494`
- `ziscs0561`
- `ziscs0564`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TRANS_ID` | CHAR | 32 | 🔑 | ADL Transaction ID |
| 3 | `TRANS_STATUS` | NUMC | 2 |  | Automated Domeo Account Linkage Status |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `EMAIL_ID` | CHAR | 241 |  | E-Mail Address |
| 6 | `FIRST_NAME` | CHAR | 40 |  | First Name of Business Partner (Person) |
| 7 | `LAST_NAME` | CHAR | 40 |  | Last Name of Business Partner (Person) |
| 8 | `DOMEO_ID` | CHAR | 100 |  | Domeo ID |
| 9 | `POINT_MIG` | CHAR | 1 |  | ADL Point Migration |
| 10 | `REMARK` | CHAR | 255 |  | ADL Remark (Message) |
| 11 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 12 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 13 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 14 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 15 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 16 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
