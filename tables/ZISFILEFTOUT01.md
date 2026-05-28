# ZISFILEFTOUT01
**Description:** Custom Table to populate BT/LPT leftout and DT Leftout
**Total Fields:** 27
**Key Fields:** MANDT, REPORT_MONTH, REPORT_YEAR, REPORT_SECTION, COUNTER

## Programs Using This Table
- `zisfi0083`
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
| 4 | `REPORT_SECTION` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 5 | `COUNTER` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 6 | `REPORT_CLASS` | CHAR | 31 |  | Class |
| 7 | `REPORT_TARIFF` | CHAR | 22 |  | Tariff |
| 8 | `CLASSTEXT` | CHAR | 50 |  | Account Class Description |
| 9 | `GWH_SOLD` | DEC | 17 |  | GWH Sold Value |
| 10 | `BASIC_R` | CURR | 13 |  | Basic Revenue ($000) |
| 11 | `SPECIAL_R` | CURR | 13 |  | Special Rebates ($000) |
| 12 | `RATE_RR` | CURR | 13 |  | Rate Reduction Rebates ($000) |
| 13 | `SPECIAL_R2006` | CURR | 13 |  | Special Rebates 2006 ($000) |
| 14 | `SPECIAL_R2007` | CURR | 13 |  | Special Rebates 2007 ($000) |
| 15 | `.INCLUDE` | &nbsp; | 0 |  | New price keys |
| 16 | `NRMSREB4` | CURR | 13 |  | 2008 Special Rebate |
| 17 | `NRMSREB6` | CURR | 13 |  | 2022 Special Rebate |
| 18 | `NRMSREB7` | CURR | 13 |  | 2023 Special Rebate |
| 19 | `NRMSREB8` | CURR | 13 |  | Special Fuel Rebate |
| 20 | `REB13` | CURR | 13 |  | 2013 Energy Saving Rebate-GST |
| 21 | `NRMSREB5` | CURR | 13 |  | R&R Special Rebate |
| 22 | `FUEL_CLAUSE` | CURR | 13 |  | Fuel Clause ($000) |
| 23 | `DSM_CHARGE` | CURR | 13 |  | DSM Charge ($000) |
| 24 | `BR_REBATE` | CURR | 13 |  | BR Rebate ($000) |
| 25 | `NET_REVENUE` | CURR | 13 |  | Net Revenue ($000) |
| 26 | `GFCREB` | CURR | 13 |  | CLP SME Subsidy(NRT) ($000) |
| 27 | `TWAERS` | CUKY | 5 |  | Transaction Currency |
