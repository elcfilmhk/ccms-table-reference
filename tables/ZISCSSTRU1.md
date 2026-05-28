# ZISCSSTRU1
**Description:** Structure sms detail report
**Total Fields:** 25
**Key Fields:** _none_

## Programs Using This Table
- `ziscssmsr1`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CREATIONDATE` | DATS | 8 |  | Date on Which Record Was Created |
| 2 | `CREATIONTIME` | TIMS | 6 |  | Time of Entry |
| 3 | `MOBILE_NO` | CHAR | 8 |  | MO Acknowledgement Request Mobile Number |
| 4 | `SEQ_NO` | NUMC | 5 |  | Item Number of Purchasing Document |
| 5 | `TXNNUM` | CHAR | 10 |  | CRM transaction no. |
| 6 | `CONTRACTACCT` | CHAR | 12 |  | Contract Account Number |
| 7 | `MOVEINDOC` | CHAR | 12 |  | Consecutive number of move-in document |
| 8 | `MOVEOUTDOC` | CHAR | 12 |  | Consecutive number of move-out document |
| 9 | `SMS_CAT` | CHAR | 2 |  | SMS Category : MI - Move-in, MO - Move-out |
| 10 | `SMS_CAT_T` | CHAR | 60 |  | Short Text for Fixed Values |
| 11 | `APP_TYPE` | CHAR | 1 |  | Application Type (Applicant - 'T' / Authorized Rep - 'A') |
| 12 | `APP_TYPE_T` | CHAR | 60 |  | Short Text for Fixed Values |
| 13 | `SMSTYPE` | CHAR | 2 |  | SMSType:RE-Reminder,AC-ApplicationCompletion,FM-ForceMoveOut |
| 14 | `SMSTYPE_T` | CHAR | 60 |  | Short Text for Fixed Values |
| 15 | `PARTNER_TYPE` | CHAR | 1 |  | Application Type (Applicant - 'T' / Authorized Rep - 'A') |
| 16 | `PARTNER_TYPE_T` | CHAR | 60 |  | Short Text for Fixed Values |
| 17 | `LANGU_T` | CHAR | 60 |  | Short Text for Fixed Values |
| 18 | `LANGU` | LANG | 1 |  | Language Key |
| 19 | `STATUS` | CHAR | 1 |  | Status : S-Sent, F-Failed |
| 20 | `STATUS_T` | CHAR | 60 |  | Short Text for Fixed Values |
| 21 | `VSTELLE` | CHAR | 10 |  | Premise |
| 22 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 23 | `ACCTHOLDERNAME1` | CHAR | 80 |  | Autopay account holder 1 name |
| 24 | `AR_NAME` | CHAR | 80 |  | Agent name |
| 25 | `MESSAGE` | CHAR | 100 |  | Message |
