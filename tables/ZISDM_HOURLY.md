# ZISDM_HOURLY
**Description:** Hourly Table for MOL For DT
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0222`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `RECORD_DATE` | DATS | 8 |  | Date of consumption record |
| 2 | `TIMEFROM` | TIMS | 6 |  | Start time of consumption record |
| 3 | `TIMETO` | TIMS | 6 |  | End time of consumption record |
| 4 | `ON_PEAK_HR` | CHAR | 1 |  | On peak hour indicator ('X' - On peak) |
| 5 | `NO_PROFILE` | CHAR | 1 |  | No profile found ('X' - No profile) |
| 6 | `CONSUMPTION` | CHAR | 35 |  | Consumption of the period |
