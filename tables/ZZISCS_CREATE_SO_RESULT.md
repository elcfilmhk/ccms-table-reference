# ZZISCS_CREATE_SO_RESULT
**Description:** Result struct for FM "Z_ISCS_CREATE_METER_SO" **Sync CD2!**
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
| 2 | `RESULT` | CHAR | 1 |  | S:Success, F:Failed |
| 3 | `SERNR` | CHAR | 18 |  | Serial Number |
| 4 | `AUFNR` | CHAR | 12 |  | Order Number |
