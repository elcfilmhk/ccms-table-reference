# ZISCS_PYL_CHAREC
**Description:** Power Your Love Challenges Records
**Total Fields:** 13
**Key Fields:** MANDT, CHALLENGE_ID, TASK_ID, VKONT, TIMESTAMP

## Programs Using This Table
- `ziscs0404`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CHALLENGE_ID` | CHAR | 10 | 🔑 | Challenge ID |
| 3 | `TASK_ID` | CHAR | 10 | 🔑 | Task ID Range: 1 - 99999 |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `TIMESTAMP` | CHAR | 14 | 🔑 | Time stamp |
| 6 | `COMP_IND` | CHAR | 1 |  | Completed Flag |
| 7 | `COMPLETE_DATE` | DATS | 8 |  | Completion Date |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERZET` | TIMS | 6 |  | Entry time |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 12 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 13 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
