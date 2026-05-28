# ZBACBCGRP
**Description:** Conversion structure group
**Total Fields:** 39
**Key Fields:** MANDT, CONVERSION, JOBGROUP

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
| 3 | `JOBGROUP` | CHAR | 12 | 🔑 | Summary of jobs for a group |
| 4 | `TEXT` | CHAR | 30 |  | Description |
| 5 | `REIHE` | NUMC | 3 |  | 3-Character Integer Field |
| 6 | `TOPJOBGROUP` | CHAR | 12 |  | Summary of jobs for a group |
| 7 | `EVENTID` | CHAR | 32 |  | Background Processing Event |
| 8 | `EVENTPARM` | CHAR | 64 |  | Batch Event Parameters (for example, Jobname/Jobcount) |
| 9 | `BREAKPOINT` | CHAR | 1 |  | Breakpoint |
| 10 | `.INCLUDE` | &nbsp; | 0 |  | Structure for job information |
| 11 | `BTCSYSTEM` | CHAR | 32 |  | Target System to Run Background Job |
| 12 | `PROGNAME` | CHAR | 40 |  | ABAP Program Name |
| 13 | `VARIANT1` | CHAR | 14 |  | ABAP: Name of variant (without program name) |
| 14 | `FILEINTERN` | CHAR | 60 |  | Logical file name |
| 15 | `GROUPID` | CHAR | 12 |  | Group name: Batch input session name |
| 16 | `QID` | CHAR | 20 |  | Queue Identification (Unique Key) |
| 17 | `PRDMINS` | NUMC | 2 |  | Duration period (in minutes) for a batch job |
| 18 | `USEGEN` | CHAR | 1 |  | Identifier use general data |
| 19 | `.INCLUDE` | &nbsp; | 0 |  | Conversion: Statistik structure scheduling objects |
| 20 | `DATUM` | DATS | 8 |  | Date |
| 21 | `UZEIT` | TIMS | 6 |  | Time |
| 22 | `UNAME` | CHAR | 12 |  | User Name |
| 23 | `ACTIVE` | CHAR | 1 |  | Element is active |
| 24 | `.INCLUDE` | &nbsp; | 0 |  | Conversion: Information about the running batch jobs |
| 25 | `JOBCOUNT` | CHAR | 8 |  | Job ID |
| 26 | `STRTDATA` | DATS | 8 |  | Job start date |
| 27 | `STRTTIME` | TIMS | 6 |  | Batch Job Start Time |
| 28 | `ENDDATE` | DATS | 8 |  | Job start date |
| 29 | `ENDTIME` | TIMS | 6 |  | Batch Job Start Time |
| 30 | `STATUS` | CHAR | 1 |  | State of Background Job |
| 31 | `LASTCHDATE` | DATS | 8 |  | Date of last job change |
| 32 | `LASTCHTIME` | TIMS | 6 |  | Time of last job change |
| 33 | `JOBNAMEBDC` | CHAR | 32 |  | Background job name |
| 34 | `JOBCOUNTBDC` | CHAR | 8 |  | Job ID |
| 35 | `.INCLUDE` | &nbsp; | 0 |  | Job splitting: Select structure |
| 36 | `JS_LOAD` | CHAR | 1 |  | Job splitting: SAP load balance |
| 37 | `JS_SERV` | CHAR | 1 |  | Job splitting: All server without DB |
| 38 | `JS_SERV_DB` | CHAR | 1 |  | Job splitting: All server incl. DB server |
| 39 | `JS_NAME` | CHAR | 1 |  | Job splitting: Server selected by name |
