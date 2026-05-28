# ZISEM_S_SETTINGS
**Description:** Energy Manager - Attributes relevant to EM general settings
**Total Fields:** 23
**Key Fields:** _none_

## Programs Using This Table
- `zisem_general_settings`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | Energy Manager - General Settings |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `RFCDEST` | CHAR | 32 |  | Logical destination (specified in function call) |
| 4 | `TEMPLATEPROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 5 | `RTPCOMP` | CHAR | 10 |  | RTP component |
| 6 | `RTPCOMP_TEXT` | CHAR | 40 |  | RTP component description |
| 7 | `WDA_HOST` | CHAR | 60 |  | Energy Manager - Host name |
| 8 | `WDA_APPL` | CHAR | 10 |  | Energy Manager - Application name of WDA |
| 9 | `WDA_HANDLER` | CHAR | 30 |  | Energy Manager - WDA Handller |
| 10 | `WDA_GRAPH` | CHAR | 40 |  | Energy Manager - Graph Host |
| 11 | `DESC_FILE_EN` | RSTR | 0 |  | Energy Manager - Description Document of EA in EN |
| 12 | `DESC_FILE_ZF` | RSTR | 0 |  | Energy Manager - Description Document of EA in ZF |
| 13 | `DESC_FILETYPE` | CHAR | 3 |  | 3-Byte field |
| 14 | `LOGONPAGE` | CHAR | 60 |  | Energy Manager - Log on page |
| 15 | `CONTROL_DATE` | DATS | 8 |  | Energy Manager - Control Date for Profile value display |
| 16 | `PROFTYPE` | NUMC | 2 |  | Profile type |
| 17 | `PROFVALCAT` | NUMC | 2 |  | Profile value category |
| 18 | `INTSIZEID` | CHAR | 4 |  | Interval Length ID |
| 19 | `MASS` | UNIT | 3 |  | Unit of Measurement |
| 20 | `DAY_OFFSET` | TIMS | 6 |  | Day Offset |
| 21 | `TIME_ZONE` | CHAR | 6 |  | Time Zone for EDM Objects |
| 22 | `INTSIZE` | NUMC | 4 |  | Interval length |
| 23 | `INTSIZETYPE` | NUMC | 1 |  | Interval length category |
