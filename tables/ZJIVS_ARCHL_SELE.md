# ZJIVS_ARCHL_SELE
**Description:** JiVS-Package: ArchiveLink - Selections
**Total Fields:** 8
**Key Fields:** MANDT, SELE_RUN, CONN, TOA_CLIENT, SAP_OBJECT, OBJECT_ID, ARCHIV_ID, ARC_DOC_ID

## Programs Using This Table
- `zjivs_analyse_doclinks`
- `zjivs_export_arch_link`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SELE_RUN` | CHAR | 10 | 🔑 | JiVS-Package: ArchiveLink selection session |
| 3 | `CONN` | CHAR | 5 | 🔑 | SAP ArchiveLink: Link table |
| 4 | `TOA_CLIENT` | CLNT | 3 | 🔑 | Client |
| 5 | `SAP_OBJECT` | CHAR | 10 | 🔑 | SAP ArchiveLink: Object type of business object |
| 6 | `OBJECT_ID` | CHAR | 50 | 🔑 | SAP ArchiveLink: Object ID (object identifier) |
| 7 | `ARCHIV_ID` | CHAR | 2 | 🔑 | Content Repository Identification |
| 8 | `ARC_DOC_ID` | CHAR | 40 | 🔑 | SAP ArchiveLink: Document ID |
