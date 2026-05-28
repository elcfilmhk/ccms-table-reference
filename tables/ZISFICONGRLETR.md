# ZISFICONGRLETR
**Description:** Eligible Customers for issuing Congratulation letter
**Total Fields:** 13
**Key Fields:** MANDT, PROM_ID, CONT_ACNT, CREATE_DATE

## Programs Using This Table
- `zisfi0261`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROM_ID` | CHAR | 10 | 🔑 | Promotion ID |
| 3 | `CONT_ACNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `CREATE_DATE` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 5 | `CREATE_TIME` | TIMS | 6 |  | System Time |
| 6 | `ENG_PRIZE_DESC` | CHAR | 100 |  | Prize description for congratulation letter in English |
| 7 | `CHI_PRIZE_DESC` | CHAR | 50 |  | Prize description for congratulation letter IN Chinese |
| 8 | `DISPATCH` | CHAR | 1 |  | Dispatch control |
| 9 | `EMAIL` | CHAR | 255 |  | Email Address |
| 10 | `SENDER` | CHAR | 100 |  | Sender Address |
| 11 | `CREATE_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `PRINT_DATE` | DATS | 8 |  | Print Date |
| 13 | `PRINT_TIME` | TIMS | 6 |  | System Time |
