# ZISBIPRINT
**Description:** Custom table to hold data for Batch Printing of Bills
**Total Fields:** 75
**Key Fields:** MANDT, COPY_TYPE, PRINTDOC, HEADER

## Programs Using This Table
- `zis_insert_statistics=========ft`
- `zisbi0002`
- `zisbi0004`
- `zisbi0089`
- `zisbi0222`
- `zisbi0232`
- `zisbi0241`
- `zprintdoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `COPY_TYPE` | CHAR | 1 | 🔑 | Copy bill status |
| 3 | `PRINTDOC` | CHAR | 12 | 🔑 | Number of print document |
| 4 | `HEADER` | CHAR | 40 | 🔑 | Header for print job |
| 5 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 6 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 7 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 8 | `SENDCONTROL` | CHAR | 4 |  | Dispatch Control |
| 9 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 13 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 14 | `DEVICEEPP` | CHAR | 8 |  | Output Type |
| 15 | `RDIEPP` | CHAR | 1 |  | Raw Data Interface |
| 16 | `FORMKEYEPP` | CHAR | 30 |  | Application form |
| 17 | `FORMKEY_RDIEPP` | CHAR | 30 |  | Alternative RDI Form |
| 18 | `FORMCLASSEPP` | CHAR | 30 |  | Form Class |
| 19 | `DELAYED_PRINTEPP` | CHAR | 1 |  | Create Print Request Instead Of Printout |
| 20 | `LANGUEPP` | LANG | 1 |  | Language indicator in the application form |
| 21 | `NO_OPEN_FORMEPP` | CHAR | 1 |  | Suppress the OPEN_FORM Module for Form Printout |
| 22 | `NO_CLOSE_FORMEPP` | CHAR | 1 |  | Do not call the module CLOSE_FORM in the form printout |
| 23 | `TEST_MODEEPP` | CHAR | 1 |  | Test Mode |
| 24 | `DEBUGEPP` | CHAR | 1 |  | Debugging mode |
| 25 | `SENDTYPEEPP` | CHAR | 10 |  | Document Transmission Method |
| 26 | `REC_ADDREPP` | CHAR | 10 |  | Address Number |
| 27 | `REC_STRINGEPP` | CHAR | 241 |  | String for Recipient Address |
| 28 | `SEND_ADDREPP` | CHAR | 10 |  | Address Number |
| 29 | `COPYFLAGEPP` | CHAR | 1 |  | Example is a Copy |
| 30 | `REC_PERSNUMBEREP` | CHAR | 10 |  | Person number |
| 31 | `LAST_DOC_ACTEPP` | CHAR | 1 |  | Create Output Request after Last Document |
| 32 | `LAST_DOCEPP` | CHAR | 1 |  | Last Document Reached |
| 33 | `OCL_ACTIVEEPP` | CHAR | 1 |  | General checkbox: X or SPACE |
| 34 | `SENDTYPE_EXTEPP` | CHAR | 4 |  | External Send Type |
| 35 | `TDPAGESLCTEPP` | CHAR | 60 |  | Pages selected for printing |
| 36 | `TDCOPIESEPP` | INT1 | 3 |  | Number of copies |
| 37 | `TDDESTEPP` | CHAR | 4 |  | Spool: Output device |
| 38 | `TDPRINTEREPP` | CHAR | 8 |  | Spool: Device type name |
| 39 | `TDPREVIEWEPP` | CHAR | 1 |  | Print preview |
| 40 | `TDNOPREVEPP` | CHAR | 1 |  | No print preview |
| 41 | `TDNOPRINTEPP` | CHAR | 1 |  | No printing from print preview |
| 42 | `TDNEWIDEPP` | CHAR | 1 |  | New Spool Request |
| 43 | `TDDATASETEPP` | CHAR | 6 |  | Spool request: Name |
| 44 | `TDSUFFIX1EPP` | CHAR | 4 |  | Spool request: Suffix 1 |
| 45 | `TDSUFFIX2EPP` | CHAR | 12 |  | Spool request: Suffix 2 |
| 46 | `TDIMMEDEPP` | CHAR | 1 |  | Immediate Spool Print |
| 47 | `TDDELETEEPP` | CHAR | 1 |  | Immediate Spool Deletion |
| 48 | `TDLIFETIMEEPP` | NUMC | 1 |  | Spool Retention Period |
| 49 | `TDSCHEDULEEPP` | CHAR | 3 |  | Send time request |
| 50 | `TDSENDDATEEPP` | DATS | 8 |  | Requested send date |
| 51 | `TDSENDTIMEEPP` | TIMS | 6 |  | Requested send time |
| 52 | `TDTELELANDEPP` | CHAR | 3 |  | Country Key |
| 53 | `TDTELENUMEPP` | CHAR | 30 |  | Telecommunications partner |
| 54 | `TDTITLEEPP` | CHAR | 50 |  | Title in dialog box |
| 55 | `TDTESTEPP` | CHAR | 1 |  | Test form |
| 56 | `TDPROGRAMEPP` | CHAR | 40 |  | Program Name |
| 57 | `TDSCRNPOSEPP` | NUMC | 15 |  | Screen display position for OTF |
| 58 | `TDCOVEREPP` | CHAR | 1 |  | Print: SAP cover page |
| 59 | `TDCOVTITLEEPP` | CHAR | 68 |  | Spool Description |
| 60 | `TDRECEIVEREPP` | CHAR | 12 |  | Spool Recipient Name |
| 61 | `TDDIVISIONEPP` | CHAR | 12 |  | Spool Department Name |
| 62 | `TDAUTORITYEPP` | CHAR | 12 |  | Print: Authorization |
| 63 | `TDARMODEPP` | CHAR | 1 |  | Print: Archiving mode |
| 64 | `TDIEXITEPP` | CHAR | 1 |  | Immediate exit after printing/faxing from print preview |
| 65 | `TDGETOTFEPP` | CHAR | 1 |  | Return of OTF table. No printing, display, or faxing |
| 66 | `TDFAXUSEREPP` | CHAR | 12 |  | SAPoffice user name |
| 67 | `TDRDIDEVEPP` | CHAR | 4 |  | Spool: Output device |
| 68 | `TDNOARMCHEPP` | CHAR | 1 |  | No changes by user in the archiving mode |
| 69 | `TDFINALEPP` | CHAR | 1 |  | Spool request completed |
| 70 | `PRINTED` | CHAR | 1 |  | Print flag |
| 71 | `GREEN_BRAILLE` | CHAR | 1 |  | Green Braille Bill |
| 72 | `SUPPRESSED` | CHAR | 1 |  | Suppressed Flag |
| 73 | `SUPPRESSED_BY` | CHAR | 12 |  | Suppressed By |
| 74 | `SUPPRESSED_DATE` | DATS | 8 |  | Suppressed Date |
| 75 | `SUPPRESSED_TIME` | TIMS | 6 |  | Suppressed Time |
