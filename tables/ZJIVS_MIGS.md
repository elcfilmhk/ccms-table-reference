# ZJIVS_MIGS
**Description:** Selection criteria
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `zjivs_analyse_archl`
- `zjivs_archl_export_check`
- `zjivs_export`
- `zjivs_export_arch_link`
- `zjivs_export_job`
- `zjivs_export_pclx`
- `zjivs_export_rfdt_bs`
- `zjivs_export_setdata`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | Selection criteria |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `MIGOBJ` | CHAR | 15 |  | Object Name Definition |
| 4 | `TABNAME` | CHAR | 30 |  | Table Name |
| 5 | `FIELDNAME` | CHAR | 30 |  | Field Name |
| 6 | `POSNR` | NUMC | 6 |  | Actual number of parameter |
| 7 | `NOT_ONLY_PK` | CHAR | 1 |  | Use selection criteria not only for primary key fields |
| 8 | `ZSIGN` | CHAR | 1 |  | SIGN field in creation of SELECT-OPTIONS tables |
| 9 | `ZOPTION` | CHAR | 2 |  | OPTION field in structure of SELECT-OPTIONS tables |
| 10 | `LOW40` | CHAR | 40 |  | LOW Parameter (as per Range Table) |
| 11 | `HIG40` | CHAR | 40 |  | HIGH Parameter (as per Range Table) |
