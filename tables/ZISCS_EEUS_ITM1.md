# ZISCS_EEUS_ITM1
**Description:** EEUS Application Item Table (Retrofit Air-conditioner)
**Total Fields:** 35
**Key Fields:** MANDT, EEUS_APPLN, SERIAL_NO, RETROFIT_NEW

## Programs Using This Table
- `ziscs0722`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EEUS_APPLN` | CHAR | 10 | 🔑 | Sales Document |
| 3 | `SERIAL_NO` | NUMC | 3 | 🔑 | Serial Number |
| 4 | `RETROFIT_NEW` | CHAR | 2 | 🔑 | Retrofit/ New |
| 5 | `IS_RET_NEW` | CHAR | 1 |  | Retrofit or New Installation |
| 6 | `MATNR` | CHAR | 18 |  | Material Number |
| 7 | `ZMATNR` | CHAR | 18 |  | CLP Material Number |
| 8 | `PROD_MOD` | CHAR | 60 |  | Model Number |
| 9 | `VENDOR_NAM` | CHAR | 300 |  | Retailer / Vendor |
| 10 | `INVOICE_NO` | CHAR | 20 |  | Invoice Number |
| 11 | `DAT_OF_PUR` | DATS | 8 |  | Date of Purchase |
| 12 | `EEUS_PRD_TYP` | CHAR | 9 |  | Material Group |
| 13 | `UNIT_PRICE` | CURR | 13 |  | Unit Price |
| 14 | `SSHOP_O_NO` | CHAR | 15 |  | CLP Smart Shopping Order Number |
| 15 | `ENERGY_LABEL` | CHAR | 2 |  | Energy Label |
| 16 | `COOLING_SYS` | CHAR | 2 |  | Cooling System |
| 17 | `BRAND` | CHAR | 100 |  | Brand |
| 18 | `TONNAGE` | QUAN | 9 |  | Tonnage of A/c |
| 19 | `COOLING_CAP` | QUAN | 12 |  | Cooling Capacity (kW) |
| 20 | `AC_FLOW_SYS` | CHAR | 2 |  | A/c Flow System |
| 21 | `AC_SYST_SUB_CAT` | CHAR | 2 |  | A/c System Sub Category |
| 22 | `HORSE_POW` | QUAN | 9 |  | Horse Power |
| 23 | `PURC_QUAN` | DEC | 8 |  | Purchase Quantity |
| 24 | `RATED_IN_POW` | QUAN | 13 |  | Rated Input Power (kW) |
| 25 | `ANN_OPR_HRS` | DEC | 10 |  | Annual Opertaing hours |
| 26 | `AVG_ANN_LOAD_FAC` | NUMC | 3 |  | Average Annual Load Factor (%) |
| 27 | `EST_ANN_ENE_CONS` | QUAN | 17 |  | Estimated Annual Energy Consumption |
| 28 | `EST_ANN_ENE_SAVE` | QUAN | 17 |  | Estimated Annual Energy Saving |
| 29 | `INSTALLED_LOC` | CHAR | 100 |  | Installed Location |
| 30 | `RET_OLD_QUAN` | DEC | 8 |  | Retrofit Old Quantity |
| 31 | `PRIORITY` | CHAR | 1 |  | Priority |
| 32 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 33 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 34 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 35 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
