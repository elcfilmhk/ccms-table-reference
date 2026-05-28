# ZZISDMPEAK_SAP
**Description:** Peak Info Details
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0207`
- `zisdm0337`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `EVENT_DATE` | DATS | 8 |  | Field of type DATS |
| 2 | `EVENT_START_TIME` | TIMS | 6 |  | Event Start Time |
| 3 | `EVENT_END_TIME` | TIMS | 6 |  | Event End Time |
| 4 | `BASELINE_CONS` | DEC | 31 |  | Profile value at application level |
| 5 | `ACTUAL_CONS` | DEC | 31 |  | Profile value at application level |
| 6 | `KWH_SAVED` | INT4 | 10 |  | AMI PTR consumption saved value |
| 7 | `REBATE_AMOUNT` | DEC | 10 |  | AMI PTR Rebate amount |
| 8 | `NA_STATUS` | CHAR | 4 |  | Status of profile value in interface |
| 9 | `T_BASELINE_DAY_CONS` | TTYP | 0 |  | Table Type for ZISDMBASE |
| 10 | `ERROR_MESSAGE` | CHAR | 200 |  | Data Element For error message |
