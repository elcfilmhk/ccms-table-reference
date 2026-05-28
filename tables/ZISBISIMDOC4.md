# ZISBISIMDOC4
**Description:** Leftout figure for RBI25
**Total Fields:** 34
**Key Fields:** MANDT, PERIOD, VKONT, LFDNR

## Programs Using This Table
- `zisbi0062_1`
- `zisbi0062_1t`
- `zisbi0062b`
- `zisbi0062c`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PERIOD` | CHAR | 6 | 🔑 | Period (MMYYYY) |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `LFDNR` | NUMC | 3 | 🔑 | Sequence Number (Internal Use Only) |
| 5 | `.INCLUDE` | &nbsp; | 0 |  | Leftout figures (in text format) |
| 6 | `DAY_OF_LOUT` | CHAR | 4 |  | Days of leftout |
| 7 | `TOT_KWH_LOUT` | CHAR | 17 |  | Total consumption leftout |
| 8 | `CONS_CHRG_LOUT` | CHAR | 17 |  | Consumption charge leftout |
| 9 | `DMD_CHRG_LOUT` | CHAR | 17 |  | Demand charge leftout |
| 10 | `HLFR_LOUT` | CHAR | 17 |  | HLFR leftout |
| 11 | `STB_CHRG_LOUT` | CHAR | 17 |  | Standby charge leftout |
| 12 | `BASIC_CHRG_LOUT` | CHAR | 17 |  | Baisc charge leftout |
| 13 | `FUEL_CL_LOUT` | CHAR | 17 |  | Fuel clause leftout |
| 14 | `REBATE_LOUT` | CHAR | 17 |  | Rebate leftout |
| 15 | `MREBATE_LOUT` | CHAR | 17 |  | 2008 special rebate leftout |
| 16 | `R2007_1_LOUT` | CHAR | 17 |  | 2007 special rebate 1 leftout |
| 17 | `R2007_2_LOUT` | CHAR | 17 |  | 2007 special rebate 2 leftout |
| 18 | `NRMSREB4_LOUT` | CHAR | 17 |  | 2008 special rebate leftout |
| 19 | `NRMSREB6_LOUT` | CHAR | 17 |  | 2022 special rebate leftout |
| 20 | `NRMSREB7_LOUT` | CHAR | 17 |  | 2023 special ES rebate leftout |
| 21 | `NRMSREB8_LOUT` | CHAR | 17 |  | Special fuel rebate leftout |
| 22 | `REB13_LOUT` | CHAR | 17 |  | 2013 ES rebate leftout |
| 23 | `NRMSREB5_LOUT` | CHAR | 17 |  | R&R special rebate leftout |
| 24 | `TOT_CHRG_LOUT` | CHAR | 17 |  | Total charge leftout |
| 25 | `GFCREB_LOUT` | CHAR | 17 |  | CLP SME Subsidy (NRT) leftout |
| 26 | `REB13_1_KWH_LOUT` | CHAR | 17 |  | 2013 ES Rebate (T1) - Unit leftout |
| 27 | `REB13_2_KWH_LOUT` | CHAR | 17 |  | 2013 ES Rebate (T2) - Unit leftout |
| 28 | `REB13_3_KWH_LOUT` | CHAR | 17 |  | 2013 ES Rebate (T3) - Unit leftout |
| 29 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 30 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 31 | `APDAT` | DATS | 8 |  | Date Approved |
| 32 | `APNAM` | CHAR | 12 |  | Approver Name |
| 33 | `DELDAT` | DATS | 8 |  | Deletion date |
| 34 | `DELNAM` | CHAR | 12 |  | Deleted by |
