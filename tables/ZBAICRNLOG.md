# ZBAICRNLOG
**Description:** Interface control - run logging table
**Total Fields:** 15
**Key Fields:** MANDT, SYSID, REPID, RN_COUNTER, FUNCT, EVENT

## Programs Using This Table
- `zbaicri05`
- `zbaicri06`
- `zisfi0171`
- `zisfi0171_new`
- `zisfi0253`
- `zisfi0331`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SYSID` | CHAR | 8 | 🔑 | Name of SAP System |
| 3 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 4 | `RN_COUNTER` | NUMC | 8 | 🔑 | Interface control - sequential number |
| 5 | `FUNCT` | CHAR | 4 | 🔑 | Interface control - function name |
| 6 | `EVENT` | CHAR | 4 | 🔑 | Interface control - status |
| 7 | `STATUS` | CHAR | 4 |  | Interface control - status |
| 8 | `EVENT_DATE` | DATS | 8 |  | Interface control - date |
| 9 | `REC_COUNT` | NUMC | 8 |  | Interface control - sequential number |
| 10 | `FILE_NAME` | CHAR | 255 |  | Interface control - Physical File Name |
| 11 | `SUCC_COUNTER` | NUMC | 8 |  | Interface control - sequential number |
| 12 | `EVENT_TIME` | TIMS | 6 |  | Interface control - time |
| 13 | `UNAME` | CHAR | 12 |  | User Name |
| 14 | `HEADER` | CHAR | 132 |  | Interface control - Header record |
| 15 | `TRAILER` | CHAR | 132 |  | Interface control - Trailer record |
