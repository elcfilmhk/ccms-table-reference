# ZISBIAMIBILL
**Description:** Table for AMI Bill
**Total Fields:** 16
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0165`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 5 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 6 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 7 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 8 | `DISPATCH_CONTROL` | CHAR | 4 |  | Dispatch Control |
| 9 | `AMI_SAVE_AMNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 10 | `PTR_AMNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 11 | `TOTAL_AMNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 12 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 13 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `CREATION_TIME` | TIMS | 6 |  | System Time |
| 15 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 16 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
