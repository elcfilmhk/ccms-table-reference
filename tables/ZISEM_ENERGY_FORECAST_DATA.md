# ZISEM_ENERGY_FORECAST_DATA
**Description:** Structure to hold consumption forecast data
**Total Fields:** 22
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0293`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `SERNR` | CHAR | 18 |  | Serial Number |
| 3 | `ISS_DATE` | DATS | 8 |  | Date 8 digits [Format: YYYYMMDD] |
| 4 | `ISS_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `ISS_TIMESLOT` | CHAR | 10 |  | Timeslot when the Forecast was issued |
| 6 | `WEA_FC_LOCATION` | CHAR | 8 |  | Location of Forecast |
| 7 | `DATE` | DATS | 8 |  | Date of which being forecast |
| 8 | `DAY_OF_WEEK` | INT1 | 3 |  | Day of week(1=MONDAY ... 7=SUNDAY) |
| 9 | `OPGROUP` | CHAR | 10 |  | Operating time groups |
| 10 | `DATATIME` | TIMS | 6 |  | Time of forecast data file |
| 11 | `WEATHER_CODE` | CHAR | 10 |  | Weather Code |
| 12 | `TEM_MAX` | DEC | 31 |  | MOL equation parameters |
| 13 | `TEM_MIN` | DEC | 31 |  | MOL equation parameters |
| 14 | `TEM_AVG` | DEC | 31 |  | MOL equation parameters |
| 15 | `HUM_MAX` | DEC | 31 |  | MOL equation parameters |
| 16 | `HUM_MIN` | DEC | 31 |  | MOL equation parameters |
| 17 | `HUM_AVG` | DEC | 31 |  | MOL equation parameters |
| 18 | `FC_MAX_KVA` | DEC | 31 |  | MOL equation parameters |
| 19 | `FC_MAX_KVA_HR` | TIMS | 6 |  | &nbsp; |
| 20 | `FC_CONS_KWH` | DEC | 31 |  | MOL equation parameters |
| 21 | `HISTORIC_AVG_KWH` | DEC | 31 |  | MOL equation parameters |
| 22 | `HISTORIC_PERIOD` | DATS | 8 |  | Month and Year of Historic Average kWh |
