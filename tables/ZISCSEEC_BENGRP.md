# ZISCSEEC_BENGRP
**Description:** Benchmarking Group
**Total Fields:** 19
**Key Fields:** MANDT, EVAL_DT, GRP_ID

## Programs Using This Table
- `ziscs0382_eec`
- `ziscs0397_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVAL_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 3 | `GRP_ID` | INT4 | 10 | 🔑 | Natural number |
| 4 | `EVAL_SEQ` | INT4 | 10 |  | Natural number |
| 5 | `RATE_CAT` | CHAR | 10 |  | Rate category |
| 6 | `HOUSING_TY` | CHAR | 20 |  | Housing Type for EE&C Benchmark grouping |
| 7 | `FLOOR_AREA_CODE` | CHAR | 20 |  | Floor Area Code for EE&C Benchmark grouping |
| 8 | `DISTRICT` | CHAR | 8 |  | District for EE&C Benchmark grouping |
| 9 | `LSB` | CHAR | 40 |  | LSB for EE&C Benchmark grouping |
| 10 | `CONN_OBJ` | CHAR | 30 |  | Connection Object |
| 11 | `GRP_MAX_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 12 | `GRP_MIN_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 13 | `GRP_AVG_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 14 | `GRP_COUNT` | INT4 | 10 |  | Natural number |
| 15 | `GRP_TIER` | CHAR | 8 |  | EE&C benchmark grouping tier |
| 16 | `GRP_GRADE_A_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 17 | `GRP_GRADE_B_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 18 | `GRP_GRADE_C_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 19 | `GRP_GRADE_D_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
