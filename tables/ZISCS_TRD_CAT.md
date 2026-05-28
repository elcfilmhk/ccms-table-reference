# ZISCS_TRD_CAT
**Description:** Trade category table
**Total Fields:** 4
**Key Fields:** MANDT, TRADE_CAT

## Programs Using This Table
- `z_bapi_acct_class_mapping=====ft`
- `z_bapi_acct_class_mapping_01==ft`
- `z_bapi_get_tradecat===========ft`
- `zcl_z_bapi_acct_class__mpc`
- `zcl_z_bapi_get_tradeca_mpc`
- `ziscs0281`
- `ziscs0299`
- `ziscs0315`
- `ziscs0318`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TRADE_CAT` | CHAR | 2 | 🔑 | Trade category |
| 3 | `TEXT1` | CHAR | 60 |  | Trade category description 1 |
| 4 | `TEXT2` | CHAR | 40 |  | Trade category description 2 |
