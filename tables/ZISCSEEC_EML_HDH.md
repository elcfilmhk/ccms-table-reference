# ZISCSEEC_EML_HDH
**Description:** Email delivery full history
**Total Fields:** 20
**Key Fields:** MANDT, REQ_DT, REQ_PROG_NAME, GUID

## Programs Using This Table
- `ziscs0397_eec`
- `ziscs0399_eec`
- `ziscs0477_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REQ_DT` | CHAR | 14 | 🔑 | Request Email Datetime |
| 3 | `REQ_PROG_NAME` | CHAR | 40 | 🔑 | ABAP Program Name |
| 4 | `GUID` | CHAR | 32 | 🔑 | GUID in 'CHAR' Format in Uppercase |
| 5 | `PRIORITY` | INT4 | 10 |  | Natural number |
| 6 | `EML_TYPE` | CHAR | 50 |  | Email Type for Email Tracking Platform |
| 7 | `REF_NO` | CHAR | 50 |  | Email Reference number |
| 8 | `REQ_USER` | CHAR | 12 |  | User Name |
| 9 | `SENDER_NAME` | CHAR | 50 |  | Email Sender Name |
| 10 | `SENDER_EML_ADDR` | CHAR | 100 |  | Email Sender Address |
| 11 | `EML_TEMPL_OBJNAME` | CHAR | 40 |  | Object Name in Object Directory |
| 12 | `EML_TEMPL_NAME` | CHAR | 20 |  | Function of the email |
| 13 | `LANGU` | LANG | 1 |  | Language Key |
| 14 | `EML_SUBJ` | CHAR | 200 |  | Email Subject |
| 15 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 16 | `SENT_DT` | CHAR | 14 |  | Email Sent Datetime |
| 17 | `RETRY_UNTIL_DT` | CHAR | 14 |  | Email Retry until datetime |
| 18 | `PERM_ERROR_FLAG` | CHAR | 1 |  | 'X': Permanent Error; {Blank}: otherwise |
| 19 | `RET_CODE` | CHAR | 100 |  | Return Code |
| 20 | `RET_MESSAGE` | CHAR | 220 |  | Message Text |
