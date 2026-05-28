# ZJIVS_MIGO
**Description:** Object definition
**Total Fields:** 18
**Key Fields:** MANDT, MIGOBJ, SAPRL

## Programs Using This Table
- `zjivs_export`
- `zjivs_export_job`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MIGOBJ` | CHAR | 15 | 🔑 | Object Name Definition |
| 3 | `POSNR` | NUMC | 6 |  | Actual number of parameter |
| 4 | `SAPRL` | CHAR | 4 | 🔑 | SAP Release |
| 5 | `KTEXT` | CHAR | 30 |  | Short text |
| 6 | `EXPORT` | CHAR | 1 |  | Indicator if Actual Delivery Date was After Expected Date |
| 7 | `IMPORT` | CHAR | 1 |  | Indicator if Actual Delivery Date was After Expected Date |
| 8 | `MIGVERF` | CHAR | 1 |  | Function for Generating Postings |
| 9 | `EXPDYN` | CHAR | 1 |  | Indicator if Actual Delivery Date was After Expected Date |
| 10 | `EXPREPORT` | CHAR | 40 |  | ABAP Program Name |
| 11 | `IMPDYN` | CHAR | 1 |  | Indicator if Actual Delivery Date was After Expected Date |
| 12 | `PROJECT` | CHAR | 15 |  | Project |
| 13 | `SUBPROJ` | CHAR | 15 |  | Subproject |
| 14 | `OBJECT` | CHAR | 15 |  | Object |
| 15 | `ENTID` | CHAR | 26 |  | Entity type name |
| 16 | `ANLEGEN` | CHAR | 1 |  | Create migration object |
| 17 | `AENDERN` | CHAR | 1 |  | Change migration object |
| 18 | `LOESCHEN` | CHAR | 1 |  | Delete migration object |
