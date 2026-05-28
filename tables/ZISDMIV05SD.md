# ZISDMIV05SD
**Description:** Non-BT/LPT account SD calculation for IV05/06
**Total Fields:** 6
**Key Fields:** MANDT, AKLASSE, MEAN_MIN, MEAN_MAX

## Programs Using This Table
- `zcl_iv`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AKLASSE` | CHAR | 4 | 🔑 | Billing class |
| 3 | `MEAN_MIN` | DEC | 12 | 🔑 | Mean (From) |
| 4 | `MEAN_MAX` | DEC | 12 | 🔑 | Mean (To) |
| 5 | `FACTOR_CMIN` | DEC | 2 |  | Factor C for calculation of minimum threshold |
| 6 | `FACTOR_CMAX` | DEC | 2 |  | Factor C for calculation of maximum threshold |
