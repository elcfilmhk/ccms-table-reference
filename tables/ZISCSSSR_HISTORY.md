# ZISCSSSR_HISTORY
**Description:** SSR Program  History
**Total Fields:** 10
**Key Fields:** MANDT, GUID

## Programs Using This Table
- `zcl_ssr_program`
- `zisdm0366`
- `zrca_ssr_cust_extract`
- `zrca_ssr_display_history`
- `zrca_ssr_extract`
- `zrca_ssr_program_upload`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GUID` | RAW | 16 | 🔑 | Generic Data Element for GUID Fields (X16) |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `PROGRAM_ID` | CHAR | 10 |  | Program ID |
| 5 | `FIELDNAME` | CHAR | 30 |  | Field Name |
| 6 | `VALUE_NEW` | CHAR | 30 |  | New contents of changed field |
| 7 | `VALUE_OLD` | CHAR | 30 |  | Old contents of changed field |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERTIM` | TIMS | 6 |  | Create time |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
