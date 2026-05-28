# ZJIVS_ARCHL_LOG
**Description:** JiVS-Package: ArchiveLink - LOG
**Total Fields:** 21
**Key Fields:** MANDT, PRJCT, SPRJCT, TOA_CLIENT, SAP_OBJECT, CREATE_DATE, CREATE_TIME, ARCHIV_ID, ARC_DOC_ID, COMP_ID, OBJECT_ID

## Programs Using This Table
- `zjivs_export_arch_link`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PRJCT` | CHAR | 12 | 🔑 | Migration project |
| 3 | `SPRJCT` | CHAR | 12 | 🔑 | Migration sub project |
| 4 | `TOA_CLIENT` | CLNT | 3 | 🔑 | Client |
| 5 | `SAP_OBJECT` | CHAR | 10 | 🔑 | SAP ArchiveLink: Object type of business object |
| 6 | `CREATE_DATE` | DATS | 8 | 🔑 | Date of export run |
| 7 | `CREATE_TIME` | TIMS | 6 | 🔑 | Time of export run |
| 8 | `ARCHIV_ID` | CHAR | 2 | 🔑 | Content Repository Identification |
| 9 | `ARC_DOC_ID` | CHAR | 40 | 🔑 | SAP ArchiveLink: Document ID |
| 10 | `COMP_ID` | CHAR | 60 | 🔑 | Component identification for archived documents |
| 11 | `OBJECT_ID` | CHAR | 50 | 🔑 | SAP ArchiveLink: Object ID (object identifier) |
| 12 | `AR_DATE` | DATS | 8 |  | SAP ArchiveLink: Storage date |
| 13 | `DEL_DATE` | DATS | 8 |  | Expiration Date |
| 14 | `AR_OBJECT` | CHAR | 10 |  | Document type |
| 15 | `OBJECT` | CHAR | 10 |  | Archiving Object |
| 16 | `CNT_BYTES` | NUMC | 12 |  | Number of exported bytes |
| 17 | `MILLI_SEC` | DEC | 15 |  | Run time of export in milliseconds |
| 18 | `MSGTYPE` | CHAR | 1 |  | Message type: S Success, E Error, W Warning, I Info, A Abort |
| 19 | `MSGID` | CHAR | 20 |  | Message Class |
| 20 | `MSGNO` | NUMC | 3 |  | Message Number |
| 21 | `MESSAGE` | CHAR | 220 |  | Message text |
