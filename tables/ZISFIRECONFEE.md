# ZISFIRECONFEE
**Description:** Daily Reconnection Charges Reports
**Total Fields:** 11
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisfi0243_d`
- `zisfi0243_m`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 5 | `AUFNR` | CHAR | 12 |  | Order Number |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `BETRW` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 9 | `EXCEPTION_IND` | CHAR | 1 |  | Exception indicator |
| 10 | `CLEARED_REASON` | CHAR | 1 |  | Cleared reason |
| 11 | `REVERSED_ON` | DATS | 8 |  | Reversed on |
