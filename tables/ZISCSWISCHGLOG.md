# ZISCSWISCHGLOG
**Description:** WIS Data Change Log
**Total Fields:** 24
**Key Fields:** MANDT, AUFNR, UPD_SEQ

## Programs Using This Table
- `ziscs0237`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `UPD_SEQ` | NUMC | 4 | 🔑 | Update sequence number |
| 4 | `CONTR_YEAR` | CHAR | 4 |  | Year of construction |
| 5 | `VOLTAGE` | CHAR | 1 |  | WIS Voltage |
| 6 | `LOADING` | DEC | 9 |  | Approved Loading |
| 7 | `FLAECHE` | DEC | 9 |  | Floor Area in Square Meters |
| 8 | `SINGLE_MULTI_FL` | CHAR | 1 |  | Single/ Multi Floor |
| 9 | `DISCOUNT_RATE` | INT1 | 3 |  | Discount Rate |
| 10 | `DISCOUNT_RATEWR2` | INT1 | 3 |  | Discount Rate for WR2 |
| 11 | `SCHARGE_WIS` | DEC | 15 |  | Service Charge(WIS) |
| 12 | `SCHARGE_WR2` | DEC | 15 |  | Service Charge(WR2) |
| 13 | `NCHARGE_WIS` | DEC | 15 |  | Net Charge(WIS) |
| 14 | `NCHARGE_WR2` | DEC | 15 |  | Net Charge(WR2) |
| 15 | `WR2_SERVICE` | CHAR | 2 |  | WR2 Service |
| 16 | `TOTAL_CHARGE` | DEC | 15 |  | Total Service Charge |
| 17 | `NET_CHARGE` | DEC | 15 |  | Net Service Charge |
| 18 | `PAYMENT_TERM` | CHAR | 2 |  | Payment Term |
| 19 | `STATUS` | CHAR | 3 |  | WIS Status |
| 20 | `PRICING_DATE_WR2` | DATS | 8 |  | Field of type DATS |
| 21 | `PRICING_DATE` | DATS | 8 |  | Field of type DATS |
| 22 | `UPDATE_DATE` | DATS | 8 |  | Created on |
| 23 | `UPDATE_TIME` | TIMS | 6 |  | Time |
| 24 | `UPDATE_BY` | CHAR | 12 |  | Last Changed By |
