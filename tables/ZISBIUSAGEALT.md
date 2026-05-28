# ZISBIUSAGEALT
**Description:** Table For Maintaining Batch Alerts Updates
**Total Fields:** 28
**Key Fields:** MANDT, BUDAT, VKONT, SEQ_NO

## Programs Using This Table
- `zisbi0163`
- `zisdm0278`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `SEQ_NO` | INT2 | 5 | 🔑 | Sequence Number |
| 5 | `EMAIL` | CHAR | 50 |  | Correspondence email |
| 6 | `SMS` | CHAR | 255 |  | SMS |
| 7 | `DISPATCH` | CHAR | 1 |  | Bill delivery channel |
| 8 | `EBILL_SENDER` | CHAR | 100 |  | Sender Of Email |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `CREATION_TIME` | TIMS | 6 |  | Creation Time |
| 12 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 13 | `PRINT_TIME` | TIMS | 6 |  | System Time |
| 14 | `STATUS` | CHAR | 1 |  | Status |
| 15 | `ALERT_SAMEPERIOD` | CHAR | 1 |  | Usage exceeds the bill of same period in the last year |
| 16 | `ALERT_95PERCENT` | CHAR | 1 |  | Usage reaches the level of 95% of my last bill |
| 17 | `ALERT_400` | CHAR | 1 |  | Usage exceeds 400kWh |
| 18 | `ALERT_1000` | CHAR | 1 |  | Usage exceeds 1000kWh |
| 19 | `ALERT_1800` | CHAR | 1 |  | Usage exceeds 1800kWh |
| 20 | `ALERT_2600` | CHAR | 1 |  | Usage exceeds 2600kWh |
| 21 | `USAGE_CSMP` | DEC | 31 |  | Usage Consumption |
| 22 | `BILL_CONSUMPTION` | DEC | 31 |  | Last year billing document billed consumption |
| 23 | `BILLING_DATE` | DATS | 8 |  | Last year billing document reading date |
| 24 | `DATEFROM` | DATS | 8 |  | From-Date |
| 25 | `DATETO` | DATS | 8 |  | To-Date |
| 26 | `ALERT_50PERCENT` | CHAR | 1 |  | Usage reaches 50% of my last bill |
| 27 | `ALERT_80PERCENT` | CHAR | 1 |  | Usage reaches 80% of my last bill |
| 28 | `ALERT_HALF_WAY` | CHAR | 1 |  | Number of days reaches half way through |
