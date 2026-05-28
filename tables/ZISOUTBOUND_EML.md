# ZISOUTBOUND_EML
**Description:** Outbound Data - Email
**Total Fields:** 57
**Key Fields:** MANDT, MSG_ID, VKONT, CREATION_DATE, MSG_TYPE, SUB_MSG_TYPE, COUNTER

## Programs Using This Table
- `ziscs0529`
- `ziscs0533`
- `ziscs0732`
- `ziscs0734`
- `ziscs_sms02`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MSG_ID` | CHAR | 15 | 🔑 | Communication Framework - Message ID |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `CREATION_DATE` | DATS | 8 | 🔑 | Date |
| 5 | `MSG_TYPE` | CHAR | 2 | 🔑 | Message Type |
| 6 | `SUB_MSG_TYPE` | CHAR | 3 | 🔑 | Sub Message Type |
| 7 | `COUNTER` | NUMC | 5 | 🔑 | Counter |
| 8 | `CREATION_TIME` | TIMS | 6 |  | Time |
| 9 | `MESSAGETEMPLATE` | CHAR | 20 |  | Template Name for Email, SMS or MPush message |
| 10 | `LANG` | LANG | 1 |  | Language Key |
| 11 | `RECEPIENT_EMAIL` | CHAR | 800 |  | Recepient emails, separated by ';' |
| 12 | `SENDER_EMAIL` | CHAR | 241 |  | E-Mail Address |
| 13 | `SENDER_NAME` | CHAR | 80 |  | Char 80 |
| 14 | `EXPIRY_DATETIME` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 15 | `MSGSEND_STATUS` | CHAR | 1 |  | Communication framework - Message status |
| 16 | `MSGSEND_DATE` | DATS | 8 |  | Message Send Date |
| 17 | `MSGSEND_TIME` | TIMS | 6 |  | Message Send Time |
| 18 | `MSGRESP_DATE` | DATS | 8 |  | Message response date |
| 19 | `MSGRESP_TIME` | TIMS | 6 |  | Message response time |
| 20 | `EXTERNAL_REF` | CHAR | 32 |  | Table-Mantainence friendly UUID (Copied from SYSUUID_C) |
| 21 | `RESPONSE_INFO` | CHAR | 300 |  | Text |
| 22 | `RESPONSE_CODE` | NUMC | 20 |  | Response code |
| 23 | `TAGVAR_NAME1` | CHAR | 50 |  | Tag Variable Name Field |
| 24 | `TAGVAR_VALUE1` | CHAR | 100 |  | Tag Variable Value Field |
| 25 | `TAGVAR_NAME2` | CHAR | 50 |  | Tag Variable Name Field |
| 26 | `TAGVAR_VALUE2` | CHAR | 100 |  | Tag Variable Value Field |
| 27 | `TAGVAR_NAME3` | CHAR | 50 |  | Tag Variable Name Field |
| 28 | `TAGVAR_VALUE3` | CHAR | 100 |  | Tag Variable Value Field |
| 29 | `TAGVAR_NAME4` | CHAR | 50 |  | Tag Variable Name Field |
| 30 | `TAGVAR_VALUE4` | CHAR | 100 |  | Tag Variable Value Field |
| 31 | `TAGVAR_NAME5` | CHAR | 50 |  | Tag Variable Name Field |
| 32 | `TAGVAR_VALUE5` | CHAR | 100 |  | Tag Variable Value Field |
| 33 | `TAGVAR_NAME6` | CHAR | 50 |  | Tag Variable Name Field |
| 34 | `TAGVAR_VALUE6` | CHAR | 100 |  | Tag Variable Value Field |
| 35 | `TAGVAR_NAME7` | CHAR | 50 |  | Tag Variable Name Field |
| 36 | `TAGVAR_VALUE7` | CHAR | 100 |  | Tag Variable Value Field |
| 37 | `TAGVAR_NAME8` | CHAR | 50 |  | Tag Variable Name Field |
| 38 | `TAGVAR_VALUE8` | CHAR | 100 |  | Tag Variable Value Field |
| 39 | `TAGVAR_NAME9` | CHAR | 50 |  | Tag Variable Name Field |
| 40 | `TAGVAR_VALUE9` | CHAR | 100 |  | Tag Variable Value Field |
| 41 | `TAGVAR_NAME10` | CHAR | 50 |  | Tag Variable Name Field |
| 42 | `TAGVAR_VALUE10` | CHAR | 100 |  | Tag Variable Value Field |
| 43 | `TAGVAR_NAME11` | CHAR | 50 |  | Tag Variable Name Field |
| 44 | `TAGVAR_VALUE11` | CHAR | 100 |  | Tag Variable Value Field |
| 45 | `TAGVAR_NAME12` | CHAR | 50 |  | Tag Variable Name Field |
| 46 | `TAGVAR_VALUE12` | CHAR | 100 |  | Tag Variable Value Field |
| 47 | `TAGVAR_NAME13` | CHAR | 50 |  | Tag Variable Name Field |
| 48 | `TAGVAR_VALUE13` | CHAR | 100 |  | Tag Variable Value Field |
| 49 | `TAGVAR_NAME14` | CHAR | 50 |  | Tag Variable Name Field |
| 50 | `TAGVAR_VALUE14` | CHAR | 100 |  | Tag Variable Value Field |
| 51 | `TAGVAR_NAME15` | CHAR | 50 |  | Tag Variable Name Field |
| 52 | `TAGVAR_VALUE15` | CHAR | 100 |  | Tag Variable Value Field |
| 53 | `DR_REF_GUID` | CHAR | 32 |  | 16 Byte UUID in 32 Characters (Hexadecimal Encoded) |
| 54 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 55 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 56 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 57 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
