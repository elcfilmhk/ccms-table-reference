# ZJIVS_ARCHL_AN_E
**Description:** for Analysis of Archive Link Exports - Error Messages
**Total Fields:** 19
**Key Fields:** .INCLUDE, MANDT, PRJCT, SPRJCT, TOA_SOURCE, TOA_CLIENT, SAP_OBJECT, OBJECT_KEY, ARCHIV_ID, ARC_DOC_ID, COMP_ID

## Programs Using This Table
- `zjivs_analyse_archl`
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
| 11 | `COMP_ID` | CHAR | 60 | 🔑 | Component identification for archived documents |
| 12 | `.INCLUDE` | &nbsp; | 0 |  | For analyze exports of archive link - time stamp |
| 13 | `CREATE_DATE` | DATS | 8 |  | Date of export run |
| 14 | `CREATE_TIME` | TIMS | 6 |  | Time of export run |
| 15 | `.INCLUDE` | &nbsp; | 0 |  | Group structure for error messages |
| 16 | `MSGTYPE` | CHAR | 1 |  | Message Type |
| 17 | `MSGID` | CHAR | 20 |  | Message Class |
| 18 | `MSGNO` | NUMC | 3 |  | Message Number |
| 19 | `MESSAGE` | CHAR | 220 |  | Message Text |
