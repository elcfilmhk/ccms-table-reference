# ZISFIMFAFUELPRCE
**Description:** Fuel Prices for the Month
**Total Fields:** 8
**Key Fields:** MANDT, TARIFF_YEAR, TARIFF_MONTH, VERSION

## Programs Using This Table
- `zisfi0297`
- `zisfi0299`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFF_YEAR` | NUMC | 4 | 🔑 | Tariff Year |
| 3 | `TARIFF_MONTH` | NUMC | 2 | 🔑 | Tariff Month |
| 4 | `VERSION` | NUMC | 2 | 🔑 | Version |
| 5 | `COAL_PRICE` | DEC | 23 |  | Coal Price |
| 6 | `GAS_PRICE` | DEC | 23 |  | Gas Price |
| 7 | `OIL_PRICE` | DEC | 23 |  | Oil Price |
| 8 | `CANCELLED_FLAG` | CHAR | 1 |  | Cancelled Flag |
