# ZFI_UI_CATEGORY
**Description:** Determine the Category for UI Logging (for output)
**Total Fields:** 6
**Key Fields:** MANDT, DATA_ELEMENT, SYS_NAME, SYSID, TCODE

## Programs Using This Table
- `zisfi0309`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATA_ELEMENT` | CHAR | 30 | 🔑 | Data element (semantic domain) |
| 3 | `SYS_NAME` | CHAR | 50 | 🔑 | UI Logging: System Name |
| 4 | `SYSID` | CHAR | 8 | 🔑 | ABAP System Field: Name of SAP System |
| 5 | `TCODE` | CHAR | 20 | 🔑 | ABAP System Field: Current Transaction Code |
| 6 | `CATEGORY` | CHAR | 15 |  | UI Logging Category |
