# ZISCS_CREATE_METER_SO_INPUT
**Description:** Input structure of FM "Z_ISCS_CREATE_METER_SO" **Sync CD2!**
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `z_iscs_create_meter_so========ft`
- `ziscs0466`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ROW_KEY` | INT4 | 10 |  | Natural number |
| 2 | `SERNR` | CHAR | 18 |  | Serial Number |
| 3 | `SO_TY` | CHAR | 4 |  | Order Code |
| 4 | `SOLD_TO` | CHAR | 10 |  | Account Number of Customer |
| 5 | `BSC_START_DT` | CHAR | 14 |  | Date Time (YYYYMMDDhhiiss) |
| 6 | `BSC_END_DT` | CHAR | 14 |  | Date Time (YYYYMMDDhhiiss) |
| 7 | `PM_ACT_TY` | CHAR | 3 |  | Maintenance activity type |
| 8 | `MAIN_WORKCNTR` | CHAR | 8 |  | Main work center for maintenance tasks |
| 9 | `PLANNER_GRP` | CHAR | 3 |  | Planner Group for Customer Service and Plant Maintenance |
| 10 | `USER_RESP` | CHAR | 12 |  | User Name |
| 11 | `TPLNR` | CHAR | 30 |  | Functional Location |
