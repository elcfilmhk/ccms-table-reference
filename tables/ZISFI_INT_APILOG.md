# ZISFI_INT_APILOG
**Description:** Batch Monitoring Dashboard:Payment File send/receive details
**Total Fields:** 14
**Key Fields:** MANDT, RUNID

## Programs Using This Table
- `zisfi0317`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNID` | CHAR | 25 | 🔑 | Run ID |
| 3 | `JOBNAME` | CHAR | 32 |  | Background job name |
| 4 | `TYPE` | CHAR | 4 |  | File Type |
| 5 | `VARIANT` | CHAR | 35 |  | Variant |
| 6 | `EXECUTE_ID` | CHAR | 60 |  | Execution ID for each Processing provided by EIP |
| 7 | `ACTUAL_START_DT` | DATS | 8 |  | Actual Start Date |
| 8 | `ACTUAL_START_TIM` | TIMS | 6 |  | Actual Start Time |
| 9 | `ACTUAL_END_DT` | DATS | 8 |  | Actual End Date |
| 10 | `ACTUAL_END_TIM` | TIMS | 6 |  | Actual End Time |
| 11 | `STATUS` | CHAR | 1 |  | Processing Status : Y: Success N: Failure |
| 12 | `ERROR_TXT` | CHAR | 255 |  | Error Text |
| 13 | `CHANGED_BY` | CHAR | 12 |  | User Name |
| 14 | `HEADER_TEXT` | CHAR | 200 |  | File identifier for duplication check |
