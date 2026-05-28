# ZISCS_U_HDR_EVNT
**Description:** Log table for uploaded event (Header)
**Total Fields:** 13
**Key Fields:** MANDT, LOG_ID, FILENAME, SRC_SYS, EVENT_TYPE, DISPATCH, TYPE

## Programs Using This Table
- `ziscs0372`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LOG_ID` | NUMC | 10 | 🔑 | Log ID |
| 3 | `FILENAME` | CHAR | 255 | 🔑 | File name |
| 4 | `SRC_SYS` | CHAR | 20 | 🔑 | Source System |
| 5 | `EVENT_TYPE` | CHAR | 20 | 🔑 | Event type of the uploaded event |
| 6 | `DISPATCH` | CHAR | 1 | 🔑 | Dispatch |
| 7 | `TYPE` | CHAR | 1 | 🔑 | Type of eService |
| 8 | `NO_OF_REC` | INT4 | 10 |  | No of records in a file |
| 9 | `STATUS` | CHAR | 1 |  | Processed Status |
| 10 | `ERR_REASON` | CHAR | 255 |  | Error Description |
| 11 | `CREATED_BY` | CHAR | 12 |  | Created By |
| 12 | `CREATED_DATE` | DATS | 8 |  | Date on Which the Record was Created |
| 13 | `CREATED_TIME` | TIMS | 6 |  | Created At |
