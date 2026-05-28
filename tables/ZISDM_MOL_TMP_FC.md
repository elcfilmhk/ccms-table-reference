# ZISDM_MOL_TMP_FC
**Description:** MOL Forecast Table
**Total Fields:** 18
**Key Fields:** MANDT, ISS_DATE, ISS_TIMESLOT, WEA_FC_LOCATION, WEA_DATE

## Programs Using This Table
- `zisdm_mol_key_change_migration`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ISS_DATE` | DATS | 8 | 🔑 | Date 8 digits [Format: YYYYMMDD] |
| 3 | `ISS_TIMESLOT` | CHAR | 10 | 🔑 | Timeslot when the Forecast was issued |
| 4 | `WEA_FC_LOCATION` | CHAR | 8 | 🔑 | Location of Forecast |
| 5 | `WEA_DATE` | DATS | 8 | 🔑 | Date |
| 6 | `ISS_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `WEEK_DAY` | CHAR | 10 |  | Weekday |
| 8 | `WEA_CODE` | CHAR | 2 |  | Weather code |
| 9 | `TEM_MAX` | DEC | 31 |  | MOL equation parameters |
| 10 | `TEM_MIN` | DEC | 31 |  | MOL equation parameters |
| 11 | `TEM_AVG` | DEC | 31 |  | MOL equation parameters |
| 12 | `HUM_MAX` | DEC | 31 |  | MOL equation parameters |
| 13 | `HUM_MIN` | DEC | 31 |  | MOL equation parameters |
| 14 | `HUM_AVG` | DEC | 31 |  | MOL equation parameters |
| 15 | `ENTHALPY` | DEC | 31 |  | MOL equation parameters |
| 16 | `OPGROUP` | CHAR | 10 |  | Operating time groups |
| 17 | `DATATIME` | TIMS | 6 |  | Time |
| 18 | `STATUS` | CHAR | 1 |  | MOL Status |
