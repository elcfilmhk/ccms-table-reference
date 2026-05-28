# ZISCSPC_INC_TYPE
**Description:** Incentive Type
**Total Fields:** 11
**Key Fields:** MANDT, INCENTIVE_TYPE

## Programs Using This Table
- `ziscs0824`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `INCENTIVE_TYPE` | CHAR | 10 | 🔑 | Incentive Type |
| 3 | `DESCRIPTION` | CHAR | 40 |  | Character field of length 40 |
| 4 | `DESCRIPTION_ZF` | CHAR | 40 |  | Chinese Description |
| 5 | `TABLE_NAME` | CHAR | 16 |  | Table name, 16 characters |
| 6 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 7 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 8 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 9 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 10 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 11 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
