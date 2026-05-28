# ZISBIEFTREFUND
**Description:** Table for EFT Refund to be sent by email
**Total Fields:** 14
**Key Fields:** MANDT, BUDAT, VKONT, GPART, COTYP, COKEY

## Programs Using This Table
- `zisbi0157`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 5 | `COTYP` | CHAR | 4 | 🔑 | Correspondence Type |
| 6 | `COKEY` | CHAR | 36 | 🔑 | Correspondence key |
| 7 | `EMAIL` | CHAR | 100 |  | Email Address |
| 8 | `EBILL_SENDER` | CHAR | 100 |  | Sender Address |
| 9 | `LANGU` | LANG | 1 |  | Language Key |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `CREATION_TIME` | TIMS | 6 |  | System Time |
| 12 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 14 | `PRINT_TIME` | TIMS | 6 |  | System Time |
