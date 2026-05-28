# ZISCSEEC_WESAV
**Description:** Weekly Energy Saving Results for AMI Customers
**Total Fields:** 19
**Key Fields:** MANDT, WEEK_END_DATE, VKONT

## Programs Using This Table
- `ziscs0481_eec`
- `ziscs0482_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `WEEK_END_DATE` | DATS | 8 | 🔑 | Date |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `WEEK_START_DATE` | DATS | 8 |  | Date |
| 5 | `WEEK_TOT_KWH` | DEC | 21 |  | AMI consumption value |
| 6 | `WEEK_ONPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 7 | `WEEK_SHOULDER_KWH` | DEC | 21 |  | AMI consumption value |
| 8 | `WEEK_OFFPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 9 | `YOY_TOT_KWH` | DEC | 21 |  | AMI consumption value |
| 10 | `YOY_ONPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 11 | `YOY_SHOULDER_KWH` | DEC | 21 |  | AMI consumption value |
| 12 | `YOY_OFFPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 13 | `SAVED_TOT_KWH_PERC` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
| 14 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 15 | `WOW_TOT_KWH` | DEC | 21 |  | AMI consumption value |
| 16 | `WOW_ONPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 17 | `WOW_SHOULDER_KWH` | DEC | 21 |  | AMI consumption value |
| 18 | `WOW_OFFPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 19 | `SAV_W_TOT_KWH_PERC` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
