# ZISCS_EEC_BENCADT
**Description:** Output Structure of ZISCSEEC_GET_BENMARK_CA_DETAIL
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `ziscseec_get_benmark_ca_detailft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `EVAL_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `RATE_CAT` | CHAR | 10 |  | Rate category |
| 4 | `HOUSING_TY` | CHAR | 20 |  | Housing Type for EE&C Benchmark grouping |
| 5 | `FLOOR_AREA_CODE` | CHAR | 20 |  | Floor Area Code for EE&C Benchmark grouping |
| 6 | `DISTRICT` | CHAR | 8 |  | Regional structure grouping |
| 7 | `LSB` | CHAR | 40 |  | LSB for EE&C Benchmark grouping |
| 8 | `CONN_OBJ` | CHAR | 30 |  | Connection Object |
| 9 | `KWH` | DEC | 16 |  | Entry value (installed value) for a device |
