# ZISDM_MOL_FC_HR
**Description:** MOL Forecast Table (Hourly)
**Total Fields:** 11
**Key Fields:** MANDT, ISS_DATE, ISS_TIMESLOT, WEA_FC_LOCATION, WEA_DATE, WEA_TIME

## Programs Using This Table
- `zisdm0318`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ISS_DATE` | DATS | 8 | 🔑 | Date 8 digits [Format: YYYYMMDD] |
| 3 | `ISS_TIMESLOT` | CHAR | 10 | 🔑 | Timeslot when the Forecast was issued |
| 4 | `WEA_FC_LOCATION` | CHAR | 8 | 🔑 | Location of Forecast |
| 5 | `WEA_DATE` | DATS | 8 | 🔑 | Date |
| 6 | `WEA_TIME` | CHAR | 2 | 🔑 | MOL Hourly Timeslot |
| 7 | `ISS_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 8 | `TEM` | DEC | 31 |  | MOL equation parameters |
| 9 | `HUM` | DEC | 31 |  | MOL equation parameters |
| 10 | `ENTHALPY` | DEC | 31 |  | MOL equation parameters |
| 11 | `STATUS` | CHAR | 1 |  | MOL Status |
