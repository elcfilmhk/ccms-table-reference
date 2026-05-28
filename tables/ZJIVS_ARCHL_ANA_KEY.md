# ZJIVS_ARCHL_ANA_KEY
**Description:** For analyze exports of archive link - table key
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `zjivs_analyse_archl`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `PRJCT` | CHAR | 12 |  | Migration project |
| 3 | `SPRJCT` | CHAR | 12 |  | Migration sub project |
| 4 | `TOA_SOURCE` | CHAR | 5 |  | SAP ArchiveLink: Link table |
| 5 | `TOA_CLIENT` | CLNT | 3 |  | Client |
| 6 | `SAP_OBJECT` | CHAR | 10 |  | SAP ArchiveLink: Object type of business object |
| 7 | `OBJECT_KEY` | CHAR | 53 |  | SAEOBJID(53) for zJIVS_ArchL_Stat |
| 8 | `ARCHIV_ID` | CHAR | 2 |  | Content Repository Identification |
| 9 | `ARC_DOC_ID` | CHAR | 40 |  | SAP ArchiveLink: Document ID |
