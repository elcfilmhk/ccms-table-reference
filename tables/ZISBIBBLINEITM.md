# ZISBIBBLINEITM
**Description:** Budget billing item detail
**Total Fields:** 10
**Key Fields:** MANDT, OPBEL, VKONT, CAT_TYPE, BELZEILE

## Programs Using This Table
- `zisbi0108`
- `zisbi0112`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `CAT_TYPE` | CHAR | 2 | 🔑 | Category |
| 5 | `BELZEILE` | CHAR | 6 | 🔑 | Line Item |
| 6 | `AMOUNT` | CURR | 13 |  | Net amount of billing line item |
| 7 | `I_ZWSTNDAB` | DEC | 31 |  | Billed meter reading |
| 8 | `I_ABRMENGE` | DEC | 31 |  | Billing quantity for internal billing format |
| 9 | `FR_DATE` | DATS | 8 |  | From Date |
| 10 | `TO_DATE` | DATS | 8 |  | To Date |
