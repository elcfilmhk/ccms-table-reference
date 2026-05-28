# ZISOUTBOUND_SMS
**Description:** Outbound Data - SMS
**Total Fields:** 55
**Key Fields:** MANDT, MSG_ID, VKONT, CREATION_DATE, MSG_TYPE, SUB_MSG_TYPE, COUNTER

## Programs Using This Table
- `zisbi0158`
- `ziscs0530`
- `ziscs0533`
- `ziscs0732`
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
| 10 | `MOBILE_NO` | CHAR | 200 |  | Mobile numbers separated by ; |
| 11 | `LANG` | LANG | 1 |  | Language Key |
| 12 | `EXPIRY_DATETIME` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 13 | `MSGSEND_STATUS` | CHAR | 1 |  | Communication framework - Message status |
| 14 | `MSGSEND_DATE` | DATS | 8 |  | Message Send Date |
| 15 | `MSGSEND_TIME` | TIMS | 6 |  | Message Send Time |
| 16 | `MSGRESP_DATE` | DATS | 8 |  | Message response date |
| 17 | `MSGRESP_TIME` | TIMS | 6 |  | Message response time |
| 18 | `EXTERNAL_REF` | CHAR | 32 |  | Table-Mantainence friendly UUID (Copied from SYSUUID_C) |
| 19 | `RESPONSE_INFO` | CHAR | 300 |  | Text |
| 20 | `RESPONSE_CODE` | CHAR | 1 |  | Indicator: is consolidator logon/change/logoff OK? |
| 21 | `TAGVAR_NAME1` | CHAR | 50 |  | Tag Variable Name Field |
| 22 | `TAGVAR_VALUE1` | CHAR | 100 |  | Tag Variable Value Field |
| 23 | `TAGVAR_NAME2` | CHAR | 50 |  | Tag Variable Name Field |
| 24 | `TAGVAR_VALUE2` | CHAR | 100 |  | Tag Variable Value Field |
| 25 | `TAGVAR_NAME3` | CHAR | 50 |  | Tag Variable Name Field |
| 26 | `TAGVAR_VALUE3` | CHAR | 100 |  | Tag Variable Value Field |
| 27 | `TAGVAR_NAME4` | CHAR | 50 |  | Tag Variable Name Field |
| 28 | `TAGVAR_VALUE4` | CHAR | 100 |  | Tag Variable Value Field |
| 29 | `TAGVAR_NAME5` | CHAR | 50 |  | Tag Variable Name Field |
| 30 | `TAGVAR_VALUE5` | CHAR | 100 |  | Tag Variable Value Field |
| 31 | `TAGVAR_NAME6` | CHAR | 50 |  | Tag Variable Name Field |
| 32 | `TAGVAR_VALUE6` | CHAR | 100 |  | Tag Variable Value Field |
| 33 | `TAGVAR_NAME7` | CHAR | 50 |  | Tag Variable Name Field |
| 34 | `TAGVAR_VALUE7` | CHAR | 100 |  | Tag Variable Value Field |
| 35 | `TAGVAR_NAME8` | CHAR | 50 |  | Tag Variable Name Field |
| 36 | `TAGVAR_VALUE8` | CHAR | 100 |  | Tag Variable Value Field |
| 37 | `TAGVAR_NAME9` | CHAR | 50 |  | Tag Variable Name Field |
| 38 | `TAGVAR_VALUE9` | CHAR | 100 |  | Tag Variable Value Field |
| 39 | `TAGVAR_NAME10` | CHAR | 50 |  | Tag Variable Name Field |
| 40 | `TAGVAR_VALUE10` | CHAR | 100 |  | Tag Variable Value Field |
| 41 | `TAGVAR_NAME11` | CHAR | 50 |  | Tag Variable Name Field |
| 42 | `TAGVAR_VALUE11` | CHAR | 100 |  | Tag Variable Value Field |
| 43 | `TAGVAR_NAME12` | CHAR | 50 |  | Tag Variable Name Field |
| 44 | `TAGVAR_VALUE12` | CHAR | 100 |  | Tag Variable Value Field |
| 45 | `TAGVAR_NAME13` | CHAR | 50 |  | Tag Variable Name Field |
| 46 | `TAGVAR_VALUE13` | CHAR | 100 |  | Tag Variable Value Field |
| 47 | `TAGVAR_NAME14` | CHAR | 50 |  | Tag Variable Name Field |
| 48 | `TAGVAR_VALUE14` | CHAR | 100 |  | Tag Variable Value Field |
| 49 | `TAGVAR_NAME15` | CHAR | 50 |  | Tag Variable Name Field |
| 50 | `TAGVAR_VALUE15` | CHAR | 100 |  | Tag Variable Value Field |
| 51 | `DR_REF_GUID` | CHAR | 32 |  | 16 Byte UUID in 32 Characters (Hexadecimal Encoded) |
| 52 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 53 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 54 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 55 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
