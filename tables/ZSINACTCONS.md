# ZSINACTCONS
**Description:** Struct for inactive consuption
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_inact_consumption==ft`
- `zcl_z_bapi_get_inac_co_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BEGDA` | DATS | 8 |  | Start Date |
| 2 | `ENDDA` | DATS | 8 |  | End Date |
| 3 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 4 | `MASS` | UNIT | 3 |  | Unit of Measurement |
| 5 | `INACTCONS` | DEC | 22 |  | Profile Value 22(6) |
