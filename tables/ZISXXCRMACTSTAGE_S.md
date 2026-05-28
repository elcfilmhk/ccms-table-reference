# ZISXXCRMACTSTAGE_S
**Description:** Structure for CRM Activity Staging table
**Total Fields:** 19
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0826`
- `zisdm0357`
- `zisdm0357_backup`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CREATION_DATE` | DATS | 8 |  | Creation Date |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `MESSAGETYPE` | CHAR | 2 |  | Message Type |
| 4 | `SUB_MESSAGE_TYPE` | CHAR | 3 |  | Sub Message Type |
| 5 | `COUNTER` | NUMC | 5 |  | Counter |
| 6 | `STATUS` | CHAR | 1 |  | CRM Activity Creation Status |
| 7 | `CREATION_TIME` | TIMS | 6 |  | Creation time |
| 8 | `PROCESS_TYPE` | CHAR | 4 |  | CRM Process Type |
| 9 | `CODE` | CHAR | 4 |  | CRM Activity Codes for EEC Comm Framework |
| 10 | `CATEGORY` | CHAR | 3 |  | CRM Activity Category |
| 11 | `PRIORITY` | NUMC | 1 |  | CRM Activity Priority |
| 12 | `COMPLETION` | NUMC | 3 |  | CRM Activity Completion |
| 13 | `CODE_GROUP` | CHAR | 8 |  | Code Group |
| 14 | `CREATOR` | CHAR | 12 |  | User Name |
| 15 | `DIRECTION` | CHAR | 1 |  | CRM Activity Direction |
| 16 | `LONG_TEXT_TAB` | TTYP | 0 |  | Text Lines_T |
| 17 | `GENERIC_DATA_1` | CHAR | 100 |  | Generic Data |
| 18 | `GENERIC_DATA_2` | CHAR | 100 |  | Generic Data |
| 19 | `SOURCE_PROGRAM` | CHAR | 40 |  | ABAP Program Name |
