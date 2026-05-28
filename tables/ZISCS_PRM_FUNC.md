# ZISCS_PRM_FUNC
**Description:** Premise function table
**Total Fields:** 4
**Key Fields:** MANDT, PREM_FUNC

## Programs Using This Table
- `z_bapi_acct_class_mapping=====ft`
- `z_bapi_acct_class_mapping_03==ft`
- `z_bapi_get_prmfunc============ft`
- `zcl_z_bapi_acct_cla_02_mpc`
- `zcl_z_bapi_get_prmfunc_mpc`
- `ziscs0281`
- `ziscs0299`
- `ziscs0315`
- `ziscs0318`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PREM_FUNC` | CHAR | 3 | 🔑 | Premise function |
| 3 | `TEXT1` | CHAR | 40 |  | Premise function description 1 |
| 4 | `TEXT2` | CHAR | 40 |  | Premise function description 2 |
