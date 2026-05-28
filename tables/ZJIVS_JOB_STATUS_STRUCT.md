# ZJIVS_JOB_STATUS_STRUCT
**Description:** JiVS Export Job Status Structure
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `zjivs_export`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `REPORTNAME` | CHAR | 40 |  | Report Name |
| 2 | `JOBCOUNT` | CHAR | 8 |  | Job ID |
| 3 | `JOBNAME` | CHAR | 32 |  | Background job name |
| 4 | `SUB_MIGOBJ` | CHAR | 15 |  | Object Name Definition |
| 5 | `JOBSTATUS` | CHAR | 1 |  | State of Background Job |
| 6 | `DATE` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `TIME` | TIMS | 6 |  | Time when record was added |
| 8 | `ENDDATE` | DATS | 8 |  | (8-character) Date for SYST |
| 9 | `ENDTIME` | TIMS | 6 |  | Local Time |
