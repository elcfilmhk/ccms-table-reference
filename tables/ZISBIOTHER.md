# ZISBIOTHER
**Description:** structure for other items  in BAPI Z_BAPI_BILL_PRESENTMENT
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_bill_presentment=======ft`
- `zcl_z_bapi_bill_pre_02_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PRINTDOC` | CHAR | 12 |  | Number of print document |
| 2 | `LANGUAGE` | LANG | 1 |  | Language ID |
| 3 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 4 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 5 | `CONSUMPTION` | CHAR | 36 |  | Consumption |
| 6 | `RATE` | DEC | 8 |  | Rate with 3dec |
| 7 | `LINE_ITEM_NAME` | CHAR | 80 |  | Line item type |
| 8 | `LINE_ITEM_TEXT` | CHAR | 30 |  | Text (30 Characters) |
| 9 | `SUB_TOTAL` | CHAR | 80 |  | Total Charge per line item |
