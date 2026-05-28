# ZISFI_JOBLOG
**Description:** Batch Monitoring Dashboard Data
**Total Fields:** 27
**Key Fields:** MANDT, JOBNAME, VARIANT

## Programs Using This Table
- `zisfi0317`
- `zisfi0320`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 3 | `VARIANT` | CHAR | 35 | 🔑 | Variant |
| 4 | `JOB_DESCRIPTION` | CHAR | 50 |  | Job Description |
| 5 | `JOBTYPE` | CHAR | 4 |  | Batch Job Type - API/PROG |
| 6 | `INTERFACE_ID` | CHAR | 10 |  | Unique ID for EIP |
| 7 | `FREQUENCY` | CHAR | 1 |  | Expected run frequency : D-Daily , W-Weekly , M-Monthly |
| 8 | `EXP_RUN_TIME` | TIMS | 6 |  | Expected Run Time |
| 9 | `EXP_DURATION` | TIMS | 6 |  | Expected Duration |
| 10 | `CALENDAR_ID` | CHAR | 2 |  | Calendar ID ZE/ZP/ZS : For expected run time calculation |
| 11 | `JOB_LOG` | CHAR | 1 |  | X : Display on Batch Monitoring Dashboard |
| 12 | `SPOOL_LOG` | CHAR | 1 |  | X : Display on monitoring Screen |
| 13 | `RUN_NUM` | CHAR | 1 |  | X = get run number from systems |
| 14 | `RUN_NUM_COUNT_F` | CHAR | 2 |  | Column count of run number position on the file name |
| 15 | `RUN_NUM_COUNT_T` | CHAR | 2 |  | Column count of run number position on the file name |
| 16 | `ARCHIVE_REPORT` | CHAR | 1 |  | Achive Report |
| 17 | `ARCHIVE_ID` | CHAR | 10 |  | Archive report document type |
| 18 | `REPORT_TEXT` | CHAR | 40 |  | SAP ArchiveLink: Text information field |
| 19 | `DISTRIBUTION_LIST` | CHAR | 1 |  | Distribution List |
| 20 | `OUTPUT_FILE` | CHAR | 1 |  | Output File |
| 21 | `SPOOL_KEYWORDS` | CHAR | 100 |  | Keywords separated by delimiter | |
| 22 | `JOB_LOG_KEYW` | CHAR | 100 |  | Job Log Keywords separated by delimiter | |
| 23 | `REPORT` | CHAR | 40 |  | SAP ArchiveLink Report Name |
| 24 | `FUNCT` | CHAR | 4 |  | Interface control - function name |
| 25 | `VARIANT_DATE` | CHAR | 3 |  | Variant Date |
| 26 | `BLOCKSTATUS` | CHAR | 1 |  | Channel is blocked or not |
| 27 | `SKIP_FILESENT_CHECK` | CHAR | 1 |  | Skip file sent flag (Obsolete) |
