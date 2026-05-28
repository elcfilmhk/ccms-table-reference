# ZISCS_AC_MAP
**Description:** Trade class to premise function mapping
**Total Fields:** 4
**Key Fields:** MANDT, TRADE_CLASS, PREM_FUNC

## Programs Using This Table
- `z_bapi_acct_class_mapping=====ft`
- `z_bapi_acct_class_mapping_04==ft`
- `z_bapi_map_acct_class=========ft`
- `zcl_z_bapi_map_acct_cl_mpc`
- `ziscs0279`
- `ziscs0281`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TRADE_CLASS` | CHAR | 10 | 🔑 | Trade |
| 3 | `PREM_FUNC` | CHAR | 3 | 🔑 | Premise function |
| 4 | `KTOKL` | CHAR | 4 |  | Account class |
