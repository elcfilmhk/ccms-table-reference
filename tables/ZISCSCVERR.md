# ZISCSCVERR
**Description:** Custom Load Program for Error Logging Purpose
**Total Fields:** 15
**Key Fields:** MANDT, START_DATE, END_DATE, START_TIME, END_TIME, SERVER, USER_ID, PROGRAM_NAME, SEQ_NO

## Programs Using This Table
- `ziscs0055`
- `ziscs0071`
- `zisdm0039`
- `zisdm0054`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `START_DATE` | DATS | 8 | 🔑 | Start Date |
| 3 | `END_DATE` | DATS | 8 | 🔑 | End Date |
| 4 | `START_TIME` | TIMS | 6 | 🔑 | Start Time |
| 5 | `END_TIME` | TIMS | 6 | 🔑 | End Time |
| 6 | `SERVER` | CHAR | 10 | 🔑 | Server |
| 7 | `USER_ID` | CHAR | 10 | 🔑 | User ID |
| 8 | `PROGRAM_NAME` | CHAR | 20 | 🔑 | Program name |
| 9 | `SEQ_NO` | NUMC | 6 | 🔑 | Sequence number |
| 10 | `FILE_NAME` | CHAR | 120 |  | Source File Name |
| 11 | `KEY_FIELD1` | CHAR | 30 |  | Key Field |
| 12 | `KEY_FIELD2` | CHAR | 30 |  | Key Field |
| 13 | `KEY_FIELD3` | CHAR | 30 |  | Key Field |
| 14 | `KEY_FIELD4` | CHAR | 30 |  | Key Field |
| 15 | `ERROR_DESCR` | CHAR | 100 |  | Error Description |
