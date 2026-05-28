# ZISCSEEC_BENCADT
**Description:** Temp table for EE&C Benchmark group calculation
**Total Fields:** 11
**Key Fields:** MANDT, EVAL_DT, VKONT

## Programs Using This Table
- `ziscs0395_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVAL_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `RATE_CAT` | CHAR | 10 |  | Rate category |
| 5 | `HOUSING_TY` | CHAR | 20 |  | Housing Type for EE&C Benchmark grouping |
| 6 | `FLOOR_AREA_CODE` | CHAR | 20 |  | Floor Area Code for EE&C Benchmark grouping |
| 7 | `DISTRICT` | CHAR | 8 |  | District for EE&C Benchmark grouping |
| 8 | `LSB` | CHAR | 40 |  | LSB for EE&C Benchmark grouping |
| 9 | `CONN_OBJ` | CHAR | 30 |  | Connection Object |
| 10 | `KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 11 | `GRP_ID` | INT4 | 10 |  | Natural number |
