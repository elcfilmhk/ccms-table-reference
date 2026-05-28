# ZISCS_PYL_CHATOK
**Description:** Power Your Love Challenges Token
**Total Fields:** 10
**Key Fields:** MANDT, TOKEN

## Programs Using This Table
- `ziscs0403`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TOKEN` | CHAR | 32 | 🔑 | GUID in 'CHAR' Format in Uppercase |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `CHALLENGE_ID` | CHAR | 10 |  | Challenge ID |
| 5 | `TASK_ID` | CHAR | 10 |  | Task ID Range: 1 - 99999 |
| 6 | `VALID_TO_DT` | DATS | 8 |  | Valid To Date |
| 7 | `VALID_TO_TIME` | TIMS | 6 |  | Valid To Time |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERZET` | TIMS | 6 |  | Entry time |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
