# ZISFIADJSALE_RC
**Description:** Monthly Sales Adj figures breakdown by Acc Class & Rate Cat
**Total Fields:** 22
**Key Fields:** MANDT, REPORT_MONTH, REPORT_YEAR, KTOKL, TARIFTYP

## Programs Using This Table
- `zisfi0083_m2`
- `zisfi0083_m2t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_MONTH` | NUMC | 2 | 🔑 | Consumption Month |
| 3 | `REPORT_YEAR` | NUMC | 4 | 🔑 | Year for period |
| 4 | `KTOKL` | CHAR | 4 | 🔑 | Account class |
| 5 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 6 | `GWH_SOLD` | DEC | 17 |  | GWH Sold Value |
| 7 | `BASIC_R` | CURR | 16 |  | Basic Revenue ($000) |
| 8 | `SPECIAL_R` | CURR | 16 |  | Special Rebates ($000) |
| 9 | `RATE_RR` | CURR | 16 |  | Rate Reduction Rebates ($000) |
| 10 | `SPECIAL_R2006` | CURR | 16 |  | Special Rebates 2006 ($000) |
| 11 | `SPECIAL_R2007` | CURR | 16 |  | Special Rebates 2007 ($000) |
| 12 | `.INCLUDE` | &nbsp; | 0 |  | New price keys |
| 13 | `NRMSREB4` | CURR | 13 |  | 2008 Special Rebate |
| 14 | `NRMSREB6` | CURR | 13 |  | 2022 Special Rebate |
| 15 | `NRMSREB7` | CURR | 13 |  | 2023 Special Rebate |
| 16 | `NRMSREB8` | CURR | 13 |  | Special Fuel Rebate |
| 17 | `REB13` | CURR | 13 |  | 2013 Energy Saving Rebate-GST |
| 18 | `NRMSREB5` | CURR | 13 |  | R&R Special Rebate |
| 19 | `FUEL_CLAUSE` | CURR | 16 |  | Fuel Clause ($000) |
| 20 | `NET_REVENUE` | CURR | 16 |  | Net Revenue ($000) |
| 21 | `GFCREB` | CURR | 13 |  | CLP SME Subsidy (NRT) |
| 22 | `TWAERS` | CUKY | 5 |  | Transaction Currency |
