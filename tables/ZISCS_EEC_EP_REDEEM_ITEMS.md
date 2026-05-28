# ZISCS_EEC_EP_REDEEM_ITEMS
**Description:** Customer's list of products to redeem
**Total Fields:** 2
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0475_eec`
- `ziscseec_ep_order_save========ft`
- `ziscseec_ep_redeem============ft`
- `ziscseec_ep_redeem_ws=========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PROD_CODE` | CHAR | 50 |  | EcoPoint Product Code |
| 2 | `QTY` | INT4 | 10 |  | Product Transaction Quantity (+: add Stock; -: reduced Stock |
