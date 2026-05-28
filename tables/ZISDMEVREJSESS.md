# ZISDMEVREJSESS
**Description:** Reject Session Table (Charging Session rejected by Billing)
**Total Fields:** 16
**Key Fields:** MANDT, VENDOR_ID, RFID_NO, CHARGESTATION_ID, SEQUENCE_NO, START_CHRG_DATE, START_CHRG_TIME, END_CHRG_DATE, END_CHRG_TIME

## Programs Using This Table
- `zisdm0219`
- `zisdm0223`
- `zisdm0224`
- `zisdm0226`
- `zisdm0230`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VENDOR_ID` | CHAR | 4 | 🔑 | The Vendor ID of the EV Vendor |
| 3 | `RFID_NO` | CHAR | 20 | 🔑 | The RFID of the RFID Card |
| 4 | `CHARGESTATION_ID` | CHAR | 32 | 🔑 | The ID of the charging station |
| 5 | `SEQUENCE_NO` | NUMC | 8 | 🔑 | The sequence number of the charging session |
| 6 | `START_CHRG_DATE` | DATS | 8 | 🔑 | The start date of charging session |
| 7 | `START_CHRG_TIME` | TIMS | 6 | 🔑 | The start time of charging session |
| 8 | `END_CHRG_DATE` | DATS | 8 | 🔑 | The end date of charging session |
| 9 | `END_CHRG_TIME` | TIMS | 6 | 🔑 | The end time of the charging session |
| 10 | `ERROR_CODE` | CHAR | 3 |  | The Error Code of the exception |
| 11 | `CREATION_DATE` | DATS | 8 |  | The Creation Date of the reject Session |
| 12 | `STATUS` | CHAR | 1 |  | Status of reject charging session |
| 13 | `REMARK` | CHAR | 50 |  | Remark |
| 14 | `AENAM` | CHAR | 12 |  | Last change UserID |
| 15 | `AEDAT` | DATS | 8 |  | Last change date |
| 16 | `AETIM` | TIMS | 6 |  | Last change time |
