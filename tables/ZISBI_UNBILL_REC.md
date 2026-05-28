# ZISBI_UNBILL_REC
**Description:** Unbilled record log
**Total Fields:** 27
**Key Fields:** MANDT, RPT_TYPE, RPT_DATE, ABRVORG, BELNR, OPBEL

## Programs Using This Table
- `zbi_unbill`
- `zisbi0042_2`
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RPT_TYPE` | CHAR | 8 | 🔑 | Unbill report type |
| 3 | `RPT_DATE` | DATS | 8 | 🔑 | Date |
| 4 | `ABRVORG` | CHAR | 2 | 🔑 | Billing Transaction |
| 5 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 6 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 7 | `OPBEL_NEW` | CHAR | 12 |  | New print document |
| 8 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 9 | `VKONTO` | CHAR | 12 |  | Contract Account Number |
| 10 | `REJ_DATE` | DATS | 8 |  | Date |
| 11 | `SYS_OS` | CHAR | 10 |  | Name of Invoicing Validation |
| 12 | `MAN_OS` | CHAR | 8 |  | Reason for manual outsorting in invoicing |
| 13 | `VERTRAG` | CHAR | 10 |  | Contract |
| 14 | `ACT_MRDATE` | DATS | 8 |  | Date |
| 15 | `ANLAGE` | CHAR | 10 |  | Installation |
| 16 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 17 | `GEMFAKT` | CHAR | 1 |  | Invoice Contracts Jointly (Mandatory Contracts) |
| 18 | `ZAHLKOND` | CHAR | 4 |  | Payment Condition |
| 19 | `ABWVK` | CHAR | 12 |  | Alternative contract account for collective bills |
| 20 | `REGIOGROUP` | CHAR | 8 |  | Regional structure grouping |
| 21 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 22 | `ERTIM` | TIMS | 6 |  | Time |
| 23 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 24 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 25 | `AETIM` | TIMS | 6 |  | Time |
| 26 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 27 | `REMARKS` | CHAR | 80 |  | Remarks |
