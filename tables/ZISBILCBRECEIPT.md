# ZISBILCBRECEIPT
**Description:** Lockbox receipt generation
**Total Fields:** 19
**Key Fields:** MANDT, BUDAT, KEYZ1, POSZA, VKONT

## Programs Using This Table
- `zisbi0127`
- `zisbi0129`
- `zisbi0181`
- `zisfi0224`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `KEYZ1` | CHAR | 12 | 🔑 | Payment Lot |
| 4 | `POSZA` | NUMC | 6 | 🔑 | Item number in a payment lot |
| 5 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 6 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 7 | `BETRZ` | CURR | 13 |  | Payment amount in transaction currency |
| 8 | `DISPATCH` | CHAR | 1 |  | Bill delivery channel |
| 9 | `SMS` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 10 | `EMAIL` | CHAR | 100 |  | Lockbox Receipt Email |
| 11 | `EBILL_SENDER` | CHAR | 100 |  | Email sender address name |
| 12 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 13 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `CREATION_TIME` | TIMS | 6 |  | System Time |
| 15 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 16 | `PRINT_TIME` | TIMS | 6 |  | System Time |
| 17 | `STATUS` | CHAR | 1 |  | Status F -Fail or S - Sent or M V Missing |
| 18 | `PAY_METH` | CHAR | 5 |  | Payment method |
| 19 | `TARIFTYP` | CHAR | 10 |  | Rate category |
