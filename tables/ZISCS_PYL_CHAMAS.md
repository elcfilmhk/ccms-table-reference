# ZISCS_PYL_CHAMAS
**Description:** Power Your Love Challenges Master
**Total Fields:** 9
**Key Fields:** MANDT, CHALLENGE_ID

## Programs Using This Table
- `ziscs0403`
- `ziscs0404`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CHALLENGE_ID` | CHAR | 10 | 🔑 | Challenge ID |
| 3 | `CHALLENGE_DESC` | CHAR | 80 |  | Challenge Description |
| 4 | `MIN_TASK` | NUMC | 2 |  | Minimum Sub-Tasks completed to proceed further action |
| 5 | `FROM_DATE` | DATS | 8 |  | Start Date |
| 6 | `START_DATE` | DATS | 8 |  | End Date |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `ERZET` | TIMS | 6 |  | Entry time |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
