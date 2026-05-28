# ZISCS_EEC_BENGRP
**Description:** Output structure for FM ZISCSEEC_RECALC_BENCHMARK_GRP
**Total Fields:** 20
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0382_eec`
- `ziscseec_get_ca_bengrp========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | Benchmarking Group |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `EVAL_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `GRP_ID` | INT4 | 10 |  | Natural number |
| 5 | `EVAL_SEQ` | INT4 | 10 |  | Natural number |
| 6 | `RATE_CAT` | CHAR | 10 |  | Rate category |
| 7 | `HOUSING_TY` | CHAR | 20 |  | Housing Type for EE&C Benchmark grouping |
| 8 | `FLOOR_AREA_CODE` | CHAR | 20 |  | Floor Area Code for EE&C Benchmark grouping |
| 9 | `DISTRICT` | CHAR | 8 |  | District for EE&C Benchmark grouping |
| 10 | `LSB` | CHAR | 40 |  | LSB for EE&C Benchmark grouping |
| 11 | `CONN_OBJ` | CHAR | 30 |  | Connection Object |
| 12 | `GRP_MAX_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 13 | `GRP_MIN_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 14 | `GRP_AVG_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 15 | `GRP_COUNT` | INT4 | 10 |  | Natural number |
| 16 | `GRP_TIER` | CHAR | 8 |  | EE&C benchmark grouping tier |
| 17 | `GRP_GRADE_A_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 18 | `GRP_GRADE_B_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 19 | `GRP_GRADE_C_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 20 | `GRP_GRADE_D_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
