# ZISCRMACT
**Description:** CRM Activities waiting to be sent
**Total Fields:** 26
**Key Fields:** MANDT, REQ_DT, REQ_ID

## Programs Using This Table
- `ziscrmact_send================ft`
- `ziscrmact_send_job`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REQ_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 3 | `REQ_ID` | CHAR | 32 | 🔑 | GUID in 'CHAR' Format in Uppercase |
| 4 | `SEND_PRIORITY` | INT4 | 10 |  | Priority: Higher = sent first. |
| 5 | `REQ_PROG_NAME` | CHAR | 40 |  | ABAP Program Name |
| 6 | `SEND_RESULT` | CHAR | 1 |  | 'S'ent; 'F'ailed; ''attempting |
| 7 | `RETRY_UNTIL_DT` | CHAR | 14 |  | Email Retry until datetime |
| 8 | `RET_CODE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 9 | `RET_CODE` | CHAR | 100 |  | Return Code |
| 10 | `RET_MESSAGE` | CHAR | 220 |  | Message Text |
| 11 | `I_PARTNER_NO` | CHAR | 32 |  | Partner Number |
| 12 | `I_BUAG_ID` | CHAR | 12 |  | Contract Account Number |
| 13 | `I_PROCESS_TYPE` | CHAR | 4 |  | CRM Type: CRMT_PROCESS_TYPE |
| 14 | `I_CATEGORY` | CHAR | 3 |  | CRM Type: CRMT_ACTIVITY_CATEGORY |
| 15 | `I_CODE_GROUP` | CHAR | 8 |  | Code Group |
| 16 | `I_CODE` | CHAR | 4 |  | Code |
| 17 | `I_DATE_FROM` | DATS | 8 |  | Start Date |
| 18 | `I_TIME_FROM` | TIMS | 6 |  | From Time |
| 19 | `I_DATE_TO` | DATS | 8 |  | End Date |
| 20 | `I_TIME_TO` | TIMS | 6 |  | To Time |
| 21 | `I_TDLINE_1` | CHAR | 132 |  | Text Line |
| 22 | `I_TDLINE_2` | CHAR | 132 |  | Text Line |
| 23 | `I_TDLINE_3` | CHAR | 132 |  | Text Line |
| 24 | `I_TDLINE_4` | CHAR | 132 |  | Text Line |
| 25 | `E_OBJECT_ID` | CHAR | 10 |  | CRM Type: CRMT_OBJECT_ID |
| 26 | `E_GUID` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
