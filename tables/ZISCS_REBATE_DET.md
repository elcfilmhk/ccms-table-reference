# ZISCS_REBATE_DET
**Description:** Rebate Amount for Items
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `zcl_ziscseec_eeus_reb__dpc_ext`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ITEM_NO` | NUMC | 3 |  | Serial Number |
| 2 | `RETROFIT_NEW` | CHAR | 2 |  | Retrofit/ New |
| 3 | `EST_ANN_ENE_CONS` | QUAN | 17 |  | Estimated Annual Energy Consumption |
| 4 | `EST_ANN_ENE_SAVE` | QUAN | 17 |  | Estimated Annual Energy Saving |
| 5 | `REB_AMNT` | CURR | 15 |  | Calculated Rebate Amount |
| 6 | `PRIORITY` | CHAR | 1 |  | Priority |
