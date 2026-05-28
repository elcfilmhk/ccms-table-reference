# ZISBIAMI_CALC_BILL
**Description:** Structure for Billing calculator BAPI
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0337`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `START_DATE` | CHAR | 8 |  | Start Date |
| 2 | `EXPIRE_DATE` | CHAR | 8 |  | Expire Date |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `QUANTITY` | DEC | 31 |  | Billing quantity for internal billing format |
| 5 | `UNIT_PRICE` | DEC | 17 |  | Price amount |
| 6 | `AMOUNT` | CURR | 13 |  | Net amount of billing line item |
| 7 | `LINE_ITEM_TYP` | CHAR | 6 |  | Line Item Type |
