# ZBACBBTJOB
**Description:** Submitted Batch Jobs
**Total Fields:** 6
**Key Fields:** MANDT, JOBNAME, JOBCOUNT, BATCH_RUN_DATE

## Programs Using This Table
- `zbacbt200`
- `zbacbt600`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 3 | `JOBCOUNT` | CHAR | 8 | 🔑 | Job ID |
| 4 | `BATCH_RUN_DATE` | DATS | 8 | 🔑 | Job start date |
| 5 | `RELDATE` | DATS | 8 |  | Release Date for Background Scheduling |
| 6 | `RELTIME` | TIMS | 6 |  | Release time of scheduled background job |
