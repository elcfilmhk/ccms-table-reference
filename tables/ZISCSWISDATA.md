# ZISCSWISDATA
**Description:** WIS Data
**Total Fields:** 41
**Key Fields:** MANDT, AUFNR

## Programs Using This Table
- `ziscs0237`
- `zisuorder`
- `zreprjt00`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `PSTER` | DATS | 8 |  | Planned Start Date |
| 4 | `PSTUR` | TIMS | 6 |  | Planned Start Time for Task |
| 5 | `BRANCH` | CHAR | 30 |  | Branch |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 8 | `CONT_TITLE` | CHAR | 30 |  | Contact Person Title |
| 9 | `CONTACT_PERSON` | CHAR | 80 |  | Contact Person Name (English) |
| 10 | `CONTACT_PERSON_C` | CHAR | 80 |  | Contact Person Name (Chinese) |
| 11 | `CONTACT_NUMBER` | CHAR | 30 |  | Contact Phone Number 1 |
| 12 | `CONTACT_NUMBER2` | CHAR | 30 |  | Contact Phone Number 2 |
| 13 | `CONTACT_NUMBER3` | CHAR | 30 |  | Contact Phone Number 3 |
| 14 | `CONTR_YEAR` | CHAR | 4 |  | Year of construction |
| 15 | `VOLTAGE` | CHAR | 1 |  | WIS Voltage |
| 16 | `LOADING` | DEC | 9 |  | Approved Loading |
| 17 | `FLAECHE` | DEC | 9 |  | Floor Area in Square Meters |
| 18 | `SINGLE_MULTI_FL` | CHAR | 1 |  | Single/ Multi Floor |
| 19 | `DISCOUNT_RATEWR2` | INT1 | 3 |  | Discount Rate for WR2 |
| 20 | `DISCOUNT_RATE` | INT1 | 3 |  | Discount Rate |
| 21 | `WR2_SERVICE` | CHAR | 2 |  | WR2 Service |
| 22 | `SCHARGE_WIS` | DEC | 15 |  | Service Charge(WIS) |
| 23 | `SCHARGE_WR2` | DEC | 15 |  | Service Charge(WR2) |
| 24 | `NCHARGE_WIS` | DEC | 15 |  | Net Charge(WIS) |
| 25 | `NCHARGE_WR2` | DEC | 15 |  | Net Charge(WR2) |
| 26 | `TOTAL_CHARGE` | DEC | 15 |  | Total Service Charge |
| 27 | `NET_CHARGE` | DEC | 15 |  | Net Service Charge |
| 28 | `PAYMENT_TERM` | CHAR | 2 |  | Payment Term |
| 29 | `PRICING_DATE` | DATS | 8 |  | Field of type DATS |
| 30 | `PRICING_DATE_WR2` | DATS | 8 |  | Field of type DATS |
| 31 | `STATUS` | CHAR | 3 |  | WIS Status |
| 32 | `CANCEL_REASON` | CHAR | 3 |  | Cancel Reason |
| 33 | `CREATE_DATE` | DATS | 8 |  | Creation date |
| 34 | `CREATE_TIME` | TIMS | 6 |  | Creation Time |
| 35 | `CREATE_BY` | CHAR | 12 |  | Created By |
| 36 | `UPDATE_DATE` | DATS | 8 |  | Date of Last Change |
| 37 | `UPDATE_TIME` | TIMS | 6 |  | Time of Change |
| 38 | `UPDATE_BY` | CHAR | 12 |  | Last Changed By |
| 39 | `CANCEL_BY` | CHAR | 12 |  | Cancelled by |
| 40 | `CANCEL_DATE` | DATS | 8 |  | Cancel date |
| 41 | `CANCEL_TIME` | TIMS | 6 |  | Cancel time |
