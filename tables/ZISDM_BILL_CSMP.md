# ZISDM_BILL_CSMP
**Description:** Bill Consumption
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_bill_csmp==========ft`
- `z_bapi_get_bill_csmpt=========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 2 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 3 | `ON_KWH` | DEC | 16 |  | On Peak KWH |
| 4 | `OFF_KWH` | DEC | 16 |  | Off Peak KWH |
| 5 | `TOT_KWH` | DEC | 16 |  | Total KWH |
| 6 | `AVG_KWH` | DEC | 16 |  | Average KWH |
| 7 | `ON_KVA` | DEC | 16 |  | On Peak KVA |
| 8 | `OFF_KVA` | DEC | 16 |  | Off Peak KVA |
| 9 | `TOT_BILLAMT` | DEC | 16 |  | Total Bill Amount |
