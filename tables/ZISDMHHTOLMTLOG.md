# ZISDMHHTOLMTLOG
**Description:** Tolerance limit change log for the streetwise handheld
**Total Fields:** 15
**Key Fields:** MANDT, BILLING_CLASS, UNIT_OF_MEASURE, STRATA_NO, ACTION, UDATE, UTIME

## Programs Using This Table
- `zisdm0264`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BILLING_CLASS` | CHAR | 15 | 🔑 | The billing class of the installation of the register |
| 3 | `UNIT_OF_MEASURE` | CHAR | 10 | 🔑 | The unit of measure of the register |
| 4 | `STRATA_NO` | NUMC | 8 | 🔑 | The strata no. of the tolerance limit interval |
| 5 | `ACTION` | CHAR | 10 | 🔑 | Action |
| 6 | `UDATE` | DATS | 8 | 🔑 | Creation date of the change document |
| 7 | `UTIME` | TIMS | 6 | 🔑 | Time changed |
| 8 | `USERNAME` | CHAR | 12 |  | User name of the person responsible in change document |
| 9 | `EC_FROM` | DEC | 17 |  | Valid-to consumption for an interval of tolerance limits |
| 10 | `EC_TO` | DEC | 17 |  | Valid-to consumption for an interval of tolerance limits |
| 11 | `LIMIT_TYPE` | CHAR | 1 |  | The type of tolerance limit V=Fixed Value Limit P =Percent |
| 12 | `L2_LIMIT` | DEC | 17 |  | The Low-2 limit |
| 13 | `L1_LIMIT` | DEC | 17 |  | The Low-1 limit |
| 14 | `H1_LIMIT` | DEC | 17 |  | The High-1 limit |
| 15 | `H2_LIMIT` | DEC | 17 |  | The High-2 limit |
