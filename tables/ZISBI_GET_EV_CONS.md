# ZISBI_GET_EV_CONS
**Description:** EV consumption detail return table
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0133`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VENDOR_ID` | CHAR | 4 |  | The Vendor ID of the EV Vendor |
| 2 | `RFID_NO` | CHAR | 20 |  | The RFID of the RFID Card |
| 3 | `CHARGER_ID` | CHAR | 32 |  | The ID of the charging station |
| 4 | `CHARGER_LOC` | CHAR | 40 |  | Charger Location |
| 5 | `SEQUENCE_NO` | NUMC | 8 |  | The sequence number of the charging session |
| 6 | `END_CHRG_DATE` | DATS | 8 |  | The end date of charging session |
| 7 | `END_CHRG_TIME` | TIMS | 6 |  | The end time of the charging session |
| 8 | `CONSUMPTION` | DEC | 13 |  | The consumption of the interval |
