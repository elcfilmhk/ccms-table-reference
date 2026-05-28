# ZISDM_PROF_HEADER
**Description:** Customized Structure for FM Z_ISDM_METER_REMOVAL
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `z_isdm_meter_removal==========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SERNR` | CHAR | 18 |  | Serial Number |
| 2 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 3 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 4 | `LOGIKZW` | NUMC | 18 |  | Logical register number |
| 5 | `MASSREAD` | UNIT | 3 |  | Unit of measurement for meter reading |
| 6 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 7 | `PROFROLE` | CHAR | 4 |  | Profile allocation role |
| 8 | `DATETO` | DATS | 8 |  | To-Date |
| 9 | `TIMETO` | TIMS | 6 |  | To-Time |
| 10 | `ROLENO` | NUMC | 4 |  | Consecutive number of profile allocation per role |
| 11 | `DATEFROM` | DATS | 8 |  | From-Date |
| 12 | `TIMEFROM` | TIMS | 6 |  | From-time |
