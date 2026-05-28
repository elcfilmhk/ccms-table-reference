# ZISCS_EEC_EP_BALANCE
**Description:** EcoPoint Balance of a Domeo ID
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_webservice_bound_ca_getft`
- `zcl_z_bapi_webservi_09_dpc_ext`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `RATE_CATE` | CHAR | 10 |  | Rate category |
| 3 | `RATE_CATE_IND` | CHAR | 1 |  | Rate category Indicator |
| 4 | `MOVE_OUT` | DATS | 8 |  | Move-Out Date |
| 5 | `MOVE_OUT_IND` | CHAR | 1 |  | Move-Out Indicator |
| 6 | `EP_AMT` | INT4 | 10 |  | Eco Points Transaction Amount (+: award to CA; -: deduct) |
