# ZISDMPROLOG
**Description:** Profile Import Log Table
**Total Fields:** 16
**Key Fields:** MANDT, RUNID, JOBNAME, INTID

## Programs Using This Table
- `zised0013`
- `zised0014`
- `zised0058`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNID` | NUMC | 14 | 🔑 | Run ID for Profile Import Interface |
| 3 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 4 | `INTID` | NUMC | 14 | 🔑 | Internal ID for Profile Import Interface |
| 5 | `IMPORTDATE` | DATS | 8 |  | Date |
| 6 | `SERNR` | CHAR | 18 |  | Serial Number |
| 7 | `KENNZIFF` | CHAR | 15 |  | Code for Identifying a Register |
| 8 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 9 | `DATEFROM` | DATS | 8 |  | From-Date |
| 10 | `TIMEFROM` | TIMS | 6 |  | From-time |
| 11 | `UNIT` | CHAR | 3 |  | Unit of measurement of profile value in general interface |
| 12 | `DATETO` | DATS | 8 |  | To-Date |
| 13 | `TIMETO` | TIMS | 6 |  | To-Time |
| 14 | `IMPORT` | CHAR | 12 |  | Import document from-number |
| 15 | `ECODE` | CHAR | 3 |  | Error Code |
| 16 | `MSG` | CHAR | 255 |  | Application Log: Formatted message text |
