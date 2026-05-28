# ZISXXCRMACTSTAGE
**Description:** CRM Activity Staging table for Mass Process Initiatives
**Total Fields:** 26
**Key Fields:** MANDT, CREATION_DATE, VKONT, MESSAGETYPE, SUB_MESSAGE_TYPE, COUNTER

## Programs Using This Table
- `ziscrm0311`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CREATION_DATE` | DATS | 8 | 🔑 | Creation Date |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `MESSAGETYPE` | CHAR | 2 | 🔑 | Message Type |
| 5 | `SUB_MESSAGE_TYPE` | CHAR | 3 | 🔑 | Sub Message Type |
| 6 | `COUNTER` | NUMC | 5 | 🔑 | Counter |
| 7 | `STATUS` | CHAR | 1 |  | CRM Activity Creation Status |
| 8 | `CREATION_TIME` | TIMS | 6 |  | Creation time |
| 9 | `PROCESS_TYPE` | CHAR | 4 |  | CRM Process Type |
| 10 | `CODE` | CHAR | 4 |  | CRM Activity Code |
| 11 | `CATEGORY` | CHAR | 3 |  | CRM Activity Category |
| 12 | `PRIORITY` | NUMC | 1 |  | CRM Activity Priority |
| 13 | `COMPLETION` | NUMC | 3 |  | CRM Activity Completion |
| 14 | `CODE_GROUP` | CHAR | 8 |  | Code Group |
| 15 | `CREATOR` | CHAR | 12 |  | User Name |
| 16 | `DIRECTION` | CHAR | 1 |  | CRM Activity Direction |
| 17 | `LONG_TEXT_REF_GUID` | CHAR | 32 |  | 16 Byte UUID in 32 Characters (Hexadecimal Encoded) |
| 18 | `GENERIC_DATA_1` | CHAR | 100 |  | Generic Data |
| 19 | `GENERIC_DATA_2` | CHAR | 100 |  | Generic Data |
| 20 | `SOURCE_PROGRAM` | CHAR | 40 |  | ABAP Program Name |
| 21 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 22 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 23 | `ERZET` | TIMS | 6 |  | Entry time |
| 24 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 25 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 26 | `AEZET` | TIMS | 6 |  | Time last change was made |
