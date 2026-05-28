# ZBACBCHEAD
**Description:** Conversion structure header
**Total Fields:** 28
**Key Fields:** MANDT, CONVERSION

## Programs Using This Table
- `zbacbe025`
- `zbacbe026`
- `zbacbe027`
- `zbacbe028`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONVERSION` | CHAR | 10 | 🔑 | Conversion |
| 3 | `TEXT` | CHAR | 30 |  | Description |
| 4 | `REIHE` | NUMC | 3 |  | 3-Character Integer Field |
| 5 | `BNAME` | CHAR | 12 |  | User Name in User Master Record |
| 6 | `SDLSTRTDT` | DATS | 8 |  | Planned Start Date for Background Job |
| 7 | `TODAY` | CHAR | 1 |  | Identifier: start job today |
| 8 | `SDLSTRTTM` | TIMS | 6 |  | Planned start time for background Job |
| 9 | `TOPCONVERSION` | CHAR | 10 |  | Conversion |
| 10 | `EVENTID` | CHAR | 32 |  | Background Processing Event |
| 11 | `EVENTPARM` | CHAR | 64 |  | Batch Event Parameters (for example, Jobname/Jobcount) |
| 12 | `BREAKPOINT` | CHAR | 1 |  | Breakpoint |
| 13 | `.INCLUDE` | &nbsp; | 0 |  | Conversion: Statistik structure scheduling objects |
| 14 | `DATUM` | DATS | 8 |  | Date |
| 15 | `UZEIT` | TIMS | 6 |  | Time |
| 16 | `UNAME` | CHAR | 12 |  | User Name |
| 17 | `ACTIVE` | CHAR | 1 |  | Element is active |
| 18 | `.INCLUDE` | &nbsp; | 0 |  | Conversion: Information about the running batch jobs |
| 19 | `JOBCOUNT` | CHAR | 8 |  | Job ID |
| 20 | `STRTDATA` | DATS | 8 |  | Job start date |
| 21 | `STRTTIME` | TIMS | 6 |  | Batch Job Start Time |
| 22 | `ENDDATE` | DATS | 8 |  | Job start date |
| 23 | `ENDTIME` | TIMS | 6 |  | Batch Job Start Time |
| 24 | `STATUS` | CHAR | 1 |  | State of Background Job |
| 25 | `LASTCHDATE` | DATS | 8 |  | Date of last job change |
| 26 | `LASTCHTIME` | TIMS | 6 |  | Time of last job change |
| 27 | `JOBNAMEBDC` | CHAR | 32 |  | Background job name |
| 28 | `JOBCOUNTBDC` | CHAR | 8 |  | Job ID |
