# ZISCS_NGOCODE
**Description:** Table for Organization Information
**Total Fields:** 15
**Key Fields:** MANDT, HQCODE, BHCODE

## Programs Using This Table
- `ziscs0800`
- `ziscs0800_c`
- `ziscs0800_c1`
- `ziscspc_ngo_myprofile_hq======ft`
- `ziscspc_ngo_myprofile_hq_sdu==ft`
- `ziscspc_ngo_search_hq=========ft`
- `ziscspc_ngo_search_hq_sdu=====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HQCODE` | CHAR | 5 | 🔑 | Head Quarter Code |
| 3 | `BHCODE` | CHAR | 8 | 🔑 | Branch Code |
| 4 | `NGOUN` | CHAR | 30 |  | Contact Person |
| 5 | `BHNAME` | CHAR | 50 |  | Branch Name |
| 6 | `ADDRESS` | CHAR | 100 |  | Address field |
| 7 | `PHONE` | NUMC | 8 |  | NGO Contact |
| 8 | `NGO_LEVEL` | CHAR | 2 |  | NGO Level |
| 9 | `DISABLE_LOGIN` | CHAR | 1 |  | Able Login |
| 10 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 11 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 12 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 13 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 14 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 15 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
