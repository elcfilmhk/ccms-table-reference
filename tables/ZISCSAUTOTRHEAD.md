# ZISCSAUTOTRHEAD
**Description:** Header table for CRM7 Transport Automation
**Total Fields:** 14
**Key Fields:** MANDT, RECORD_DATE, TRKORR

## Programs Using This Table
- `ziscs0700`
- `ziscs0703`
- `ziscs0704`
- `ziscs0705`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RECORD_DATE` | DATS | 8 | 🔑 | Created on |
| 3 | `TRKORR` | CHAR | 20 | 🔑 | Request/Task |
| 4 | `AS4TEXT` | CHAR | 60 |  | Short Description of Repository Objects |
| 5 | `IMPORT_RANGE` | CHAR | 20 |  | Import Date Range |
| 6 | `KORRDEV` | CHAR | 4 |  | Request or task category |
| 7 | `AS4USER` | CHAR | 12 |  | Owner of a Request or Task |
| 8 | `PRD_IMPORT_DATE` | DATS | 8 |  | Last Changed On |
| 9 | `PRD_IMPORT_TIME` | TIMS | 6 |  | Last changed at |
| 10 | `NEED_IMPORT` | CHAR | 1 |  | The transport need to deploy to new server? (Y/N) |
| 11 | `NEW_TRKORR` | CHAR | 20 |  | Request/Task |
| 12 | `NEW_SERVER_DATE` | DATS | 8 |  | The date of TR imported to new server |
| 13 | `NEW_SERVER_TIME` | TIMS | 6 |  | The time of TR imported to new server |
| 14 | `IMPORT_STATUS` | CHAR | 1 |  | Status of import to new server (Y/N) |
