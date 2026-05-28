# ZISCSSMS1
**Description:** SMS Notification History
**Total Fields:** 15
**Key Fields:** MANDT, CREATIONDATE, CREATIONTIME, MOBILE_NO, SEQ_NO, TXNNUM, CONTRACTACCT

## Programs Using This Table
- `ziscs0301`
- `ziscs_sms02`
- `ziscssmsr1`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CREATIONDATE` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 3 | `CREATIONTIME` | TIMS | 6 | 🔑 | Time of Entry |
| 4 | `MOBILE_NO` | CHAR | 8 | 🔑 | MO Acknowledgement Request Mobile Number |
| 5 | `SEQ_NO` | NUMC | 5 | 🔑 | Item Number of Purchasing Document |
| 6 | `TXNNUM` | CHAR | 10 | 🔑 | CRM transaction no. |
| 7 | `CONTRACTACCT` | CHAR | 12 | 🔑 | Contract Account Number |
| 8 | `MOVEINDOC` | CHAR | 12 |  | Consecutive number of move-in document |
| 9 | `MOVEOUTDOC` | CHAR | 12 |  | Consecutive number of move-out document |
| 10 | `SMS_CAT` | CHAR | 2 |  | SMS Category : MI - Move-in, MO - Move-out |
| 11 | `SMSTYPE` | CHAR | 2 |  | SMSType:RE-Reminder,AC-ApplicationCompletion,FM-ForceMoveOut |
| 12 | `PARTNER_TYPE` | CHAR | 2 |  | Partner Type : BP - Business Partner, AR - Authorized Rep |
| 13 | `LANGU` | LANG | 1 |  | Language Key |
| 14 | `STATUS` | CHAR | 1 |  | Status : S-Sent, F-Failed |
| 15 | `MESSAGE` | CHAR | 100 |  | Message |
