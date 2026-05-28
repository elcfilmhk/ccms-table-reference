# ZJIVS_DT_TAB_STATUS_S
**Description:** 
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `zjivs_export`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `STATE` | CHAR | 10 |  | JiVS-Package: State of export of one table in LOG file |
| 2 | `.INCLUDE` | &nbsp; | 0 |  | Interface ZJIVS_EXPORT_TABLES |
| 3 | `TABNAME` | CHAR | 49 |  | JiVS Dataelement for tablename |
| 4 | `TABLE_TYPE` | CHAR | 8 |  | Table Category |
| 5 | `COUNT_EXP` | DEC | 15 |  | Number of exported data records |
| 6 | `TIME_EXP` | DEC | 15 |  | Run time of export in milliseconds |
| 7 | `DURATION` | STRG | 0 |  | JiVS Dataelement for Duration Output |
| 8 | `MESSAGE` | CHAR | 220 |  | Message Text |
