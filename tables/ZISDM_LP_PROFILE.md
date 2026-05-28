# ZISDM_LP_PROFILE
**Description:** Profile returned from ZED_AGGREGATE_LP
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `zed_aggregate_lp==============ft`
- `zisdm0207`
- `zisdm0231`
- `zisdm0284`
- `zisdm0286`
- `zisdm0310_adr`
- `zisdm0343`
- `zised0008`
- `zised0016`
- `zised0017`
- `zised0049`
- `zisem0004`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MASSREAD` | UNIT | 3 |  | Unit of measurement for meter reading |
| 2 | `DATEFROM` | DATS | 8 |  | From-Date |
| 3 | `TIMEFROM` | TIMS | 6 |  | From-time |
| 4 | `STATUS` | CHAR | 4 |  | Status of profile value in interface |
| 5 | `VALUE` | DEC | 31 |  | Profile value at application level |
| 6 | `STAT` | CHAR | 5 |  | Object status |
