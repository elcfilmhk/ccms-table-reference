# ZISCS_TRD_CLAS
**Description:** Trade class table
**Total Fields:** 5
**Key Fields:** MANDT, TRADE_CAT, TRADE_CLASS

## Programs Using This Table
- `z_bapi_acct_class_mapping=====ft`
- `z_bapi_acct_class_mapping_02==ft`
- `z_bapi_get_tradecls===========ft`
- `zcl_z_bapi_get_tradecl_mpc`
- `ziscs0279`
- `ziscs0281`
- `ziscs0299`
- `ziscs0315`
- `ziscs0318`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TRADE_CAT` | CHAR | 2 | 🔑 | Trade category |
| 3 | `TRADE_CLASS` | CHAR | 10 | 🔑 | Trade |
| 4 | `TEXT1` | CHAR | 40 |  | Trade class description 1 |
| 5 | `TEXT2` | CHAR | 40 |  | Trade class description 2 |
