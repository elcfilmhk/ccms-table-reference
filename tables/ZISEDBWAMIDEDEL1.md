# ZISEDBWAMIDEDEL1
**Description:** Delta profile values table
**Total Fields:** 7
**Key Fields:** PROFILE, PROFVALDAY

## Programs Using This Table
- `zedm_delta_housekeeping`
- `zedm_delta_housekeeping2`
- `zedm_delta_housekeeping_sub`
- `zedm_ext_30int_sub`
- `zedm_records_calculate`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PROFILE` | NUMC | 18 | 🔑 | Number of EDM Profile |
| 2 | `PROFVALDAY` | DATS | 8 | 🔑 | Day of profile values |
| 3 | `SERNR` | CHAR | 18 |  | Serial Number |
| 4 | `VALUE` | DEC | 16 |  | Profile value at application level |
| 5 | `STATUS` | CHAR | 5 |  | Object status |
| 6 | `CREATE_TIMESTAMP` | DEC | 15 |  | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
| 7 | `UPDATE_TIMESTAMP` | DEC | 15 |  | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
