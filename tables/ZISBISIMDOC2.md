# ZISBISIMDOC2
**Description:** Left out for RBI25B
**Total Fields:** 35
**Key Fields:** MANDT, PERIOD, VERTRAG

## Programs Using This Table
- `zisbi0061`
- `zisbi0062`
- `zisbi0062_1`
- `zisbi0062_1t`
- `zisbi0071`
- `zisbi0071_tmp`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PERIOD` | CHAR | 6 | 🔑 | Period (MMYYYY) |
| 3 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 4 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `KOFIZ` | CHAR | 2 |  | Account determination ID for IS-U contracts |
| 7 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 8 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 9 | `LAST_RDG_DATE` | DATS | 8 |  | Last actual reading date |
| 10 | `CURR_RDG_DATE` | DATS | 8 |  | Current actual reading date |
| 11 | `TOT_KWH` | DEC | 17 |  | Total Kwh |
| 12 | `C_NETTOBTR` | CURR | 13 |  | Consumption charge |
| 13 | `D_NETTOBTR` | CURR | 13 |  | Demand charge |
| 14 | `HLFR` | CURR | 13 |  | HLFR |
| 15 | `STB_CHRG` | CURR | 13 |  | Standby charge |
| 16 | `F_CLAUSE` | CURR | 13 |  | FUEL clause |
| 17 | `REBATE` | CURR | 13 |  | Rebate |
| 18 | `MISC_REBATE` | CURR | 13 |  | Misc. rebate |
| 19 | `REBATE_2007_1` | CURR | 13 |  | 2007 misc. rebate 1 |
| 20 | `REBATE_2007_2` | CURR | 13 |  | 2007 misc. rebate 2 |
| 21 | `TOT_CHRG` | CURR | 13 |  | Total charge |
| 22 | `.INCLUDE` | &nbsp; | 0 |  | New price keys |
| 23 | `NRMSREB4` | CURR | 13 |  | 2008 Special Rebate |
| 24 | `NRMSREB6` | CURR | 13 |  | 2022 Special Rebate |
| 25 | `NRMSREB7` | CURR | 13 |  | 2023 Special Rebate |
| 26 | `NRMSREB8` | CURR | 13 |  | Special Fuel Rebate |
| 27 | `REB13` | CURR | 13 |  | 2013 Energy Saving Rebate-GST |
| 28 | `NRMSREB5` | CURR | 13 |  | R&R Special Rebate |
| 29 | `GFCREB` | CURR | 13 |  | CLP SME Subsidy (NRT) |
| 30 | `REB13_1_KWH` | DEC | 17 |  | 2013 ES Rebate (T1) - Unit |
| 31 | `REB13_2_KWH` | DEC | 17 |  | 2013 ES Rebate (T2) - Unit |
| 32 | `REB13_3_KWH` | DEC | 17 |  | 2013 ES Rebate (T3) - Unit |
| 33 | `REB13_1_TOT` | DEC | 17 |  | Total 2013 ES Rebate (T1) - Unit |
| 34 | `REB13_2_TOT` | DEC | 17 |  | Total 2013 ES Rebate (T2) - Unit |
| 35 | `REB13_3_TOT` | DEC | 17 |  | Total 2013 ES Rebate (T3) - Unit |
