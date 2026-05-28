# ZISFIMFAEFMS
**Description:** EFMS Extracted Data
**Total Fields:** 13
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
| 5 | `ACTUAL_COAL_COST` | DEC | 23 |  | Actual Coal Cost |
| 6 | `ACTUAL_COAL_UNIT` | CHAR | 12 |  | Unit |
| 7 | `ACTUAL_GAS_COST` | DEC | 23 |  | Actual Gas Cost |
| 8 | `ACTUAL_GAS_UNIT` | CHAR | 12 |  | Unit |
| 9 | `ACTUAL_OIL_COST` | DEC | 23 |  | Actual Oil Cost |
| 10 | `ACTUAL_OIL_UNIT` | CHAR | 12 |  | Unit |
| 11 | `CANCELLED_FLAG` | CHAR | 1 |  | Cancelled Flag |
| 12 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 13 | `ERZEIT` | TIMS | 6 |  | Time, at Which Record Was Added |
