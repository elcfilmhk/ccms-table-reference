# ZISCS_BEN_STAT
**Description:** Beneficiary Status record
**Total Fields:** 12
**Key Fields:** MANDT, BEN_STATUS_CODE

## Programs Using This Table
- `ziscs0800`
- `ziscs0800_c`
- `ziscs0800_c1`
- `ziscs0802`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BEN_STATUS_CODE` | CHAR | 12 | 🔑 | Beneficiary Status Code |
| 3 | `EXCLUDE_STATUS` | CHAR | 1 |  | Allow to change |
| 4 | `BEN_STATUS_TXT` | CHAR | 40 |  | Beneficiary Status Text |
| 5 | `DATA_SRC` | CHAR | 5 |  | Data Source |
| 6 | `PC_INDICATOR` | CHAR | 1 |  | PC_Indicator |
| 7 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 8 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 9 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 10 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 11 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 12 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
