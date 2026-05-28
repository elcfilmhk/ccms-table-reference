# ZISCSCONSUM
**Description:** BP  Consumption Values
**Total Fields:** 45
**Key Fields:** MANDT, NR_MONTH, PARTNER, REL_PARTNER, MAS_PARTNER

## Programs Using This Table
- `zisbifi_recon`
- `ziscs0084`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `NR_MONTH` | NUMC | 2 | 🔑 | Number of months (00 = YTD) |
| 3 | `PARTNER` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `REL_PARTNER` | CHAR | 10 | 🔑 | Business Partner Number |
| 5 | `MAS_PARTNER` | CHAR | 10 | 🔑 | Business Partner Number |
| 6 | `FUEL` | DEC | 16 |  | Amount |
| 7 | `CHARGE` | DEC | 16 |  | Amount |
| 8 | `CONSUMPTION` | DEC | 16 |  | Amount |
| 9 | `REBATE` | DEC | 16 |  | Amount |
| 10 | `SP_REBATE` | DEC | 16 |  | Amount |
| 11 | `REBATE_2007_1` | DEC | 16 |  | Amount |
| 12 | `REBATE_2007_2` | DEC | 16 |  | Amount |
| 13 | `.INCLUDE` | &nbsp; | 0 |  | New price keys |
| 14 | `NRMSREB4` | CURR | 13 |  | 2008 Special Rebate |
| 15 | `NRMSREB6` | CURR | 13 |  | 2022 Special Rebate |
| 16 | `NRMSREB7` | CURR | 13 |  | 2023 Special Rebate |
| 17 | `NRMSREB8` | CURR | 13 |  | Special Fuel Rebate |
| 18 | `REB13` | CURR | 13 |  | 2013 Energy Saving Rebate-GST |
| 19 | `NRMSREB5` | CURR | 13 |  | R&R Special Rebate |
| 20 | `PLOUT_FUEL` | DEC | 16 |  | Amount |
| 21 | `PLOUT_CHARGE` | DEC | 16 |  | Amount |
| 22 | `PLOUT_CONSUMPT` | DEC | 16 |  | Amount |
| 23 | `PLOUT_REBATE` | DEC | 16 |  | Amount |
| 24 | `PLOUT_SP_REBATE` | DEC | 16 |  | Amount |
| 25 | `PLOUT_R2007_1` | DEC | 16 |  | Amount |
| 26 | `PLOUT_R2007_2` | DEC | 16 |  | Amount |
| 27 | `PLOUT_NRMSREB4` | DEC | 16 |  | Amount |
| 28 | `PLOUT_NRMSREB6` | DEC | 16 |  | Amount |
| 29 | `PLOUT_NRMSREB7` | DEC | 16 |  | Amount |
| 30 | `PLOUT_NRMSREB8` | DEC | 16 |  | Amount |
| 31 | `PLOUT_REB13` | DEC | 16 |  | Amount |
| 32 | `PLOUT_NRMSREB5` | DEC | 16 |  | Amount |
| 33 | `CLOUT_FUEL` | DEC | 16 |  | Amount |
| 34 | `CLOUT_CHARGE` | DEC | 16 |  | Amount |
| 35 | `CLOUT_CONSUMPT` | DEC | 16 |  | Amount |
| 36 | `CLOUT_REBATE` | DEC | 16 |  | Amount |
| 37 | `CLOUT_SP_REBATE` | DEC | 16 |  | Amount |
| 38 | `CLOUT_R2007_1` | DEC | 16 |  | Amount |
| 39 | `CLOUT_R2007_2` | DEC | 16 |  | Amount |
| 40 | `CLOUT_NRMSREB4` | DEC | 16 |  | Amount |
| 41 | `CLOUT_NRMSREB6` | DEC | 16 |  | Amount |
| 42 | `CLOUT_NRMSREB7` | DEC | 16 |  | Amount |
| 43 | `CLOUT_NRMSREB8` | DEC | 16 |  | Amount |
| 44 | `CLOUT_REB13` | DEC | 16 |  | Amount |
| 45 | `CLOUT_NRMSREB5` | DEC | 16 |  | Amount |
