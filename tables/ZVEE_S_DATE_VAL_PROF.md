# ZVEE_S_DATE_VAL_PROF
**Description:** Date Value Range with profile
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `z_vee_pre_bill_estimation=====ft`
- `zrvee_pre_bill_estimation`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 2 | `.INCLUDE` | &nbsp; | 0 |  | Structure for From-Date |
| 3 | `DATEFROM` | DATS | 8 |  | From-Date |
| 4 | `TIMEFROM` | TIMS | 6 |  | From-time |
| 5 | `.INCLUDE` | &nbsp; | 0 |  | Structure for To-Date |
| 6 | `DATETO` | DATS | 8 |  | To-Date |
| 7 | `TIMETO` | TIMS | 6 |  | To-Time |
| 8 | `START_VAL` | DEC | 31 |  | Profile value at application level |
| 9 | `END_VAL` | DEC | 31 |  | Profile value at application level |
| 10 | `DATEFROM_L` | DATS | 8 |  | From-Date |
| 11 | `DATETO_L` | DATS | 8 |  | To-Date |
