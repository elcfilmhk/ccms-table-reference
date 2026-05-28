# ZISBIREJCRCARD
**Description:** Rejected Credit Card Letter Outbox & History
**Total Fields:** 17
**Key Fields:** MANDT, BATCH_RUN_DATE, VKONT

## Programs Using This Table
- `zisbi0189`
- `zisbi0190`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCH_RUN_DATE` | DATS | 8 | 🔑 | Batch Run Date 1 |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `DISPATCH` | CHAR | 1 |  | Bill delivery channel |
| 5 | `EMAIL` | CHAR | 255 |  | Email Address |
| 6 | `PAYMENT_TYPE` | CHAR | 10 |  | AutoPay Payment Type |
| 7 | `CARD_NUMBER` | CHAR | 30 |  | AutoPay card Number |
| 8 | `CARDHOLDER_NAME` | CHAR | 80 |  | Card Holder Name |
| 9 | `REJECT_REASON` | CHAR | 4 |  | &nbsp; |
| 10 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 11 | `PRINT_TIME` | TIMS | 6 |  | System Time |
| 12 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 13 | `ERZET` | TIMS | 6 |  | Entry time |
| 14 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 15 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 16 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 17 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
