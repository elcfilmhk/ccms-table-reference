# ZISBI_GET_BILL_DET
**Description:** Energy charge detail return by FICA/PrintDoc
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0133`
- `zisbi0136`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract account |
| 2 | `EV_PRICE_KEY` | CHAR | 10 |  | EV Price key |
| 3 | `EV_QUANTITY` | DEC | 13 |  | EV Quantity |
| 4 | `EV_UNIT_PRICE` | DEC | 17 |  | EV Unit price |
| 5 | `EV_TOT_CHRG_AMT` | CURR | 13 |  | EV Charge amount |
| 6 | `BILL_START` | DATS | 8 |  | Bill doc V billing period start date |
| 7 | `BILL_END` | DATS | 8 |  | Bill doc V billing period end date |
| 8 | `BILL_DOC_NO` | CHAR | 12 |  | Bill doc number |
| 9 | `PRINT_DOC_NO` | CHAR | 12 |  | Print doc / EV doc number |
| 10 | `FICA_DOC_NO` | CHAR | 12 |  | FICA document number |
