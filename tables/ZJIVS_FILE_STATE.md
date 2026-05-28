# ZJIVS_FILE_STATE
**Description:** JiVS-Package: State of LOG file
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `zjivs_export`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `FILE` | CHAR | 60 |  | JiVS package: Filename including file extension |
| 2 | `MOD_DATE` | DATS | 8 |  | Field of type DATS |
| 3 | `MOD_TIME` | TIMS | 6 |  | Field of type TIMS |
| 4 | `STATE` | CHAR | 10 |  | JiVS-Package: State of export of one table in LOG file |
