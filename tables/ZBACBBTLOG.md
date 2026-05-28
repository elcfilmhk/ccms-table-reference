# ZBACBBTLOG
**Description:** Batch Job Log
**Total Fields:** 11
**Key Fields:** MANDT, JOBNAME, JOBCOUNT, BATCH_RUN_DATE, RELUNAME

## Programs Using This Table
- `zbacbt600`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 3 | `JOBCOUNT` | CHAR | 8 | 🔑 | Job ID |
| 4 | `BATCH_RUN_DATE` | DATS | 8 | 🔑 | Job start date |
| 5 | `RELUNAME` | CHAR | 12 | 🔑 | User that released scheduled batch job |
| 6 | `STATUS` | CHAR | 1 |  | State of Background Job |
| 7 | `STRTDATE` | DATS | 8 |  | Job start date |
| 8 | `STRTTIME` | TIMS | 6 |  | Batch Job Start Time |
| 9 | `ENDDATE` | DATS | 8 |  | Job start date |
| 10 | `ENDTIME` | TIMS | 6 |  | Batch Job Start Time |
| 11 | `DATAVOL` | INT4 | 10 |  | Natural number |
