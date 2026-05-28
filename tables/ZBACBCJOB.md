# ZBACBCJOB
**Description:** Conversion structure job
**Total Fields:** 32
**Key Fields:** MANDT, CONVERSION, JOBGROUP, JOBNAME

## Programs Using This Table
- `zbacbe026`
- `zbacbe029`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONVERSION` | CHAR | 10 | 🔑 | Conversion |
| 3 | `JOBGROUP` | CHAR | 12 | 🔑 | Summary of jobs for a group |
| 4 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 5 | `TEXT` | CHAR | 30 |  | Description |
| 6 | `REIHE` | NUMC | 3 |  | 3-Character Integer Field |
| 7 | `TOPJOBNAME` | CHAR | 32 |  | Background job name |
| 8 | `.INCLUDE` | &nbsp; | 0 |  | Structure for job information |
| 9 | `BTCSYSTEM` | CHAR | 32 |  | Target System to Run Background Job |
| 10 | `PROGNAME` | CHAR | 40 |  | ABAP Program Name |
| 11 | `VARIANT1` | CHAR | 14 |  | ABAP: Name of variant (without program name) |
| 12 | `FILEINTERN` | CHAR | 60 |  | Logical file name |
| 13 | `GROUPID` | CHAR | 12 |  | Group name: Batch input session name |
| 14 | `QID` | CHAR | 20 |  | Queue Identification (Unique Key) |
| 15 | `PRDMINS` | NUMC | 2 |  | Duration period (in minutes) for a batch job |
| 16 | `USEGEN` | CHAR | 1 |  | Identifier use general data |
| 17 | `.INCLUDE` | &nbsp; | 0 |  | Conversion: Statistik structure scheduling objects |
| 18 | `DATUM` | DATS | 8 |  | Date |
| 19 | `UZEIT` | TIMS | 6 |  | Time |
| 20 | `UNAME` | CHAR | 12 |  | User Name |
| 21 | `ACTIVE` | CHAR | 1 |  | Element is active |
| 22 | `.INCLUDE` | &nbsp; | 0 |  | Conversion: Information about the running batch jobs |
| 23 | `JOBCOUNT` | CHAR | 8 |  | Job ID |
| 24 | `STRTDATA` | DATS | 8 |  | Job start date |
| 25 | `STRTTIME` | TIMS | 6 |  | Batch Job Start Time |
| 26 | `ENDDATE` | DATS | 8 |  | Job start date |
| 27 | `ENDTIME` | TIMS | 6 |  | Batch Job Start Time |
| 28 | `STATUS` | CHAR | 1 |  | State of Background Job |
| 29 | `LASTCHDATE` | DATS | 8 |  | Date of last job change |
| 30 | `LASTCHTIME` | TIMS | 6 |  | Time of last job change |
| 31 | `JOBNAMEBDC` | CHAR | 32 |  | Background job name |
| 32 | `JOBCOUNTBDC` | CHAR | 8 |  | Job ID |
