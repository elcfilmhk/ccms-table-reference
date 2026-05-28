# ZISFI_WF_BW
**Description:** Write Off Data for BW interface
**Total Fields:** 31
**Key Fields:** MANDT, BUKRS, ENTRY_DATE, WF_DOC, WF_ITEMNO

## Programs Using This Table
- `zisfi0287`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUKRS` | CHAR | 4 | 🔑 | Company Code |
| 3 | `ENTRY_DATE` | DATS | 8 | 🔑 | Day On Which Accounting Document Was Entered |
| 4 | `WF_DOC` | CHAR | 12 | 🔑 | Write Off Document or Reverse Write Off Document |
| 5 | `WF_ITEMNO` | NUMC | 5 | 🔑 | Unique Sequence Number for WF Document/Reverse WF Document |
| 6 | `WF_POSTING_DATE` | DATS | 8 |  | Posting Date of WF Document / Reverse WF Document |
| 7 | `OPBEL` | CHAR | 12 |  | Document Number being Write Off |
| 8 | `OPUPW` | NUMC | 3 |  | Repetition Item of Document Number being Write Off |
| 9 | `OPUPK` | NUMC | 4 |  | Item number of Document Number being Write Off |
| 10 | `OPUPZ` | NUMC | 3 |  | Subitem of Document Number being Write Off |
| 11 | `CATEGORY` | CHAR | 20 |  | Category for Write Off |
| 12 | `XBLNR` | CHAR | 16 |  | Reference Document Number |
| 13 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 14 | `FB_PRINT_DOC` | CHAR | 12 |  | Print Document of Final Bill |
| 15 | `FB_POSTING_DATE` | DATS | 8 |  | Posting Date of Final Bill |
| 16 | `ABRZU` | DATS | 8 |  | Lower Limit of Settlement Period |
| 17 | `ABRZO` | DATS | 8 |  | Upper Limit of the Billing Period |
| 18 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 19 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 20 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 21 | `BPKIND` | CHAR | 4 |  | Business Partner Type |
| 22 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 23 | `ZZTRADE_CAT` | CHAR | 2 |  | Trade category |
| 24 | `ZZTRADE_CLASS` | CHAR | 10 |  | Trade |
| 25 | `ZZPREM_FUNC` | CHAR | 3 |  | Premise function |
| 26 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 27 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 28 | `BETRH` | CURR | 13 |  | Amount In Local Currency With +/- Signs |
| 29 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 30 | `ERZET` | TIMS | 6 |  | Entry time |
| 31 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
