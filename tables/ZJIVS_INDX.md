# ZJIVS_INDX
**Description:** System table INDX
**Total Fields:** 9
**Key Fields:** RELID, SRTFD, SRTF2

## Programs Using This Table
- `zjivs_create_exp_filters`
- `zjivs_create_table_count`
- `zjivs_export_adk`
- `zjivs_export_adk_dispatcher`
- `zjivs_export_arch_link`
- `zjivs_export_info`
- `zjivs_export_job`
- `zjivs_export_nast_to_pdf`
- `zjivs_initial_setup`
- `zjivs_rollname`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `RELID` | CHAR | 2 | 🔑 | Region in IMPORT/EXPORT Data Table |
| 2 | `SRTFD` | CHAR | 22 | 🔑 | User-defined key in table INDX |
| 3 | `SRTF2` | INT4 | 10 | 🔑 | Natural number |
| 4 | `USERA` | CHAR | 12 |  | User Name |
| 5 | `PGMID` | CHAR | 40 |  | ABAP Program Name |
| 6 | `BEGDT` | DATS | 8 |  | (8-character) Date for SYST |
| 7 | `ENDDT` | DATS | 8 |  | (8-character) Date for SYST |
| 8 | `CLUSTR` | INT2 | 5 |  | Length field for user data in EXPORT/IMPORT tables |
| 9 | `CLUSTD` | LRAW | 2886 |  | Data field for IMPORT/EXPORT database tables |
