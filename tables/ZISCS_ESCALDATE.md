# ZISCS_ESCALDATE
**Description:** Table for summer and annual energy save calculation dates
**Total Fields:** 13
**Key Fields:** MANDT, PROG_ID, ES_CODE

## Programs Using This Table
- `ziscs0823`
- `ziscs0825`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `ES_CODE` | CHAR | 1 | 🔑 | Single-Character Flag |
| 4 | `START_DATE` | DATS | 8 |  | Start Date |
| 5 | `END_DATE` | DATS | 8 |  | End date |
| 6 | `CAL_DATE` | DATS | 8 |  | Period Calculation Start date |
| 7 | `CUTOFF_DATE` | DATS | 8 |  | Cut Off Date |
| 8 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 9 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 10 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 11 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 12 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 13 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
