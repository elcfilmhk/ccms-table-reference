# ZJIVS_RFDT_BS_RF011F
**Description:** JiVS-Package: Output structure ZJIVS_RFDT_BS_RF011F
**Total Fields:** 7
**Key Fields:** MANDT, VERSN, LINE_NUMBER

## Programs Using This Table
- `zjivs_export_rfdt_bs`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VERSN` | CHAR | 4 | 🔑 | Financial Statement Version |
| 3 | `LINE_NUMBER` | NUMC | 15 | 🔑 | JiVS Line Number |
| 4 | `.INCLUDE` | &nbsp; | 0 |  | Financial statement item - functional area |
| 5 | `BISFB` | CHAR | 16 |  | Functional area interval upper limit |
| 6 | `VONFB` | CHAR | 16 |  | Functional area interval lower limit |
| 7 | `ERGSL` | CHAR | 10 |  | Financial Statement Item |
