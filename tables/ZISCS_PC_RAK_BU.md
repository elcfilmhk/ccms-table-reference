# ZISCS_PC_RAK_BU
**Description:** Power Connect Beneficiery Ranking Backup
**Total Fields:** 13
**Key Fields:** MANDT, APPLN_REF, PROG_ID

## Programs Using This Table
- `ziscs0855`
- `ziscs0858`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `APPLN_REF` | CHAR | 10 | 🔑 | Application Reference Number |
| 3 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `BEN_TEXT` | CHAR | 12 |  | Beneficiary Type |
| 6 | `HK_ID` | CHAR | 60 |  | Identification Number |
| 7 | `RANK` | NUMC | 8 |  | RANK |
| 8 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 9 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 10 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 11 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 12 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 13 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
