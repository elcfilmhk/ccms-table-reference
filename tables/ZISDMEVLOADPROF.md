# ZISDMEVLOADPROF
**Description:** EV Load Profile Interface File Data
**Total Fields:** 10
**Key Fields:** MANDT, ZDATE, SEQ

## Programs Using This Table
- `zisdm0220`
- `zisdm0225`
- `zisdm0228`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZDATE` | DATS | 8 | 🔑 | Date which the consumption entries received from EV Vendor |
| 3 | `SEQ` | NUMC | 8 | 🔑 | Sequence number from EV Vendor for the day |
| 4 | `VENDOR_ID` | CHAR | 4 |  | The Vendor ID of the EV Vendor |
| 5 | `CHARGESTATION_ID` | CHAR | 32 |  | The ID of the charging station |
| 6 | `INT_START_DATE` | DATS | 8 |  | The start date of the interval |
| 7 | `INT_START_TIME` | TIMS | 6 |  | The start time of the interval |
| 8 | `INT_CONSUMPTION` | DEC | 13 |  | The consumption of the interval |
| 9 | `INT_END_RDG` | DEC | 13 |  | The end reading of the interval |
| 10 | `STATUS` | CHAR | 1 |  | The status of the interval |
