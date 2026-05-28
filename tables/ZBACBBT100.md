# ZBACBBT100
**Description:** Batch automation - Job dependency
**Total Fields:** 50
**Key Fields:** MANDT, JOBNAME

## Programs Using This Table
- `zbacbt200`
- `zbacbt300`
- `zbacbt600`
- `zbapi_check_workingday========ft`
- `zbapi_check_workingday_f_job==ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 3 | `PROGNAME` | CHAR | 40 |  | Program name |
| 4 | `ZVARIANT` | CHAR | 14 |  | Variant name |
| 5 | `MAINJOB` | CHAR | 32 |  | Background job name |
| 6 | `CHAINNO` | NUMC | 3 |  | Chain number of job in job stream |
| 7 | `DPNDSEQ` | NUMC | 3 |  | Sequence number of job in job stream |
| 8 | `JOBFREQ` | CHAR | 1 |  | Job frequency |
| 9 | `SCHEDDAY` | CHAR | 3 |  | Scheduled day of week |
| 10 | `SCHEDDATE` | DEC | 3 |  | Scheduled date in month |
| 11 | `FACTCAL` | CHAR | 2 |  | Factory Calendar |
| 12 | `DELFLAG` | CHAR | 1 |  | Job deletion flag |
| 13 | `EVENTID` | CHAR | 32 |  | Background Processing Event |
| 14 | `USERID` | CHAR | 12 |  | Background User Name for Authorization Check |
| 15 | `PDEST` | CHAR | 4 |  | Spool Output Device |
| 16 | `PRCOP` | NUMC | 3 |  | Number of Spool Copies |
| 17 | `PLIST` | CHAR | 12 |  | Spool Request |
| 18 | `PRTXT` | CHAR | 68 |  | Spool Description |
| 19 | `PRIMM` | CHAR | 1 |  | Immediate Spool Print |
| 20 | `PRREL` | CHAR | 1 |  | Immediate Spool Deletion |
| 21 | `PRNEW` | CHAR | 1 |  | New Spool Request |
| 22 | `PEXPI` | NUMC | 1 |  | Spool Retention Period |
| 23 | `LINCT` | INT4 | 10 |  | Page Length of List |
| 24 | `LINSZ` | INT4 | 10 |  | Line width of list |
| 25 | `PAART` | CHAR | 16 |  | Spool Format |
| 26 | `PRBIG` | CHAR | 1 |  | Spool Cover Sheet |
| 27 | `PRSAP` | CHAR | 1 |  | Print: SAP cover page |
| 28 | `PRREC` | CHAR | 12 |  | Spool Recipient Name |
| 29 | `PRABT` | CHAR | 12 |  | Spool Department Name |
| 30 | `PRBER` | CHAR | 12 |  | Print: Authorization |
| 31 | `PRDSN` | CHAR | 6 |  | Spool File |
| 32 | `PTYPE` | CHAR | 12 |  | Print: Type of spool request |
| 33 | `ARMOD` | CHAR | 1 |  | Print: Archiving mode |
| 34 | `FOOTL` | CHAR | 1 |  | Print: Output footer |
| 35 | `PRIOT` | NUMC | 1 |  | PRINT: Spool request priority |
| 36 | `PRUNX` | CHAR | 1 |  | PRINT: Host spool cover page |
| 37 | `SAP_OBJECT` | CHAR | 10 |  | SAP ArchiveLink: Object type of business object |
| 38 | `AR_OBJECT` | CHAR | 10 |  | Document type |
| 39 | `INFO` | CHAR | 3 |  | SAP ArchiveLink: Info field |
| 40 | `ARCTEXT` | CHAR | 40 |  | SAP ArchiveLink: Text information field |
| 41 | `L_ADR_NAME` | CHAR | 241 |  | Recipient address |
| 42 | `L_SKP` | CHAR | 1 |  | Send: Copy |
| 43 | `L_SGK` | CHAR | 1 |  | Send: Blind copy |
| 44 | `L_SEX` | CHAR | 1 |  | Send Express |
| 45 | `L_SKW` | CHAR | 1 |  | Send: No forwarding |
| 46 | `SDLSTRTTM` | TIMS | 6 |  | Planned start time for background Job |
| 47 | `LASTSTRTTM` | TIMS | 6 |  | Latest Execution Time for Background Job |
| 48 | `ZZTIMDEPEND` | CHAR | 1 |  | Time Dependency Flag |
| 49 | `PRDMINS` | NUMC | 2 |  | Duration period (in minutes) for a batch job |
| 50 | `ZZENDTIMREQ` | CHAR | 1 |  | End-Tme Required Flag |
