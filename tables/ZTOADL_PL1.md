# ZTOADL_PL1
**Description:** Generated Table for View
**Total Fields:** 19
**Key Fields:** MANDANT, REPORT, REPORT_TITLE, SPRSL, INFO, LNR

## Programs Using This Table
- `zisfi0317`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDANT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT` | CHAR | 40 | 🔑 | SAP ArchiveLink Report Name |
| 3 | `REPORT_TITLE` | CHAR | 70 | 🔑 | Report title |
| 4 | `SPRSL` | LANG | 1 | 🔑 | Language Key |
| 5 | `INFO` | CHAR | 3 | 🔑 | SAP ArchiveLink: Info field |
| 6 | `LNR` | CHAR | 10 | 🔑 | SAP ArchiveLink: Sequential version number |
| 7 | `DATUM` | DATS | 8 |  | SAP ArchiveLink: Storage date |
| 8 | `DRUCKER` | CHAR | 4 |  | SAP ArchiveLink: Specify target printer |
| 9 | `FORMULAR` | CHAR | 16 |  | SAP ArchiveLink: Output format |
| 10 | `ARCHIV_ID` | CHAR | 2 |  | Content Repository Identification |
| 11 | `KURZTEXT` | CHAR | 40 |  | SAP ArchiveLink: Text information field |
| 12 | `BENUTZER` | CHAR | 12 |  | Data element for user |
| 13 | `ARC_DOC_ID` | CHAR | 40 |  | SAP ArchiveLink: Document ID |
| 14 | `SAP_OBJECT` | CHAR | 10 |  | SAP ArchiveLink: Object type of business object |
| 15 | `AR_OBJECT` | CHAR | 10 |  | Document type |
| 16 | `SIGN` | CHAR | 40 |  | SAP ArchiveLink: Reference character |
| 17 | `DEL_DATE` | DATS | 8 |  | Expiration Date |
| 18 | `DATALENGTH` | NUMC | 12 |  | Numeric field 12 |
| 19 | `AR_TIME` | TIMS | 6 |  | SAP ArchiveLink: Archiving time |
