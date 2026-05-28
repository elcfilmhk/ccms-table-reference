# ZISBIEVSTBILLITM
**Description:** Custom Table for standalone Bill, line items
**Total Fields:** 12
**Key Fields:** MANDT, OPBEL, BUDAT, LINE_NO

## Programs Using This Table
- `zisbi0133`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 4 | `LINE_NO` | NUMC | 2 | 🔑 | Total no. of line |
| 5 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 6 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 7 | `CONSUMPTION` | DEC | 7 |  | Consumption Unit |
| 8 | `AMOUNT` | CURR | 13 |  | Amount |
| 9 | `DUE_DATE` | DATS | 8 |  | Due Date |
| 10 | `FICA_DOC_NO` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 11 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 12 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
