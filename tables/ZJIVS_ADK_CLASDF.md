# ZJIVS_ADK_CLASDF
**Description:** JiVS-Package: ADK-class definitions generic
**Total Fields:** 4
**Key Fields:** SAPRL, ARCH_CLASS, STRUCTURE

## Programs Using This Table
- `zjivs_analyse_archl`
- `zjivs_create_exp_filters`
- `zjivs_create_table_count`
- `zjivs_export_adk`
- `zjivs_export_arch_link`
- `zjivs_export_info`
- `zjivs_export_nast_to_pdf`
- `zjivs_rollname`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SAPRL` | CHAR | 4 | 🔑 | Release of SAP System |
| 2 | `ARCH_CLASS` | CHAR | 10 | 🔑 | Archiving class |
| 3 | `STRUCTURE` | CHAR | 30 | 🔑 | Structure of segment in archive hierarchy |
| 4 | `GEN_STRUCTURE` | CHAR | 30 |  | JIVS-Package: Structure of generic module |
