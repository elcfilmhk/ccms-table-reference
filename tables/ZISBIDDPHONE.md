# ZISBIDDPHONE
**Description:** Table of DD app confirm letter to be sent by email
**Total Fields:** 13
**Key Fields:** MANDT, BUDAT, VKONT, GPART, COKEY

## Programs Using This Table
- `zisbi0140`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 5 | `COKEY` | CHAR | 36 | 🔑 | Correspondence key |
| 6 | `EMAIL` | CHAR | 100 |  | Email Address |
| 7 | `EBILL_SENDER` | CHAR | 100 |  | Sender Address |
| 8 | `LANGU` | LANG | 1 |  | Language Key |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `CREATION_TIME` | TIMS | 6 |  | System Time |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 13 | `PRINT_TIME` | TIMS | 6 |  | System Time |
