# ZISEMSETTINGS
**Description:** Energy Manager - General Settings
**Total Fields:** 14
**Key Fields:** MANDT

## Programs Using This Table
- `zisem_general_settings`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RFCDEST` | CHAR | 32 |  | Logical destination (specified in function call) |
| 3 | `TEMPLATEPROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 4 | `RTPCOMP` | CHAR | 10 |  | RTP component |
| 5 | `RTPCOMP_TEXT` | CHAR | 40 |  | RTP component description |
| 6 | `WDA_HOST` | CHAR | 60 |  | Energy Manager - Host name |
| 7 | `WDA_APPL` | CHAR | 10 |  | Energy Manager - Application name of WDA |
| 8 | `WDA_HANDLER` | CHAR | 30 |  | Energy Manager - WDA Handller |
| 9 | `WDA_GRAPH` | CHAR | 40 |  | Energy Manager - Graph Host |
| 10 | `DESC_FILE_EN` | RSTR | 0 |  | Energy Manager - Description Document of EA in EN |
| 11 | `DESC_FILE_ZF` | RSTR | 0 |  | Energy Manager - Description Document of EA in ZF |
| 12 | `DESC_FILETYPE` | CHAR | 3 |  | 3-Byte field |
| 13 | `LOGONPAGE` | CHAR | 60 |  | Energy Manager - Log on page |
| 14 | `CONTROL_DATE` | DATS | 8 |  | Energy Manager - Control Date for Profile value display |
