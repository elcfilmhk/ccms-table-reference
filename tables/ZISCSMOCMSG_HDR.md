# ZISCSMOCMSG_HDR
**Description:** Managed Outbound Communication Message Header Table
**Total Fields:** 73
**Key Fields:** MANDT, VKONT, CREATION_DATE, MESSAGETYPE, SUB_MESSAGE_TYPE, DISPATCH, COUNTER

## Programs Using This Table
- `ziscrm0316`
- `ziscrm0318`
- `ziscs0711`
- `ziscs0713`
- `ziscs0726`
- `ziscs0730`
- `ziscs0807`
- `ziscs0826`
- `ziscs_pc_registration_tmp`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CREATION_DATE` | DATS | 8 | 🔑 | Creation Date |
| 4 | `MESSAGETYPE` | CHAR | 2 | 🔑 | Message Type |
| 5 | `SUB_MESSAGE_TYPE` | CHAR | 3 | 🔑 | Sub Message Type |
| 6 | `DISPATCH` | CHAR | 1 | 🔑 | Dispatch |
| 7 | `COUNTER` | NUMC | 5 | 🔑 | Counter |
| 8 | `ACTION_NAME` | CHAR | 2 |  | Action Code |
| 9 | `MESSAGETEMPLATE` | CHAR | 20 |  | Template Name for Email, SMS or MPush message |
| 10 | `LANGUAGE` | LANG | 1 |  | Language Key |
| 11 | `STATUS` | CHAR | 1 |  | Status of Record |
| 12 | `TAGVAR_NAME1` | CHAR | 50 |  | Tag Variable Name Field |
| 13 | `TAGVAR_VALUE1` | CHAR | 100 |  | Tag Variable Value Field |
| 14 | `TAGVAR_NAME2` | CHAR | 50 |  | Tag Variable Name Field |
| 15 | `TAGVAR_VALUE2` | CHAR | 100 |  | Tag Variable Value Field |
| 16 | `TAGVAR_NAME3` | CHAR | 50 |  | Tag Variable Name Field |
| 17 | `TAGVAR_VALUE3` | CHAR | 100 |  | Tag Variable Value Field |
| 18 | `TAGVAR_NAME4` | CHAR | 50 |  | Tag Variable Name Field |
| 19 | `TAGVAR_VALUE4` | CHAR | 100 |  | Tag Variable Value Field |
| 20 | `TAGVAR_NAME5` | CHAR | 50 |  | Tag Variable Name Field |
| 21 | `TAGVAR_VALUE5` | CHAR | 100 |  | Tag Variable Value Field |
| 22 | `TAGVAR_NAME6` | CHAR | 50 |  | Tag Variable Name Field |
| 23 | `TAGVAR_VALUE6` | CHAR | 100 |  | Tag Variable Value Field |
| 24 | `TAGVAR_NAME7` | CHAR | 50 |  | Tag Variable Name Field |
| 25 | `TAGVAR_VALUE7` | CHAR | 100 |  | Tag Variable Value Field |
| 26 | `TAGVAR_NAME8` | CHAR | 50 |  | Tag Variable Name Field |
| 27 | `TAGVAR_VALUE8` | CHAR | 100 |  | Tag Variable Value Field |
| 28 | `TAGVAR_NAME9` | CHAR | 50 |  | Tag Variable Name Field |
| 29 | `TAGVAR_VALUE9` | CHAR | 100 |  | Tag Variable Value Field |
| 30 | `TAGVAR_NAME10` | CHAR | 50 |  | Tag Variable Name Field |
| 31 | `TAGVAR_VALUE10` | CHAR | 100 |  | Tag Variable Value Field |
| 32 | `TAGVAR_NAME11` | CHAR | 50 |  | Tag Variable Name Field |
| 33 | `TAGVAR_VALUE11` | CHAR | 100 |  | Tag Variable Value Field |
| 34 | `TAGVAR_NAME12` | CHAR | 50 |  | Tag Variable Name Field |
| 35 | `TAGVAR_VALUE12` | CHAR | 100 |  | Tag Variable Value Field |
| 36 | `TAGVAR_NAME13` | CHAR | 50 |  | Tag Variable Name Field |
| 37 | `TAGVAR_VALUE13` | CHAR | 100 |  | Tag Variable Value Field |
| 38 | `TAGVAR_NAME14` | CHAR | 50 |  | Tag Variable Name Field |
| 39 | `TAGVAR_VALUE14` | CHAR | 100 |  | Tag Variable Value Field |
| 40 | `TAGVAR_NAME15` | CHAR | 50 |  | Tag Variable Name Field |
| 41 | `TAGVAR_VALUE15` | CHAR | 100 |  | Tag Variable Value Field |
| 42 | `TAGVAR_NAME16` | CHAR | 50 |  | Tag Variable Name Field |
| 43 | `TAGVAR_VALUE16` | CHAR | 100 |  | Tag Variable Value Field |
| 44 | `TAGVAR_NAME17` | CHAR | 50 |  | Tag Variable Name Field |
| 45 | `TAGVAR_VALUE17` | CHAR | 100 |  | Tag Variable Value Field |
| 46 | `TAGVAR_NAME18` | CHAR | 50 |  | Tag Variable Name Field |
| 47 | `TAGVAR_VALUE18` | CHAR | 100 |  | Tag Variable Value Field |
| 48 | `TAGVAR_NAME19` | CHAR | 50 |  | Tag Variable Name Field |
| 49 | `TAGVAR_VALUE19` | CHAR | 100 |  | Tag Variable Value Field |
| 50 | `TAGVAR_NAME20` | CHAR | 50 |  | Tag Variable Name Field |
| 51 | `TAGVAR_VALUE20` | CHAR | 100 |  | Tag Variable Value Field |
| 52 | `TAGVAR_NAME21` | CHAR | 50 |  | Tag Variable Name Field |
| 53 | `TAGVAR_VALUE21` | CHAR | 255 |  | Tag Value for Document Links |
| 54 | `TAGVAR_NAME22` | CHAR | 50 |  | Tag Variable Name Field |
| 55 | `TAGVAR_VALUE22` | CHAR | 255 |  | Tag Value for Document Links |
| 56 | `TAGVAR_NAME23` | CHAR | 15 |  | Tag Variable Name Field |
| 57 | `TAGVAR_VALUE23` | CHAR | 30 |  | Tag Variable Value Field |
| 58 | `TAGVAR_NAME24` | CHAR | 15 |  | Tag Variable Name Field |
| 59 | `TAGVAR_VALUE24` | CHAR | 30 |  | Tag Variable Value Field |
| 60 | `TAGVAR_NAME25` | CHAR | 15 |  | Tag Variable Name Field |
| 61 | `TAGVAR_VALUE25` | CHAR | 30 |  | Tag Variable Value Field |
| 62 | `TAGVAR_NAME26` | CHAR | 15 |  | Tag Variable Name Field |
| 63 | `TAGVAR_VALUE26` | CHAR | 30 |  | Tag Variable Value Field |
| 64 | `TAGVAR_NAME27` | CHAR | 15 |  | Tag Variable Name Field |
| 65 | `TAGVAR_VALUE27` | CHAR | 30 |  | Tag Variable Value Field |
| 66 | `TAGVAR_NAME28` | CHAR | 11 |  | Tag Variable Name Field |
| 67 | `TAGVAR_NAME29` | CHAR | 11 |  | Tag Variable Name Field |
| 68 | `TAGVAR_NAME30` | CHAR | 11 |  | Tag Variable Name Field |
| 69 | `DR_REF_GUID` | CHAR | 32 |  | 16 Byte UUID in 32 Characters (Hexadecimal Encoded) |
| 70 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 71 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 72 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 73 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
