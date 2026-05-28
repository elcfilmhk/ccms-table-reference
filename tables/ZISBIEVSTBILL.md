# ZISBIEVSTBILL
**Description:** Custom Table for standalone Bill
**Total Fields:** 21
**Key Fields:** MANDT, OPBEL, BUDAT

## Programs Using This Table
- `zisbi0133`
- `zisbi0134`
- `zisbi0135`
- `zisbi0136`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 6 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 7 | `DUE_DATE` | DATS | 8 |  | Due Date |
| 8 | `BPAMT` | CURR | 13 |  | Brought Forward Amount |
| 9 | `TOTAL_AMNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 10 | `LASTPAYMENTON` | DATS | 8 |  | Last payment on |
| 11 | `LASTPAYMENTAMT` | CURR | 13 |  | Last payment amount |
| 12 | `NEXTBILLISSUE` | DATS | 8 |  | Next Bill issue date |
| 13 | `EZAWE` | CHAR | 1 |  | Incoming Payment Method |
| 14 | `BANKNAME` | CHAR | 60 |  | Bank name/Credit Card Name |
| 15 | `DISPATCH_CONTROL` | CHAR | 4 |  | Dispatch Control |
| 16 | `LANGU` | LANG | 1 |  | Language Key |
| 17 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 18 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 19 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 20 | `PRINT_TIME` | TIMS | 6 |  | Printed time |
| 21 | `AENAM` | CHAR | 12 |  | Printed by |
