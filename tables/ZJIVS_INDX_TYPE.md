# ZJIVS_INDX_TYPE
**Description:** JiVS-Package: Implemented INDX type tables
**Total Fields:** 8
**Key Fields:** TABNAME_JIVS

## Programs Using This Table
- `zjivs_export_pclx`
- `zjivs_export_rfdt_bs`
- `zjivs_export_setdata`
- `zjivs_initial_setup`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TABNAME_JIVS` | CHAR | 30 | 🔑 | Table Name |
| 2 | `TABNAME_SAP` | CHAR | 30 |  | Table Name |
| 3 | `RELID` | CHAR | 2 |  | CHAR02 data element for SYST |
| 4 | `CLIENT_SPECIFIC` | CHAR | 1 |  | JIVS Data element for client specific mark |
| 5 | `FMT` | CHAR | 1 |  | General Flag |
| 6 | `ZIP7` | CHAR | 1 |  | General Flag |
| 7 | `ENHC_REF` | CHAR | 30 |  | Table Name |
| 8 | `GEN_STRUCT` | CHAR | 30 |  | Table Name |
