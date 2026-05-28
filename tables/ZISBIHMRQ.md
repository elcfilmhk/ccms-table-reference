# ZISBIHMRQ
**Description:** Home Move Notification Generation Request Table
**Total Fields:** 16
**Key Fields:** MANDT, BUDAT, VKONT

## Programs Using This Table
- `zisbi0125`
- `zisbi0126`
- `ziscs0274`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `TRANS_NO` | CHAR | 50 |  | Transaction no./Activity no for the MI shown |
| 5 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 6 | `EBILL_SENDER` | CHAR | 50 |  | Email sender address name |
| 7 | `EMAIL_ADDRESS` | CHAR | 50 |  | EBill email 1 |
| 8 | `SMS_NO` | CHAR | 30 |  | Mobile No |
| 9 | `DISPATCH` | CHAR | 1 |  | Bill delivery channel |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `CREATION_TIME` | TIMS | 6 |  | Creation time |
| 13 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 14 | `PRINT_TIME` | TIMS | 6 |  | Printed time |
| 15 | `STATUS` | CHAR | 1 |  | Status 'F' -Fail or 'S' - Sent or 'M' V Missing |
| 16 | `VSTELLE` | CHAR | 10 |  | Premise |
