# ZFI_UILOGGING
**Description:** Convert the UI Logging from standard to this table
**Total Fields:** 20
**Key Fields:** MANDT, SYSID, GUID

## Programs Using This Table
- `zisfi0308`
- `zisfi0309`
- `zisfi0339`
- `zisfi0342`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SYSID` | CHAR | 8 | 🔑 | ABAP System Field: Name of SAP System |
| 3 | `GUID` | RAW | 16 | 🔑 | GUID for input and output data |
| 4 | `TIMESTAMP` | DEC | 15 |  | Time Stamp |
| 5 | `USERNAME` | CHAR | 12 |  | User Name |
| 6 | `TCODE` | CHAR | 20 |  | Transaction Code |
| 7 | `TCODE2` | CHAR | 20 |  | Client-Side Transaction Code |
| 8 | `TA_ID` | CHAR | 32 |  | Transaction ID in Extended Passport (EPP) |
| 9 | `ROOT_CONTEXT_ID` | CHAR | 32 |  | Root Context ID of Extended Passport (EPP) |
| 10 | `SESSION_ID` | CHAR | 40 |  | Session ID of Taskhandler |
| 11 | `PARENT_GUID` | RAW | 16 |  | Parent GUID of Temporary Logging Entry |
| 12 | `INF_GUID` | RAW | 16 |  | GUID of Temporary Logging Item |
| 13 | `CLIENT_PC` | CHAR | 46 |  | Client IP in Log |
| 14 | `HOST_NAME` | CHAR | 255 |  | Host Name in Log Record |
| 15 | `PBO` | CHAR | 1 |  | PBO Flag |
| 16 | `GUI_TITLE` | CHAR | 70 |  | Title Line |
| 17 | `SYS_NAME` | CHAR | 50 |  | UI Logging: System Name |
| 18 | `CATEGORY` | CHAR | 15 |  | UI Logging Category |
| 19 | `DATA_ELEMENT` | CHAR | 30 |  | Data element (semantic domain) |
| 20 | `VALUE` | CHAR | 100 |  | UI Logging value |
