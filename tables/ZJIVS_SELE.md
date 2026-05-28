# ZJIVS_SELE
**Description:** Selection criteria
**Total Fields:** 10
**Key Fields:** MANDT, MIGOBJ, TABNAME, FIELDNAME, POSNR

## Programs Using This Table
- `zjivs_export`
- `zjivs_set_export_selections`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MIGOBJ` | CHAR | 15 | 🔑 | Object Name Definition |
| 3 | `TABNAME` | CHAR | 30 | 🔑 | Table Name |
| 4 | `FIELDNAME` | CHAR | 30 | 🔑 | Field Name |
| 5 | `POSNR` | NUMC | 6 | 🔑 | Actual number of parameter |
| 6 | `NOT_ONLY_PK` | CHAR | 1 |  | Use selection criteria not only for primary key fields |
| 7 | `ZSIGN` | CHAR | 1 |  | SIGN field in creation of SELECT-OPTIONS tables |
| 8 | `ZOPTION` | CHAR | 2 |  | OPTION field in structure of SELECT-OPTIONS tables |
| 9 | `LOW40` | CHAR | 40 |  | LOW Parameter (as per Range Table) |
| 10 | `HIG40` | CHAR | 40 |  | HIGH Parameter (as per Range Table) |
