# ZISCS_NGOUSR_UPD_S
**Description:** NGO User table output BAPI structure
**Total Fields:** 16
**Key Fields:** MANDT, HQCODE, BHCODE, UCODE

## Programs Using This Table
- `ziscs0801`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HQCODE` | CHAR | 5 | 🔑 | Head Quarter Code |
| 3 | `BHCODE` | CHAR | 8 | 🔑 | Branch Code |
| 4 | `UCODE` | CHAR | 12 | 🔑 | User Name in User Master Record |
| 5 | `CNTPERSON` | CHAR | 15 |  | Name of NGO User |
| 6 | `NGOUROLE` | NUMC | 2 |  | NGO User Role |
| 7 | `NGOEML` | CHAR | 50 |  | NGO Email |
| 8 | `NGOCNT` | NUMC | 8 |  | NGO Contact |
| 9 | `BPNUMBER` | CHAR | 10 |  | Business Partner Number |
| 10 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 11 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 12 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 13 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 14 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 15 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
| 16 | `MODE` | CHAR | 1 |  | Mode, Insert - I, Update - U, Delete - D |
