# ZFI_LOGGING_ALT
**Description:** Alert for UI Logging
**Total Fields:** 12
**Key Fields:** MANDT, REPORT_DATE, SYSID, USERNAME, TCODE, TCODE2, CATEGORY, VALUE, COUNTS

## Programs Using This Table
- `zisfi0308`
- `zisfi0344`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_DATE` | DATS | 8 | 🔑 | Date |
| 3 | `SYSID` | CHAR | 8 | 🔑 | ABAP System Field: Name of SAP System |
| 4 | `USERNAME` | CHAR | 12 | 🔑 | User Name |
| 5 | `TCODE` | CHAR | 20 | 🔑 | Transaction Code |
| 6 | `TCODE2` | CHAR | 20 | 🔑 | Client-Side Transaction Code |
| 7 | `CATEGORY` | CHAR | 15 | 🔑 | UI Logging Category |
| 8 | `VALUE` | CHAR | 100 | 🔑 | UI Logging value |
| 9 | `COUNTS` | INT2 | 5 | 🔑 | No. of search result |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERZET` | TIMS | 6 |  | Entry time |
| 12 | `SENT` | CHAR | 1 |  | Sent email |
