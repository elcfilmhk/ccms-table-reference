# ZJIVS_ARCHL_ANA
**Description:** for Analysis of Archive Link Exports [ANA]
**Total Fields:** 23
**Key Fields:** .INCLUDE, MANDT, PRJCT, SPRJCT, TOA_SOURCE, TOA_CLIENT, SAP_OBJECT, OBJECT_KEY, ARCHIV_ID, ARC_DOC_ID

## Programs Using This Table
- `zjivs_analyse_archl`
- `zjivs_archl_export_check`
- `zjivs_export_arch_link`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 | 🔑 | For analyze exports of archive link - table key |
| 2 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 3 | `PRJCT` | CHAR | 12 | 🔑 | Migration project |
| 4 | `SPRJCT` | CHAR | 12 | 🔑 | Migration sub project |
| 5 | `TOA_SOURCE` | CHAR | 5 | 🔑 | SAP ArchiveLink: Link table |
| 6 | `TOA_CLIENT` | CLNT | 3 | 🔑 | Client |
| 7 | `SAP_OBJECT` | CHAR | 10 | 🔑 | SAP ArchiveLink: Object type of business object |
| 8 | `OBJECT_KEY` | CHAR | 53 | 🔑 | SAEOBJID(53) for zJIVS_ArchL_Stat |
| 9 | `ARCHIV_ID` | CHAR | 2 | 🔑 | Content Repository Identification |
| 10 | `ARC_DOC_ID` | CHAR | 40 | 🔑 | SAP ArchiveLink: Document ID |
| 11 | `.INCLUDE` | &nbsp; | 0 |  | For analyze exports of archive link - table arguments 1 |
| 12 | `AR_OBJECT` | CHAR | 10 |  | Document type |
| 13 | `AR_DATE` | CHAR | 8 |  | SAP ArchiveLink: Archiving date |
| 14 | `COUNT_COMP` | INT4 | 10 |  | Number of exported components |
| 15 | `ERROR_FLAG` | CHAR | 1 |  | Component read/export not OK [nOK] |
| 16 | `.INCLUDE` | &nbsp; | 0 |  | For analyze exports of archive link - time stamp |
| 17 | `CREATE_DATE` | DATS | 8 |  | Date of export run |
| 18 | `CREATE_TIME` | TIMS | 6 |  | Time of export run |
| 19 | `.INCLUDE` | &nbsp; | 0 |  | Archive Link Exports - exported components |
| 20 | `EXP_COMP` | INT4 | 10 |  | Number of exported components |
| 21 | `EXP_ERROR` | CHAR | 1 |  | Component read/export not OK [nOK] |
| 22 | `EXP_DATE` | DATS | 8 |  | Date of export run |
| 23 | `EXP_TIME` | TIMS | 6 |  | Time of export run |
