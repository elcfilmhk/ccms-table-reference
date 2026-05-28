# ZJIVS_ARCHL_CMPL
**Description:** for Analysis of Archive Link Exports [CMPL]
**Total Fields:** 20
**Key Fields:** .INCLUDE, MANDT, PRJCT, SPRJCT, TOA_SOURCE, TOA_CLIENT, SAP_OBJECT, OBJECT_KEY, ARCHIV_ID, ARC_DOC_ID

## Programs Using This Table
- `zjivs_archl_export_check`

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
| 11 | `STATUS` | CHAR | 1 |  | Message Type |
| 12 | `COUNT_COMP` | INT4 | 10 |  | Number of exported components |
| 13 | `ERROR_FLAG` | CHAR | 1 |  | Component read/export not OK [nOK] |
| 14 | `EXP_COMP` | INT4 | 10 |  | Number of exported components |
| 15 | `EXP_ERROR` | CHAR | 1 |  | Component read/export not OK [nOK] |
| 16 | `CMP_IN_FILE` | INT4 | 10 |  | Number of exported components |
| 17 | `FILE_ERROR` | CHAR | 1 |  | Component read/export not OK [nOK] |
| 18 | `.INCLUDE` | &nbsp; | 0 |  | For analyze exports of archive link - time stamp |
| 19 | `CREATE_DATE` | DATS | 8 |  | Date of export run |
| 20 | `CREATE_TIME` | TIMS | 6 |  | Time of export run |
