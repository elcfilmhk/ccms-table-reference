# ZISCS_PYL_CHADTL
**Description:** Power Your Love Challenges Detail
**Total Fields:** 12
**Key Fields:** MANDT, CHALLENGE_ID, TASK_ID

## Programs Using This Table
- `ziscs0403`
- `ziscs0404`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CHALLENGE_ID` | CHAR | 10 | 🔑 | Challenge ID |
| 3 | `TASK_ID` | CHAR | 10 | 🔑 | Task ID Range: 1 - 99999 |
| 4 | `TASK_DESC` | CHAR | 80 |  | Task Description |
| 5 | `ONLINE_IND` | CHAR | 1 |  | Online task indicator |
| 6 | `IN_PERSON_IND` | CHAR | 1 |  | Manual task completion indicator |
| 7 | `FROM_DATE` | DATS | 8 |  | Start Date for the task |
| 8 | `FROM_TIME` | TIMS | 6 |  | Start Time for the task |
| 9 | `TO_DATE` | DATS | 8 |  | End Date for the challenge |
| 10 | `TO_TIME` | TIMS | 6 |  | End Tme for the challenge |
| 11 | `DUP_IND` | CHAR | 1 |  | Allow Duplicate indicator |
| 12 | `DRAW_DATE` | DATS | 8 |  | Lucky Draw Date |
