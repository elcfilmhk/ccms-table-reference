# ZISCS_TARIFF_OUT
**Description:** Tariff Price Calculation
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_simu_blockrate=========ft`
- `z_bapi_tariff_simulation======ft`
- `zcl_z_bapi_simu_blockr_mpc`
- `ztest_simulation`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZSEQ` | NUMC | 3 |  | Sequence |
| 2 | `CHARGE_TYPE` | CHAR | 40 |  | Description |
| 3 | `CONSUMPTION` | NUMC | 10 |  | To-block |
| 4 | `RATE` | DEC | 17 |  | Price amount |
| 5 | `CHARGE` | CURR | 13 |  | Tariff Price Calculation |
| 6 | `CURRENCY` | CUKY | 5 |  | Transaction Currency |
| 7 | `FROM_DATE` | DATS | 8 |  | Date from which time slice is valid |
| 8 | `TO_DATE` | DATS | 8 |  | Date at Which a Time Slice Expires |
