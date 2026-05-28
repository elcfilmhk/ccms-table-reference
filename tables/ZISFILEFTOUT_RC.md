# ZISFILEFTOUT_RC
**Description:** Leftout breakdown by Account Class and Rate Category
**Total Fields:** 24
**Key Fields:** MANDT, REPORT_MONTH, REPORT_YEAR, KTOKL, TARIFTYP

## Programs Using This Table
- `zisfi0083_1`
- `zisfi0083_1t`
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
| 7 | `BASIC_R` | CURR | 13 |  | Basic Revenue ($000) |
| 8 | `SPECIAL_R` | CURR | 13 |  | Special Rebates ($000) |
| 9 | `RATE_RR` | CURR | 13 |  | Rate Reduction Rebates ($000) |
| 10 | `SPECIAL_R2006` | CURR | 13 |  | Special Rebates 2006 ($000) |
| 11 | `SPECIAL_R2007` | CURR | 13 |  | Special Rebates 2007 ($000) |
| 12 | `.INCLUDE` | &nbsp; | 0 |  | New price keys |
| 13 | `NRMSREB4` | CURR | 13 |  | 2008 Special Rebate |
| 14 | `NRMSREB6` | CURR | 13 |  | 2022 Special Rebate |
| 15 | `NRMSREB7` | CURR | 13 |  | 2023 Special Rebate |
| 16 | `NRMSREB8` | CURR | 13 |  | Special Fuel Rebate |
| 17 | `REB13` | CURR | 13 |  | 2013 Energy Saving Rebate-GST |
| 18 | `NRMSREB5` | CURR | 13 |  | R&R Special Rebate |
| 19 | `FUEL_CLAUSE` | CURR | 13 |  | Fuel Clause ($000) |
| 20 | `DSM_CHARGE` | CURR | 13 |  | DSM Charge ($000) |
| 21 | `BR_REBATE` | CURR | 13 |  | BR Rebate ($000) |
| 22 | `NET_REVENUE` | CURR | 13 |  | Net Revenue ($000) |
| 23 | `GFCREB` | CURR | 13 |  | CLP SME Subsidy(NRT) ($000) |
| 24 | `TWAERS` | CUKY | 5 |  | Transaction Currency |
