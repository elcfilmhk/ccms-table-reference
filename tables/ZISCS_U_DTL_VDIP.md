# ZISCS_U_DTL_VDIP
**Description:** Log table for uploaded Vdip
**Total Fields:** 13
**Key Fields:** MANDT, LOG_ID, FILENAME, SRC_SYS, EVENT_TYPE, REC_NO

## Programs Using This Table
- `ziscs0372`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LOG_ID` | NUMC | 10 | 🔑 | Log Id |
| 3 | `FILENAME` | CHAR | 255 | 🔑 | File name |
| 4 | `SRC_SYS` | CHAR | 20 | 🔑 | Source System |
| 5 | `EVENT_TYPE` | CHAR | 20 | 🔑 | Event type of the uploaded event |
| 6 | `REC_NO` | NUMC | 10 | 🔑 | Record Number |
| 7 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 8 | `ORIGUPLDID_VDIP` | NUMC | 10 |  | Original Upload Vdip Id |
| 9 | `STATUS` | CHAR | 1 |  | Record processed status |
| 10 | `ERR_REASON` | CHAR | 1000 |  | Error Reason |
| 11 | `CREATED_BY` | CHAR | 12 |  | Created By |
| 12 | `CREATED_DATE` | DATS | 8 |  | Date on Which the Record was Created |
| 13 | `CREATED_TIME` | TIMS | 6 |  | Created At |
