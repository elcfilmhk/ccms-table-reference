# ZISCS_EEC_WEEK_SAV_RS
**Description:** Structure for ZISCSEEC_GET_WEEK_SAV_RS_WS
**Total Fields:** 20
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0481_eec`
- `ziscseec_week_sav_calc========ft`
- `ziscseec_week_sav_get_rs======ft`
- `ziscseec_week_sav_get_rs_ws===ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | Weekly Energy Saving Results for AMI Customers |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `WEEK_END_DATE` | DATS | 8 |  | Date |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `WEEK_START_DATE` | DATS | 8 |  | Date |
| 6 | `WEEK_TOT_KWH` | DEC | 21 |  | AMI consumption value |
| 7 | `WEEK_ONPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 8 | `WEEK_SHOULDER_KWH` | DEC | 21 |  | AMI consumption value |
| 9 | `WEEK_OFFPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 10 | `YOY_TOT_KWH` | DEC | 21 |  | AMI consumption value |
| 11 | `YOY_ONPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 12 | `YOY_SHOULDER_KWH` | DEC | 21 |  | AMI consumption value |
| 13 | `YOY_OFFPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 14 | `SAVED_TOT_KWH_PERC` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
| 15 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 16 | `WOW_TOT_KWH` | DEC | 21 |  | AMI consumption value |
| 17 | `WOW_ONPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 18 | `WOW_SHOULDER_KWH` | DEC | 21 |  | AMI consumption value |
| 19 | `WOW_OFFPEAK_KWH` | DEC | 21 |  | AMI consumption value |
| 20 | `SAV_W_TOT_KWH_PERC` | DEC | 12 |  | Data Element of Technical Type Decimal (Length 12, Scale 2) |
