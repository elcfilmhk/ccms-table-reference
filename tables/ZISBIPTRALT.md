# ZISBIPTRALT
**Description:** PTR Alert - List generation
**Total Fields:** 14
**Key Fields:** MANDT, BUDAT, VKONT, SEQ_NO

## Programs Using This Table
- `zisbi0163`
- `ziscs0334`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `SEQ_NO` | INT2 | 5 | 🔑 | Sequence no. for sending the alert |
| 5 | `DISPATCH` | CHAR | 1 |  | Bill delivery channel |
| 6 | `SMS` | CHAR | 50 |  | &nbsp; |
| 7 | `EMAIL` | CHAR | 100 |  | &nbsp; |
| 8 | `EBILL_SENDER` | CHAR | 100 |  | &nbsp; |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `CREATION_TIME` | TIMS | 6 |  | System Time |
| 12 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 13 | `PRINT_TIME` | TIMS | 6 |  | System Time |
| 14 | `STATUS` | CHAR | 2 |  | Blank when creation and updated when generating email report |
