# ZISBIPRTWB
**Description:** Table for RBI11-Group Account Result(PrintWorkbench)
**Total Fields:** 18
**Key Fields:** MANDT, UNIQUE_ID, OPBEL

## Programs Using This Table
- `zisbi0021`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `UNIQUE_ID` | NUMC | 4 | 🔑 | Unique ID |
| 3 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 4 | `PERIOD_YEAR` | NUMC | 4 |  | Year for period |
| 5 | `PERIOD_MONTH` | CHAR | 3 |  | 3 Characters to represent month |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `ZAHLKOND` | CHAR | 4 |  | Payment Condition |
| 8 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 9 | `BILLED_AMOUNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 10 | `REV_AMOUNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 11 | `AMOUNT_WAER` | CUKY | 5 |  | Transaction Currency |
| 12 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 13 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 14 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 15 | `TOT_CHILD_ACC` | INT4 | 10 |  | Total number of child accounts |
| 16 | `TOT_BILLD_ACC` | INT4 | 10 |  | Total of billed account |
| 17 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 18 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
