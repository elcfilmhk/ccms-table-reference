# ZISDMEV_AMENDMENT_S
**Description:** Structure for Z_ISDM_CONSUMP_AMENDMENT_SCR screen use
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0226`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZDATE` | DATS | 8 |  | Date which the consumption entries received from EV Vendor |
| 2 | `SEQ` | NUMC | 8 |  | Sequence number from EV Vendor for the day |
| 3 | `INT_START_DATE` | DATS | 8 |  | The start date of the interval |
| 4 | `INT_START_TIME` | TIMS | 6 |  | The start time of the interval |
| 5 | `INT_CONSUMPTION` | DEC | 13 |  | The consumption of the interval |
| 6 | `INT_START_RDG` | DEC | 13 |  | The start reading of the interval |
| 7 | `INT_END_RDG` | DEC | 13 |  | The end reading of the interval |
| 8 | `STATUS` | CHAR | 1 |  | The status of the interval |
| 9 | `STATUS_DESC` | CHAR | 15 |  | The description of the status |
| 10 | `MARK` | CHAR | 1 |  | General Flag |
