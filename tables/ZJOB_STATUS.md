# ZJOB_STATUS
**Description:** Job Status for Profile Value Extraction
**Total Fields:** 13
**Key Fields:** JOBNUM, JOBNAME

## Programs Using This Table
- `zedm_delta_housekeeping`
- `zedm_ext_30int_dynamic`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `JOBNUM` | CHAR | 8 | 🔑 | Job ID |
| 2 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 3 | `JOBDURATION` | INT4 | 10 |  | Job Duration |
| 4 | `JOBSTATE` | CHAR | 1 |  | Job State |
| 5 | `TSN` | DEC | 15 |  | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
| 6 | `DESCRIPTION` | CHAR | 30 |  | Job State Description |
| 7 | `FAILDESC` | CHAR | 90 |  | &nbsp; |
| 8 | `JOBDAY` | DATS | 8 |  | ABAP System Field: Current Date of Application Server |
| 9 | `PROFILE_LOW` | NUMC | 18 |  | Number of EDM Profile |
| 10 | `PROFILE_HIGH` | NUMC | 18 |  | Number of EDM Profile |
| 11 | `PERIOD_FROM` | DATS | 8 |  | ABAP System Field: Current Date of Application Server |
| 12 | `PERIOD_TO` | DATS | 8 |  | ABAP System Field: Current Date of Application Server |
| 13 | `INTSIZE` | CHAR | 4 |  | Interval Length ID |
