# ZISFIMFAMSBI
**Description:** MSBI Extracted Data
**Total Fields:** 11
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
| 5 | `ACTUAL_COAL_CONS` | DEC | 23 |  | Actual Coal Consumption |
| 6 | `COAL_CONS_UNIT` | CHAR | 12 |  | Unit |
| 7 | `ACTUAL_OIL_CONS` | DEC | 23 |  | Actual Oil Consumption |
| 8 | `OIL_CONS_UNIT` | CHAR | 12 |  | Unit |
| 9 | `CANCELLED_FLAG` | CHAR | 1 |  | Cancelled Flag |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERZEIT` | TIMS | 6 |  | Time, at Which Record Was Added |
