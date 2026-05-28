# ZZISCS_CREATE_SO_RETCODES
**Description:** Ret code struc for FM "Z_ISCS_CREATE_METER_SO" **Sync CD2!**
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `z_iscs_complete_meter_so======ft`
- `z_iscs_create_meter_so========ft`
- `ziscs0015`
- `ziscs0466`
- `ziscs1119`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ROW_KEY` | INT4 | 10 |  | Natural number |
| 2 | `TYPE` | CHAR | 1 |  | 'I'nfo; 'W'arning; 'E'rror |
| 3 | `RETURN_CODE` | CHAR | 100 |  | Return Code |
| 4 | `MESSAGE` | CHAR | 220 |  | Message Text |
