# ZISFIADJSALE
**Description:** Custom Table to store monthly Sales Adjustment figures
**Total Fields:** 24
**Key Fields:** MANDT, REPORT_MONTH, REPORT_YEAR, REPORT_SECTION, COUNTER

## Programs Using This Table
- `zisfi0083_m2`
- `zisfi0083_m2t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_MONTH` | NUMC | 2 | 🔑 | Consumption Month |
| 3 | `REPORT_YEAR` | NUMC | 4 | 🔑 | Year for period |
| 4 | `REPORT_SECTION` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 5 | `COUNTER` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 6 | `REPORT_CLASS` | CHAR | 31 |  | Class |
| 7 | `CLASSTEXT` | CHAR | 50 |  | Account Class Description |
| 8 | `GWH_SOLD` | DEC | 17 |  | GWH Sold Value |
| 9 | `BASIC_R` | CURR | 16 |  | Basic Revenue ($000) |
| 10 | `SPECIAL_R` | CURR | 16 |  | Special Rebates ($000) |
| 11 | `RATE_RR` | CURR | 16 |  | Rate Reduction Rebates ($000) |
| 12 | `SPECIAL_R2006` | CURR | 16 |  | Special Rebates 2006 ($000) |
| 13 | `SPECIAL_R2007` | CURR | 16 |  | Special Rebates 2007 ($000) |
| 14 | `.INCLUDE` | &nbsp; | 0 |  | New price keys |
| 15 | `NRMSREB4` | CURR | 13 |  | 2008 Special Rebate |
| 16 | `NRMSREB6` | CURR | 13 |  | 2022 Special Rebate |
| 17 | `NRMSREB7` | CURR | 13 |  | 2023 Special Rebate |
| 18 | `NRMSREB8` | CURR | 13 |  | Special Fuel Rebate |
| 19 | `REB13` | CURR | 13 |  | 2013 Energy Saving Rebate-GST |
| 20 | `NRMSREB5` | CURR | 13 |  | R&R Special Rebate |
| 21 | `FUEL_CLAUSE` | CURR | 16 |  | Fuel Clause ($000) |
| 22 | `NET_REVENUE` | CURR | 16 |  | Net Revenue ($000) |
| 23 | `GFCREB` | CURR | 13 |  | CLP SME Subsidy (NRT) |
| 24 | `TWAERS` | CUKY | 5 |  | Transaction Currency |
