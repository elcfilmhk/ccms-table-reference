# ZISCS_NGOUROLE
**Description:** Table for NGO User Role
**Total Fields:** 9
**Key Fields:** MANDT, NGOUROLE

## Programs Using This Table
- `ziscspc_ngo_myprofile_hq======ft`
- `ziscspc_ngo_myprofile_hq_sdu==ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `NGOUROLE` | NUMC | 2 | 🔑 | NGO User Role |
| 3 | `DESCRIPTION` | CHAR | 100 |  | General Description |
| 4 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 5 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 6 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 7 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 8 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 9 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
