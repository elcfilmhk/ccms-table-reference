# ZISBIBBCNMPITM
**Description:** Budget Billing Consumption information
**Total Fields:** 12
**Key Fields:** MANDT, OPBEL, VKONT, CONSUM_ITEM, CAT_TYPE

## Programs Using This Table
- `zisbi0108`
- `zisbi0112`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `CONSUM_ITEM` | CHAR | 6 | 🔑 | Consumption Item |
| 5 | `CAT_TYPE` | CHAR | 2 | 🔑 | Category |
| 6 | `NETTOBTR` | CURR | 13 |  | Net amount of billing line item |
| 7 | `I_ABRMENGE` | DEC | 31 |  | Billing quantity for internal billing format |
| 8 | `PERCENTAGE` | CHAR | 15 |  | Percentage |
| 9 | `NO_OF_DAY` | NUMC | 3 |  | No Of Days |
| 10 | `EXTRA_RATE` | DEC | 17 |  | Price amount |
| 11 | `FR_DATE` | DATS | 8 |  | From Date |
| 12 | `TO_DATE` | DATS | 8 |  | To Date |
