# ZJIVS_INDX_PART
**Description:** JiVS-Package: Sub-Tables of implemented INDX type tables
**Total Fields:** 5
**Key Fields:** TABNAME_JIVS, NAME_PART

## Programs Using This Table
- `zjivs_create_table_count`
- `zjivs_export`
- `zjivs_export_pclx`
- `zjivs_export_rfdt_bs`
- `zjivs_export_setdata`
- `zjivs_initial_setup`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TABNAME_JIVS` | CHAR | 30 | 🔑 | Table Name |
| 2 | `NAME_PART` | CHAR | 49 | 🔑 | JiVS Dataelement for tablename |
| 3 | `TABNAME_PART` | CHAR | 49 |  | JiVS Dataelement for tablename |
| 4 | `STRUCTNAME_PART` | CHAR | 30 |  | Table Name |
| 5 | `STRUCTNAME_ENHC` | CHAR | 30 |  | Table Name |
