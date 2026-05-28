# ZISCS0151_GET_ACC_BAL_OUTPUT
**Description:** Output Struct for FM "ZISCS0151_GET_ACC_BALANCE"
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0151_get_acc_balance=====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `ACCOUNT_BALANCE` | DEC | 16 |  | Decimal Field Length 16 with 4 Decimal Places and +/- Sign |
| 3 | `DUE_DATE` | DATS | 8 |  | Field of type DATS |
| 4 | `DUE_DATE_COUNT` | INT4 | 10 |  | Natural number |
