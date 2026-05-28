# ZISBIENRGYCHARGE
**Description:** structure for Energy charge  in BAPI Z_BAPI_BILL_PRESENTMENT
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_bill_presentment=======ft`
- `zcl_z_bapi_bill_pre_02_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PRINTDOC` | CHAR | 12 |  | Number of print document |
| 2 | `LANGUAGE` | LANG | 1 |  | Language ID |
| 3 | `CODE` | CHAR | 6 |  | Line Item Type |
| 4 | `DESCRIPTION` | CHAR | 30 |  | Text (30 Characters) |
| 5 | `BLOCK_NO` | CHAR | 10 |  | block no |
| 6 | `BLOCK_SIZE` | CHAR | 20 |  | block size |
| 7 | `BLOCK_SIZE_TEXT` | CHAR | 20 |  | Block size test |
| 8 | `RATE` | DEC | 8 |  | Rate with 3dec |
| 9 | `CONSUMPTION` | CHAR | 36 |  | Consumption |
| 10 | `AMOUNT` | CHAR | 30 |  | Currency amount in BAPI interfaces |
