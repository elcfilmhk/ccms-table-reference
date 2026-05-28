# ZJIVS_PARA
**Description:** JIVS parameter - R/3 Protocol
**Total Fields:** 8
**Key Fields:** MANDT, MIGOBJ, VAR_NAME

## Programs Using This Table
- `zcl_jivs_project_util`
- `zjivs_analyse_archl`
- `zjivs_archl_export_check`
- `zjivs_export`
- `zjivs_export_arch_link`
- `zjivs_export_job`
- `zjivs_initial_setup`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MIGOBJ` | CHAR | 15 | 🔑 | Object Name Definition |
| 3 | `VAR_NAME` | CHAR | 60 | 🔑 | Parameter name |
| 4 | `VAR_VALUE` | CHAR | 50 |  | Parameter value |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERZEI` | TIMS | 6 |  | Time when record was added |
| 8 | `JDT_STATUS` | CHAR | 1 |  | General Flag |
