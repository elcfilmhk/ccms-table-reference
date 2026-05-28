# ZWFM_S_LOGS
**Description:** Log structure without content fields
**Total Fields:** 15
**Key Fields:** _none_

## Programs Using This Table
- `zwfm_purge_message_log`
- `zwfm_show_message_log`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `COMM_GUID` | CHAR | 22 |  | Communication GUID |
| 3 | `DIRECTION` | CHAR | 1 |  | Message Direction with respect to SAP |
| 4 | `STATUS` | CHAR | 1 |  | Message Status |
| 5 | `MSG_NAME` | CHAR | 40 |  | Message Name |
| 6 | `REQ_CR_DATE` | DATS | 8 |  | Request Creation Date |
| 7 | `REQ_CR_TIME` | TIMS | 6 |  | Request Creation Time |
| 8 | `RES_CR_DATE` | DATS | 8 |  | Response Creation Date |
| 9 | `RES_CR_TIME` | TIMS | 6 |  | Response Creation Time |
| 10 | `TRANS_NAME` | CHAR | 40 |  | SAP Transaction Name |
| 11 | `CREATED_BY` | CHAR | 12 |  | User Name |
| 12 | `SEARCH1` | CHAR | 20 |  | Search Field |
| 13 | `SEARCH2` | CHAR | 20 |  | Search Field |
| 14 | `SEARCH3` | CHAR | 20 |  | Search Field |
| 15 | `SEARCH4` | CHAR | 20 |  | Search Field |
