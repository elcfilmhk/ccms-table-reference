# ZISCS_PYL_LTOK
**Description:** PYL Login Token
**Total Fields:** 9
**Key Fields:** MANDT, TOKEN

## Programs Using This Table
- `ziscs0369_pyl`
- `ziscs0401`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TOKEN` | CHAR | 32 | 🔑 | GUID in 'CHAR' Format in Uppercase |
| 3 | `PYL_ID` | CHAR | 10 |  | Power Your Love ID |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `VALID_TO_DT` | DATS | 8 |  | Valid To Date |
| 6 | `VALID_TO_TIME` | TIMS | 6 |  | Valid To Time |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `ERZET` | TIMS | 6 |  | Entry time |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
