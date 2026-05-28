# ZISCS_PYL_PREGH
**Description:** Power Your Love Pregistration Table
**Total Fields:** 10
**Key Fields:** MANDT, PYL_ID, EMAIL

## Programs Using This Table
- `ziscs0369_pyl`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PYL_ID` | CHAR | 10 | 🔑 | Power Your Love ID |
| 3 | `EMAIL` | CHAR | 100 | 🔑 | Email |
| 4 | `CONTACT` | CHAR | 20 |  | Contact Number |
| 5 | `TOKEN` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
| 6 | `VALID_TO_DT` | DATS | 8 |  | Valid To Date |
| 7 | `VALID_TO_TIME` | TIMS | 6 |  | Valid To Time |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERZET` | TIMS | 6 |  | Entry time |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
