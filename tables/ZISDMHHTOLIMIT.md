# ZISDMHHTOLIMIT
**Description:** Tolerance limit table for the streetwise handheld
**Total Fields:** 11
**Key Fields:** MANDT, BILLING_CLASS, UNIT_OF_MEASURE, STRATA_NO

## Programs Using This Table
- `zisdh0002`
- `zisdm0027`
- `zisdm0082`
- `zisdm0264`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BILLING_CLASS` | CHAR | 15 | 🔑 | The billing class of the installation of the register |
| 3 | `UNIT_OF_MEASURE` | CHAR | 10 | 🔑 | The unit of measure of the register |
| 4 | `STRATA_NO` | NUMC | 8 | 🔑 | The strata no. of the tolerance limit interval |
| 5 | `EC_FROM` | DEC | 17 |  | Valid-to consumption for an interval of tolerance limits |
| 6 | `EC_TO` | DEC | 17 |  | Valid-to consumption for an interval of tolerance limits |
| 7 | `LIMIT_TYPE` | CHAR | 1 |  | The type of tolerance limit V=Fixed Value Limit P =Percent |
| 8 | `L2_LIMIT` | DEC | 17 |  | The Low-2 limit |
| 9 | `L1_LIMIT` | DEC | 17 |  | The Low-1 limit |
| 10 | `H1_LIMIT` | DEC | 17 |  | The High-1 limit |
| 11 | `H2_LIMIT` | DEC | 17 |  | The High-2 limit |
