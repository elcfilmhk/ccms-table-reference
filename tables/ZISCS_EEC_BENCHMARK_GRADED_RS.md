# ZISCS_EEC_BENCHMARK_GRADED_RS
**Description:** Output Structure for FM ZISCSEEC_EO_BENCHMARK_CA_WS
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_eco_benchmark======ft`
- `zcl_ziscseec_eo_benchm_mpc`
- `ziscseec_eo_benchmark_ca_ws===ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `GRP_MIN_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 2 | `GRP_AVG_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 3 | `GRP_MAX_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 4 | `CA_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 5 | `CA_GRADE` | CHAR | 1 |  | Single-Character Flag |
| 6 | `GRP_COUNT` | INT4 | 10 |  | Natural number |
