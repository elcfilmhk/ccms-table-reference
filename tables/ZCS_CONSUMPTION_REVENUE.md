# ZCS_CONSUMPTION_REVENUE
**Description:** Consumption & revenue
**Total Fields:** 66
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0062_1`
- `zisbi0062_1t`
- `zisbi0071`
- `zisbifi_recon`
- `ziscs0086a`
- `ziscs0086b`
- `ziscs0086c`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BATCH_DATE` | CHAR | 8 |  | Batch run date |
| 2 | `PRINT_DOC` | CHAR | 12 |  | Print document |
| 3 | `POSTING_DATE` | CHAR | 8 |  | Posting date |
| 4 | `CONTRACT_ACC` | CHAR | 12 |  | Contract account |
| 5 | `PARTNER_NO` | CHAR | 10 |  | Business partner |
| 6 | `FUEL_CLAUSE` | CHAR | 17 |  | Fuel clasue |
| 7 | `TARIFF_CHARGE` | CHAR | 17 |  | Consumption charge |
| 8 | `CONSUMPTION` | CHAR | 17 |  | Consumption |
| 9 | `REBATE` | CHAR | 17 |  | Rebate |
| 10 | `SPECIAL_REBATE` | CHAR | 17 |  | Special rebate |
| 11 | `ENERGY_CHARGE` | CHAR | 17 |  | kWH charge |
| 12 | `DEMAND_CHARGE` | CHAR | 17 |  | kVA charge |
| 13 | `HLFR_CHARGE` | CHAR | 17 |  | HLFR charge |
| 14 | `STB_CHARGE` | CHAR | 17 |  | Standby charge |
| 15 | `INDUSTRY_GROUP` | CHAR | 1 |  | Industry group |
| 16 | `RATE_CATEGORY` | CHAR | 10 |  | Rate category |
| 17 | `LAST_ARDATE` | CHAR | 8 |  | Last actual reading date |
| 18 | `CURR_ARDATE` | CHAR | 8 |  | Current actual reading date |
| 19 | `CUR_CONSUMPTION` | CHAR | 17 |  | Current consumption |
| 20 | `CUR_FUEL_CLAUSE` | CHAR | 17 |  | Current fuel clause |
| 21 | `CUR_REBATE` | CHAR | 17 |  | Current rebate |
| 22 | `CUR_SP_REBATE` | CHAR | 17 |  | Current special rebate |
| 23 | `CUR_MISC_REBATE` | CHAR | 17 |  | Current miscellaneou rebate |
| 24 | `BILL_TOTAL` | CHAR | 17 |  | Invoice amount |
| 25 | `SMALL_BILL` | CHAR | 1 |  | Indicator: Small bill |
| 26 | `PAY_METH` | CHAR | 2 |  | Payment method |
| 27 | `ADJ_ENERGY_CHRG` | CHAR | 17 |  | Adjusted energy charge |
| 28 | `ADJ_DEMAND_CHRG` | CHAR | 17 |  | Adjusted demand charge |
| 29 | `ADJ_HLFR` | CHAR | 17 |  | Adjusted HLFR charge |
| 30 | `ADJ_STB_CHRG` | CHAR | 17 |  | Adjusted standby charge |
| 31 | `ADJ_CONSUMPTION` | CHAR | 17 |  | Adjusted consumption |
| 32 | `ADJ_FUEL_CLAUSE` | CHAR | 17 |  | Adjusted fuel clause |
| 33 | `ADJ_REBATE` | CHAR | 17 |  | Adjusted rebate |
| 34 | `ADJ_SP_REBATE` | CHAR | 17 |  | Adjusted special rebate |
| 35 | `ADJ_MISC_REBATE` | CHAR | 17 |  | Adjusted miscellaneous rebate |
| 36 | `BILL_TYPE` | CHAR | 2 |  | Bill type |
| 37 | `CUR_2007_MSCREB1` | CHAR | 17 |  | Current 2007 miscellaneous rebate 1 |
| 38 | `CUR_2007_MSCREB2` | CHAR | 17 |  | Current 2007 miscellaneous rebate 2 |
| 39 | `ADJ_2007_MSCREB1` | CHAR | 17 |  | Adjusted 2007 miscellaneous rebate 1 |
| 40 | `ADJ_2007_MSCREB2` | CHAR | 17 |  | Adjusted 2007 miscellaneous rebate 2 |
| 41 | `CUR_NRMSREB4` | CHAR | 17 |  | Current 2008 miscellaneous rebate |
| 42 | `ADJ_NRMSREB4` | CHAR | 17 |  | Adjusted 2008 miscellaneous rebate |
| 43 | `CUR_NRMSREB6` | CHAR | 17 |  | Current 2022 miscellaneous rebate |
| 44 | `ADJ_NRMSREB6` | CHAR | 17 |  | Adjusted 2022 miscellaneous rebate |
| 45 | `CUR_NRMSREB7` | CHAR | 17 |  | Current 2023 Special energy saving rebate |
| 46 | `ADJ_NRMSREB7` | CHAR | 17 |  | Adjusted 2023 Special energy saving rebate |
| 47 | `CUR_NRMSREB8` | CHAR | 17 |  | Current Special fuel rebate |
| 48 | `ADJ_NRMSREB8` | CHAR | 17 |  | Adjusted Special fuel rebate |
| 49 | `CUR_REB13` | CHAR | 17 |  | Current 2013 Energy saving rebate |
| 50 | `ADJ_REB13` | CHAR | 17 |  | Adjusted 2013 Energy saving rebate |
| 51 | `CUR_NRMSREB5` | CHAR | 17 |  | Current R&R special rebate |
| 52 | `ADJ_NRMSREB5` | CHAR | 17 |  | Adjusted R&R special rebate |
| 53 | `CUR_GFCREB` | CHAR | 17 |  | Current CLP SME Subsidy (NRT) |
| 54 | `ADJ_GFCREB` | CHAR | 17 |  | Adjusted CLP SME Subsidy (NRT) |
| 55 | `CUR_REB13_1_KWH` | CHAR | 17 |  | Current 2013 ES Rebate (T1) - Unit |
| 56 | `ADJ_REB13_1_KWH` | CHAR | 17 |  | Adjusted 2013 ES Rebate (T1) - Unit |
| 57 | `CUR_REB13_2_KWH` | CHAR | 17 |  | Current 2013 ES Rebate (T2) - Unit |
| 58 | `ADJ_REB13_2_KWH` | CHAR | 17 |  | Adjusted 2013 ES Rebate (T2) - Unit |
| 59 | `CUR_REB13_3_KWH` | CHAR | 17 |  | Current 2013 ES Rebate (T3) - Unit |
| 60 | `ADJ_REB13_3_KWH` | CHAR | 17 |  | Adjusted 2013 ES Rebate (T3) - Unit |
| 61 | `CUR_REB13_1_TOT` | CHAR | 17 |  | Total Current 2013 ES Rebate (T1) - Unit |
| 62 | `ADJ_REB13_1_TOT` | CHAR | 17 |  | Total Adjusted 2013 ES Rebate (T1) - Unit |
| 63 | `CUR_REB13_2_TOT` | CHAR | 17 |  | Total Current 2013 ES Rebate (T2) - Unit |
| 64 | `ADJ_REB13_2_TOT` | CHAR | 17 |  | Total Adjusted 2013 ES Rebate (T2) - Unit |
| 65 | `CUR_REB13_3_TOT` | CHAR | 17 |  | Total Current 2013 ES Rebate (T3) - Unit |
| 66 | `ADJ_REB13_3_TOT` | CHAR | 17 |  | Total Adjusted 2013 ES Rebate (T3) - Unit |
