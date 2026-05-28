# ZISDMEVBCSMP
**Description:** EV Bill Consumption Entries from EV Vendor
**Total Fields:** 19
**Key Fields:** MANDT, ZDATE, SEQ

## Programs Using This Table
- `zisdm0219`
- `zisdm0220`
- `zisdm0223`
- `zisdm0224`
- `zisdm0226`
- `zisdm0227`
- `zisdm0230`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZDATE` | DATS | 8 | 🔑 | Date which the consumption entries received from EV Vendor |
| 3 | `SEQ` | NUMC | 8 | 🔑 | Sequence number from EV Vendor for the day |
| 4 | `VENDOR_ID` | CHAR | 4 |  | The Vendor ID of the EV Vendor |
| 5 | `RFID_NO` | CHAR | 20 |  | The RFID of the RFID Card |
| 6 | `CHARGESTATION_ID` | CHAR | 32 |  | The ID of the charging station |
| 7 | `SEQUENCE_NO` | NUMC | 8 |  | The sequence number of the charging session |
| 8 | `START_CHRG_DATE` | DATS | 8 |  | The start date of charging session |
| 9 | `START_CHRG_TIME` | TIMS | 6 |  | The start time of charging session |
| 10 | `END_CHRG_DATE` | DATS | 8 |  | The end date of charging session |
| 11 | `END_CHRG_TIME` | TIMS | 6 |  | The end time of the charging session |
| 12 | `INT_START_DATE` | DATS | 8 |  | The start date of the interval |
| 13 | `INT_START_TIME` | TIMS | 6 |  | The start time of the interval |
| 14 | `INT_CONSUMPTION` | DEC | 13 |  | The consumption of the interval |
| 15 | `INT_START_RDG` | DEC | 13 |  | The start reading of the interval |
| 16 | `INT_END_RDG` | DEC | 13 |  | The end reading of the interval |
| 17 | `STATUS` | CHAR | 1 |  | The status of the interval |
| 18 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 19 | `FI_DOC_NO` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
