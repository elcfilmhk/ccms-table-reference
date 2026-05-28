# ZJIVS_ARCHL_STAT
**Description:** Status of JiVS objects: file folder and others
**Total Fields:** 21
**Key Fields:** MANDT, PRJCT, SPRJCT, TOA_CLIENT, SAP_OBJECT, OBJECT_ID, ARCHIV_ID, ARC_DOC_ID, COMP_ID

## Programs Using This Table
- `zjivs_analyse_archl`
- `zjivs_archl_export_check`
- `zjivs_export_arch_link`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PRJCT` | CHAR | 12 | 🔑 | Migration project |
| 3 | `SPRJCT` | CHAR | 12 | 🔑 | Migration sub project |
| 4 | `TOA_CLIENT` | CLNT | 3 | 🔑 | Client |
| 5 | `SAP_OBJECT` | CHAR | 10 | 🔑 | SAP ArchiveLink: Object type of business object |
| 6 | `OBJECT_ID` | CHAR | 53 | 🔑 | SAEOBJID(53) for zJIVS_ArchL_Stat |
| 7 | `ARCHIV_ID` | CHAR | 2 | 🔑 | Content Repository Identification |
| 8 | `ARC_DOC_ID` | CHAR | 40 | 🔑 | SAP ArchiveLink: Document ID |
| 9 | `COMP_ID` | CHAR | 60 | 🔑 | Component identification for archived documents |
| 10 | `DL_REP` | CHAR | 40 |  | SAP ArchiveLink Report Name |
| 11 | `DL_INFO` | CHAR | 3 |  | SAP ArchiveLink: Info field |
| 12 | `DL_LNR` | CHAR | 10 |  | SAP ArchiveLink: Sequential version number |
| 13 | `AR_DATE` | DATS | 8 |  | SAP ArchiveLink: Storage date |
| 14 | `AR_OBJECT` | CHAR | 10 |  | Document type |
| 15 | `DOC_FOLDER_ROOT` | CHAR | 255 |  | Text, 255 Characters |
| 16 | `DOC_FOLDER` | CHAR | 255 |  | Text, 255 Characters |
| 17 | `DOC_FILENAME` | CHAR | 255 |  | Text, 255 Characters |
| 18 | `ANZ_REC` | DEC | 15 |  | Number of exported data records |
| 19 | `QTABLE` | CHAR | 5 |  | Source table of archive records |
| 20 | `CREATEDATE` | DATS | 8 |  | Date of export run |
| 21 | `CREATETIME` | TIMS | 6 |  | Time of export run |
