# ZISSDSOREFITM
**Description:** Sales Order Reference for Retail Sales (Item)
**Total Fields:** 34
**Key Fields:** MANDT, SALES_ORDER_REF, ITEM_NO

## Programs Using This Table
- `zissd00085`
- `zissd00086`
- `zissd00086a`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SALES_ORDER_REF` | CHAR | 18 | 🔑 | Sales Order Reference Number |
| 3 | `ITEM_NO` | NUMC | 6 | 🔑 | Item Number |
| 4 | `PDT_TYPE` | CHAR | 4 |  | Product Type |
| 5 | `PDT_BRAND` | CHAR | 18 |  | Product Brand |
| 6 | `PDT_BRAND_TEXT` | CHAR | 20 |  | Product Brand Text |
| 7 | `PDT_DESC` | CHAR | 40 |  | Product Description |
| 8 | `PRODUCT_NO` | CHAR | 18 |  | Product Number |
| 9 | `QTY` | QUAN | 13 |  | Quantity |
| 10 | `UNIT` | UNIT | 3 |  | Unit |
| 11 | `CURRENCY` | CUKY | 5 |  | Currency Key |
| 12 | `UNIT_PRICE` | CURR | 15 |  | Unit Price |
| 13 | `DISCOUNT` | CURR | 11 |  | Discount |
| 14 | `REBATE_PC` | NUMC | 3 |  | Rebate Percentage |
| 15 | `SALES_PRICE` | CURR | 15 |  | Sales Price |
| 16 | `EXT_WARR` | CHAR | 10 |  | Extended Warranty |
| 17 | `PRODT_TYPE` | CHAR | 10 |  | Product Type |
| 18 | `EXH_VALVE` | CHAR | 10 |  | Exhaust Valve |
| 19 | `RMV_APPL` | CHAR | 10 |  | Remove Appliance |
| 20 | `GAS_DISCON` | CHAR | 1 |  | Gas Disconnect Indicator |
| 21 | `REJECT_REASON` | CHAR | 2 |  | Rejection Reason for Sales Order Item |
| 22 | `ITEM_NO_PARENT` | NUMC | 6 |  | Item Number (Parent) |
| 23 | `CREATE_DATE` | DATS | 8 |  | Creation date |
| 24 | `CREATE_TIME` | TIMS | 6 |  | Creation Time |
| 25 | `CREATED_BY` | CHAR | 12 |  | Created By |
| 26 | `UPDATE_DATE` | DATS | 8 |  | Last change date |
| 27 | `UPDATE_TIME` | TIMS | 6 |  | Last changed at |
| 28 | `UPDATED_BY` | CHAR | 12 |  | Last Changed by |
| 29 | `CANCEL_DATE` | DATS | 8 |  | Cancel date |
| 30 | `CANCEL_TIME` | TIMS | 6 |  | Cancel time |
| 31 | `CANCELLED_BY` | CHAR | 12 |  | Cancelled by |
| 32 | `DEL_TYPE` | CHAR | 20 |  | Delivery type |
| 33 | `DEL_DATE` | DATS | 8 |  | Delivery date |
| 34 | `DEL_PERIOD` | CHAR | 10 |  | Delivery period |
