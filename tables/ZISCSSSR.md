# ZISCSSSR
**Description:** SSR Program Contract Accounts
**Total Fields:** 10
**Key Fields:** MANDT, VKONT, PROGRAM_ID

## Programs Using This Table
- `zcl_ssr_program`
- `zisdm0362`
- `zisdm0364`
- `zisdm0366`
- `zisdm0369_ssr_mod`
- `zrca_ssr_cust_extract`
- `zrca_ssr_display_history`
- `zrca_ssr_program_upload`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `PROGRAM_ID` | CHAR | 10 | 🔑 | Program ID |
| 4 | `OPT_IN_DATE` | DATS | 8 |  | Opt In Date |
| 5 | `OPT_OUT_DATE` | DATS | 8 |  | Opt Out Date |
| 6 | `ENDRES` | CHAR | 2 |  | Reason for ending subscription |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 10 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
