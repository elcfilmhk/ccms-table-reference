# ZISCSCONSALERT
**Description:** Table for Consumption Alert - AMI
**Total Fields:** 21
**Key Fields:** MANDT, VKONT, ALERT_TYPE, BLOCK_LEVEL, START_DT, START_TIME

## Programs Using This Table
- `ziscs0734`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ALERT_TYPE` | CHAR | 2 | 🔑 | Alert Type |
| 4 | `BLOCK_LEVEL` | INT4 | 10 | 🔑 | Block Level |
| 5 | `START_DT` | DATS | 8 | 🔑 | Start Date |
| 6 | `START_TIME` | TIMS | 6 | 🔑 | Time |
| 7 | `EXPIRE_DT` | DATS | 8 |  | Expiry Date |
| 8 | `EXPIRE_TIME` | TIMS | 6 |  | Time |
| 9 | `SUBSCRIBED` | CHAR | 1 |  | Subscribed |
| 10 | `QUANTITY` | NUMC | 10 |  | Quantity |
| 11 | `AMOUNT` | CURR | 15 |  | Amount |
| 12 | `CREATEDON` | DATS | 8 |  | Date on Which Record Was Created |
| 13 | `CREATEDTIME` | TIMS | 6 |  | Field of type TIMS |
| 14 | `CREATEDBY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 15 | `CHANGEDON` | DATS | 8 |  | Date of Last Change |
| 16 | `CHANGEDTIME` | TIMS | 6 |  | Field of type TIMS |
| 17 | `CHANGEDBY` | CHAR | 12 |  | Name of person who changed object |
| 18 | `PERCENT` | NUMC | 3 |  | Percentage field |
| 19 | `KWH_QTY` | NUMC | 8 |  | Percentage field for KWH |
| 20 | `NEXT_CHANGE` | DATS | 8 |  | Next change date |
| 21 | `NEXT_SEND_DATE` | DATS | 8 |  | Next send date |
