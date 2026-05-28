# ZISDM_METER_INFO
**Description:** Meter Information
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_meter_info=========ft`
- `zcl_z_bapi_get_meter_i_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SERNR` | CHAR | 18 |  | Serial Number |
| 2 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 3 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 4 | `LOGIKNR` | NUMC | 18 |  | Logical device number |
| 5 | `METERTYP` | CHAR | 1 |  | Meter Type |
| 6 | `FIT` | CHAR | 1 |  | FiT Meter Indicator |
| 7 | `REVENUE_METER` | CHAR | 1 |  | Checkbox |
