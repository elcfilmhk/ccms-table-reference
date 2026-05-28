# ZISFIMFAYEARLY
**Description:** Yearly Tariff Review Parameters
**Total Fields:** 33
**Key Fields:** MANDT, TARIFF_YEAR, VERSION

## Programs Using This Table
- `zisfi0297`
- `zisfi0299`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFF_YEAR` | NUMC | 4 | 🔑 | Tariff Year |
| 3 | `VERSION` | NUMC | 2 | 🔑 | Version |
| 4 | `COAL_COST_FORECAST` | DEC | 23 |  | Fuel Cost Forecast of Coal |
| 5 | `COAL_COST_UNIT` | CHAR | 12 |  | Unit |
| 6 | `GAS_COST_FORECAST` | DEC | 23 |  | Fuel Cost Forecast of Gas |
| 7 | `GAS_COST_UNIT` | CHAR | 12 |  | Unit |
| 8 | `OIL_COST_FORECAST` | DEC | 23 |  | Fuel Cost Forecast of Oil |
| 9 | `OIL_COST_UNIT` | CHAR | 12 |  | Unit |
| 10 | `ANNUAL_SALES_FORECAST` | DEC | 23 |  | Annual Sales Forecast |
| 11 | `ANNUAL_FORECAST_UNIT` | CHAR | 12 |  | Unit |
| 12 | `COAL_PRICE_PROJECTED` | DEC | 23 |  | Fuel Price Projected for Coal |
| 13 | `COAL_PRICE_UNIT` | CHAR | 12 |  | Unit |
| 14 | `GAS_PRICE_PROJECTED` | DEC | 23 |  | Fuel Price Projected for Gas |
| 15 | `GAS_PRICE_UNIT` | CHAR | 12 |  | Unit |
| 16 | `OIL_PRICE_PROJECTED` | DEC | 23 |  | Fuel Price Projected for Oil |
| 17 | `OIL_PRICE_UNIT` | CHAR | 12 |  | Unit |
| 18 | `ANNUAL_FCC` | DEC | 23 |  | Annual Fuel Clause Charge |
| 19 | `ANNUAL_FCC_UNIT` | CHAR | 12 |  | Unit |
| 20 | `LOCK_FLAG` | CHAR | 1 |  | Lock Flag |
| 21 | `CANCELLED_FLAG` | CHAR | 1 |  | Cancelled Flag |
| 22 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 23 | `ERZEIT` | TIMS | 6 |  | Time, at Which Record Was Added |
| 24 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 25 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 26 | `AEZEIT` | TIMS | 6 |  | Time of Change |
| 27 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 28 | `LOCK_ON` | DATS | 8 |  | Lock On |
| 29 | `LOCK_AT` | TIMS | 6 |  | Lock At |
| 30 | `LOCK_BY` | CHAR | 12 |  | Lock By |
| 31 | `UNLOCK_ON` | DATS | 8 |  | Unlock On |
| 32 | `UNLOCK_AT` | TIMS | 6 |  | Unlock At |
| 33 | `UNLOCK_BY` | CHAR | 12 |  | Unlock By |
