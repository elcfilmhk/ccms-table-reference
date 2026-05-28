# ZISDMEVREJSESS_S
**Description:** Reject Session (Charging Session rejected by Billing)
**Total Fields:** 15
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0132`
- `zisdm0226`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VENDOR_ID` | CHAR | 4 |  | The Vendor ID of the EV Vendor |
| 2 | `RFID_NO` | CHAR | 20 |  | The RFID of the RFID Card |
| 3 | `CHARGESTATION_ID` | CHAR | 32 |  | The ID of the charging station |
| 4 | `SEQUENCE_NO` | NUMC | 8 |  | The sequence number of the charging session |
| 5 | `START_CHRG_DATE` | DATS | 8 |  | The start date of charging session |
| 6 | `START_CHRG_TIME` | TIMS | 6 |  | The start time of charging session |
| 7 | `END_CHRG_DATE` | DATS | 8 |  | The end date of charging session |
| 8 | `END_CHRG_TIME` | TIMS | 6 |  | The end time of the charging session |
| 9 | `ERROR_CODE` | CHAR | 3 |  | The Error Code of the exception |
| 10 | `CREATION_DATE` | DATS | 8 |  | The Creation Date of the reject Session |
| 11 | `STATUS` | CHAR | 1 |  | Status of reject charging session |
| 12 | `REMARK` | CHAR | 50 |  | Remark |
| 13 | `AENAM` | CHAR | 12 |  | Last change UserID |
| 14 | `AEDAT` | DATS | 8 |  | Last change date |
| 15 | `AETIM` | TIMS | 6 |  | Last change time |
