# ZISDMIV05P
**Description:** Non-BT/LPT account parameters for IV05/06
**Total Fields:** 14
**Key Fields:** MANDT, AKLASSE

## Programs Using This Table
- `zcl_iv`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AKLASSE` | CHAR | 4 | 🔑 | Billing class |
| 3 | `FACTOR_A` | DEC | 3 |  | Factor A |
| 4 | `FACTOR_BMIN` | DEC | 3 |  | Factor B for calculation of minimum threshold |
| 5 | `FACTOR_BMAX` | DEC | 3 |  | Factor B for calculation of maximum threshold |
| 6 | `FACTOR_D` | DEC | 3 |  | Factor D |
| 7 | `MIN1` | DEC | 2 |  | 1st Preference, min sample |
| 8 | `MAX1` | DEC | 2 |  | 1st Preference, max. sample |
| 9 | `MONTH1` | DEC | 2 |  | 1st Preference, +/- months |
| 10 | `MIN2` | DEC | 2 |  | 2nd Preference, min sample |
| 11 | `MAX2` | DEC | 2 |  | 2nd Preference, max sample |
| 12 | `MONTH2` | DEC | 2 |  | 2nd Preference, previous month |
| 13 | `PASTMTH` | DEC | 2 |  | Duration of past months |
| 14 | `ALLOWCONS` | DEC | 6 |  | Allowable Consumption |
