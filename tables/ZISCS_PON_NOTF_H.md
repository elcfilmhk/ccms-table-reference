# ZISCS_PON_NOTF_H
**Description:** History of Notifications sent by PON system
**Total Fields:** 17
**Key Fields:** MANDT, IMPORT_TIME, SYS_NOTI_MSG_ID

## Programs Using This Table
- `ziscs_pon_ca_scr`
- `ziscs_pon_import_sent_hist`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `IMPORT_TIME` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 3 | `SYS_NOTI_MSG_ID` | INT4 | 10 | 🔑 | Natural number |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `EVENT_NAME` | CHAR | 30 |  | Event Name |
| 6 | `EVENT_TYPE` | CHAR | 5 |  | Event Type |
| 7 | `MSG_TYPE` | CHAR | 10 |  | Message Type |
| 8 | `CHANNEL` | CHAR | 5 |  | Contact Method |
| 9 | `RECIPIENT` | CHAR | 200 |  | Recipient email address/ SMS#/ Device ID/ etc... |
| 10 | `LANGU` | LANG | 1 |  | Language Key |
| 11 | `PON_STATUS` | CHAR | 10 |  | Status of the message on PON system |
| 12 | `PON_STATUS_TIME` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 13 | `API_CALL_RESULT` | CHAR | 10 |  | Return result of calling send message API |
| 14 | `REMARK` | CHAR | 300 |  | Information for "IGNORE" status, or if API_CALL_RESULT fails |
| 15 | `SEND_CONTENT` | STRG | 0 |  | Message Content |
| 16 | `SENT_TIME` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 17 | `NOTI_CREATE_TIME` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
