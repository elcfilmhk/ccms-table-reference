# ZISBIEVBILLSUMM
**Description:** EV Bill Summary
**Total Fields:** 22
**Key Fields:** MANDT, VKONT, VENDOR_ID, RFID_NO, EV_BILL_DATE, EV_PRICE_KEY, SEQ_NO, BILL_START, BILL_END

## Programs Using This Table
- `zisbi0132`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract account |
| 3 | `VENDOR_ID` | CHAR | 4 | 🔑 | Vendor ID |
| 4 | `RFID_NO` | CHAR | 20 | 🔑 | RFID number |
| 5 | `EV_BILL_DATE` | DATS | 8 | 🔑 | EV Bill issue date |
| 6 | `EV_PRICE_KEY` | CHAR | 10 | 🔑 | EV Price key |
| 7 | `SEQ_NO` | NUMC | 2 | 🔑 | Sequence no. |
| 8 | `BILL_START` | DATS | 8 | 🔑 | Bill doc V billing period start date |
| 9 | `BILL_END` | DATS | 8 | 🔑 | Bill doc V billing period end date |
| 10 | `EV_BILL_TYPE` | CHAR | 1 |  | EV Bill type |
| 11 | `EV_QUANTITY` | DEC | 13 |  | EV Quantity |
| 12 | `EV_UNIT_PRICE` | DEC | 17 |  | EV Unit price |
| 13 | `EV_TOT_CHRG_AMT` | CURR | 13 |  | EV Charge amount |
| 14 | `BILL_DOC_NO` | CHAR | 12 |  | Bill doc number |
| 15 | `PRINT_DOC_NO` | CHAR | 12 |  | Print doc / EV doc number |
| 16 | `FICA_DOC_NO` | CHAR | 12 |  | FICA document number |
| 17 | `CREATE_DATE` | DATS | 8 |  | Creation date |
| 18 | `CREATE_TIME` | TIMS | 6 |  | Creation time |
| 19 | `CREATE_USERID` | CHAR | 12 |  | Created by |
| 20 | `UPDATE_DATE` | DATS | 8 |  | Update date |
| 21 | `UPDATE_TIME` | TIMS | 6 |  | Update time |
| 22 | `UPDATE_USERID` | CHAR | 12 |  | Updated by |
