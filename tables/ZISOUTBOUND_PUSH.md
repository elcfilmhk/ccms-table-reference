# ZISOUTBOUND_PUSH
**Description:** Outbound Data - Push notifications
**Total Fields:** 58
**Key Fields:** MANDT, MSG_ID, VKONT, CREATION_DATE, MSG_TYPE, SUB_MSG_TYPE, COUNTER

## Programs Using This Table
- `ziscs0532`
- `ziscs0533`
- `ziscs0734`

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
| 11 | `RECIPIENT_NUMBER` | CHAR | 100 |  | Character 100 |
| 12 | `DEVICETOKEN` | CHAR | 256 |  | The push notification token of mobile device (Pass from App) |
| 13 | `DEVICETYPE` | CHAR | 1 |  | Device Type (iPhone or Android) |
| 14 | `SENDER_NUMBER` | CHAR | 50 |  | Comment |
| 15 | `EXPIRY_DATETIME` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 16 | `MSGSEND_STATUS` | CHAR | 1 |  | Communication framework - Message status |
| 17 | `MSGSEND_DATE` | DATS | 8 |  | Message Send Date |
| 18 | `MSGSEND_TIME` | TIMS | 6 |  | Message Send Time |
| 19 | `MSGRESP_DATE` | DATS | 8 |  | Message response date |
| 20 | `MSGRESP_TIME` | TIMS | 6 |  | Message response time |
| 21 | `EXTERNAL_REF` | CHAR | 32 |  | Table-Mantainence friendly UUID (Copied from SYSUUID_C) |
| 22 | `RESPONSE_INFO` | CHAR | 300 |  | Text |
| 23 | `RESPONSE_CODE` | CHAR | 20 |  | Char 20 |
| 24 | `TAGVAR_NAME1` | CHAR | 50 |  | Tag Variable Name Field |
| 25 | `TAGVAR_VALUE1` | CHAR | 100 |  | Tag Variable Value Field |
| 26 | `TAGVAR_NAME2` | CHAR | 50 |  | Tag Variable Name Field |
| 27 | `TAGVAR_VALUE2` | CHAR | 100 |  | Tag Variable Value Field |
| 28 | `TAGVAR_NAME3` | CHAR | 50 |  | Tag Variable Name Field |
| 29 | `TAGVAR_VALUE3` | CHAR | 100 |  | Tag Variable Value Field |
| 30 | `TAGVAR_NAME4` | CHAR | 50 |  | Tag Variable Name Field |
| 31 | `TAGVAR_VALUE4` | CHAR | 100 |  | Tag Variable Value Field |
| 32 | `TAGVAR_NAME5` | CHAR | 50 |  | Tag Variable Name Field |
| 33 | `TAGVAR_VALUE5` | CHAR | 100 |  | Tag Variable Value Field |
| 34 | `TAGVAR_NAME6` | CHAR | 50 |  | Tag Variable Name Field |
| 35 | `TAGVAR_VALUE6` | CHAR | 100 |  | Tag Variable Value Field |
| 36 | `TAGVAR_NAME7` | CHAR | 50 |  | Tag Variable Name Field |
| 37 | `TAGVAR_VALUE7` | CHAR | 100 |  | Tag Variable Value Field |
| 38 | `TAGVAR_NAME8` | CHAR | 50 |  | Tag Variable Name Field |
| 39 | `TAGVAR_VALUE8` | CHAR | 100 |  | Tag Variable Value Field |
| 40 | `TAGVAR_NAME9` | CHAR | 50 |  | Tag Variable Name Field |
| 41 | `TAGVAR_VALUE9` | CHAR | 100 |  | Tag Variable Value Field |
| 42 | `TAGVAR_NAME10` | CHAR | 50 |  | Tag Variable Name Field |
| 43 | `TAGVAR_VALUE10` | CHAR | 100 |  | Tag Variable Value Field |
| 44 | `TAGVAR_NAME11` | CHAR | 50 |  | Tag Variable Name Field |
| 45 | `TAGVAR_VALUE11` | CHAR | 100 |  | Tag Variable Value Field |
| 46 | `TAGVAR_NAME12` | CHAR | 50 |  | Tag Variable Name Field |
| 47 | `TAGVAR_VALUE12` | CHAR | 100 |  | Tag Variable Value Field |
| 48 | `TAGVAR_NAME13` | CHAR | 50 |  | Tag Variable Name Field |
| 49 | `TAGVAR_VALUE13` | CHAR | 100 |  | Tag Variable Value Field |
| 50 | `TAGVAR_NAME14` | CHAR | 50 |  | Tag Variable Name Field |
| 51 | `TAGVAR_VALUE14` | CHAR | 100 |  | Tag Variable Value Field |
| 52 | `TAGVAR_NAME15` | CHAR | 50 |  | Tag Variable Name Field |
| 53 | `TAGVAR_VALUE15` | CHAR | 100 |  | Tag Variable Value Field |
| 54 | `DR_REF_GUID` | CHAR | 32 |  | 16 Byte UUID in 32 Characters (Hexadecimal Encoded) |
| 55 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 56 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 57 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 58 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
