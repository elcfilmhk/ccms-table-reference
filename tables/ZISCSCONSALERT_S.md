# ZISCSCONSALERT_S
**Description:** Consumption Alert
**Total Fields:** 17
**Key Fields:** _none_

## Programs Using This Table
- `ziscsami_get_alert============ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `ALERT_TYPE` | CHAR | 2 |  | Alert Type |
| 3 | `BLOCK_LEVEL` | INT4 | 10 |  | Block Level |
| 4 | `START_DT` | DATS | 8 |  | Start Date |
| 5 | `START_TIME` | TIMS | 6 |  | Time |
| 6 | `EXPIRE_DT` | DATS | 8 |  | Expiry Date |
| 7 | `EXPIRE_TIME` | TIMS | 6 |  | Time |
| 8 | `SUBSCRIBED` | CHAR | 1 |  | Subscribed |
| 9 | `QUANTITY` | NUMC | 10 |  | Quantity |
| 10 | `AMOUNT` | CURR | 15 |  | Amount |
| 11 | `CREATEDON` | DATS | 8 |  | Date on Which Record Was Created |
| 12 | `CREATEDTIME` | TIMS | 6 |  | Field of type TIMS |
| 13 | `CREATEDBY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `CHANGEDON` | DATS | 8 |  | Date of Last Change |
| 15 | `CHANGEDTIME` | TIMS | 6 |  | Field of type TIMS |
| 16 | `CHANGEDBY` | CHAR | 12 |  | Name of person who changed object |
| 17 | `CURRENCY` | CUKY | 5 |  | Currency Key |
