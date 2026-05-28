# ZISBILNITEM
**Description:** Structure for Line Item
**Total Fields:** 3
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_bill_presentment=======ft`
- `zcl_z_bapi_bill_pre_01_mpc`
- `zcl_z_bapi_test_table_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `LINE_ITEM_NAME` | CHAR | 80 |  | Line item type |
| 2 | `LINE_ITEM_TEXT` | CHAR | 30 |  | Text (30 Characters) |
| 3 | `SUB_TOTAL` | CHAR | 80 |  | Total Charge per line item |
