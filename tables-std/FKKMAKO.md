# `FKKMAKO`

**Description:** Direct Debit Agreement — payment method setup
**Category:** Standard SAP Table
**References:** 32 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/fkkmako/) — validated 2026-05-30, schema v1.0
**Schema fields:** 69 fields | **Data types:** CHAR(46), CUKY(1), CURR(6), DATS(8), DEC(4), NUMC(4)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `AUSDT` | AUSDT_KK | — | DATS | 8 | 0 | Date of issue |
| `MDRKD` | MDRKD_KK | — | DATS | 8 | 0 | Execution Date of Dunning Notice |
| `MAHNV` | MAHNV_KK | — | CHAR | 2 | 0 | Dunning Procedure |
| `MGRUP` | MGRUP_KK | — | CHAR | 2 | 0 | Grouping fur Dunning Notices |
| `VKONTGRP` | VKGRP_CM_KK | — | CHAR | 12 | 0 | Collection Management: Contract Account Group |
| `VTREFGRP` | VTGRP_CM_KK | — | CHAR | 20 | 0 | Collection Management: Contract Group |
| `ITEMGRP` | ITEMGRP_CM_KK | — | DEC | 15 | 0 | Closed Item Group for Dunning |
| `ITEMGRP_LAST` | ITEMGRP_LAST_CM_KK | — | DEC | 15 | 0 | Item Group in Last Dunning Notice |
| `GRPFIELD` | GRPFIELD_CM_KK | — | CHAR | 12 | 0 | Grouping Field for Dunning |
| `GRPFIELD_LAST` | GRPFIELD_LAST_CM_KK | — | CHAR | 12 | 0 | Grouping Field in Last Dunning Notice |
| `STRAT` | STRAT_CM_KK | TFK047X | CHAR | 2 | 0 | Collection Strategy |
| `STEP` | STEP_CM_KK | TFK047U | CHAR | 4 | 0 | Collection Step |
| `STEP_LAST` | STEP_LAST_CM_KK | TFK047U | CHAR | 4 | 0 | Collection Step of Last Dunning |
| `STEP_REPLACED` | STEP_REPL_CM_KK | TFK047U | CHAR | 4 | 0 | Replaced Collection Step (Capacity Restriction) |
| `STRAT_CHAMP` | STRAT_CHAMP_CM_KK | — | CHAR | 2 | 0 | Champion Collection Strategy |
| `TESTS` | TESTS_CM_KK | — | CHAR | 10 | 0 | Collection Management: Test Series for Collection Strategies |
| `LIMITED` | LIMITED_CM_KK | — | CHAR | 1 | 0 | Capacity for Dunning Activity Restricted |
| `RELEA` | RELEA_CM_KK | — | CHAR | 1 | 0 | Release Dunning |
| `RELDATE` | RELDATE_CM_KK | — | DATS | 8 | 0 | Latest Release Date |
| `RELGROUP` | RELGROUP_CM_KK | — | CHAR | 4 | 0 | Release Group |
| `NEXDT` | NEXDT_CM_KK | — | DATS | 8 | 0 | Date of Next Dunning |
| `OPBUK` | OPBUK_KK | — | CHAR | 4 | 0 | Company Code Group |
| `STDBK` | BUKRS | — | CHAR | 4 | 0 | Company Code |
| `GSBER` | GSBER | — | CHAR | 4 | 0 | Business Area |
| `SPART` | SPART | — | CHAR | 2 | 0 | Division |
| `VTREF` | VTREF_KK | — | CHAR | 20 | 0 | Reference Specifications from Contract |
| `SUBAP` | SUBAP_KK | — | CHAR | 1 | 0 | Subapplication in Contract Accounts Receivable and Payable |
| `VKNT1` | VKNT1_KK | — | CHAR | 12 | 0 | Leading Contract Account in Dunning |
| `ABWMA` | ABWMA_KK | — | CHAR | 10 | 0 | Alternative dunning recipient |
| `MAHNS` | MAHNS_KK | — | NUMC | 2 | 0 | Dunning Level |
| `MSTYP` | MSTYP_KK | TFK047G | CHAR | 2 | 0 | Dunning Level Category |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `MSALM` | MSALM_KK | — | CURR | 13 | 2 | Dunning Balance |
| `MSALH` | UNUSED_KK | — | DEC | 13 | 2 | Not used (formerly dunned amount in local currency) |
| `RSALM` | RSALM_KK | — | CURR | 13 | 2 | Total of Dunning Reductions |
| `CHGID` | CHGID_KK | — | CHAR | 2 | 0 | Charges Schedule |
| `MGE1M` | MGE1M_KK | — | CURR | 13 | 2 | Dun. charge 1 |
| `MG1BL` | MG1BL_KK | — | CHAR | 12 | 0 | Doc no. for charge 1 |
| `MG1TY` | MG1TY_KK | — | CHAR | 2 | 0 | Charge type f. charge 1 |
| `POST1` | CPOST_KK | — | CHAR | 1 | 0 | Posting Key for Charges |
| `MGE2M` | MGE2M_KK | — | CURR | 13 | 2 | Dun.charge 2 |
| `MG2BL` | MG2BL_KK | — | CHAR | 12 | 0 | Doc number for charge 2 |
| `MG2TY` | MG2TY_KK | — | CHAR | 2 | 0 | Charge type f. charge 2 |
| `POST2` | CPOST_KK | — | CHAR | 1 | 0 | Posting Key for Charges |
| `MGE3M` | MGE3M_KK | — | CURR | 13 | 2 | Dun.charge 3 |
| `MG3BL` | MG3BL_KK | — | CHAR | 12 | 0 | Doc number for charge 3 |
| `MG3TY` | MG3TY_KK | — | CHAR | 2 | 0 | Charge type f. charge 3 |
| `POST3` | CPOST_KK | — | CHAR | 1 | 0 | Posting Key for Charges |
| `MINTM` | MINTM_KK | — | CURR | 13 | 2 | Dunning interest in transaction currency |
| `MIBEL` | MIBEL_KK | — | CHAR | 12 | 0 | Doc no. of interest posting |
| `BONIT` | BONDU_KK | — | NUMC | 4 | 0 | Creditworthiness |
| `XMSTO` | XMSTO_KK | — | CHAR | 1 | 0 | Dunning Notice Reversed |
| `NRZAS` | NRZAS_KK | — | CHAR | 12 | 0 | Payment Form Number |
| `XINFO` | XINFG_KK | — | CHAR | 1 | 0 | Group Not Due For Dunning/Information Only |
| `FRDAT` | FRDAT_KK | — | DATS | 8 | 0 | Payment Target in Dunning Notice |
| `COKEY` | COKEY_KK | — | CHAR | 36 | 0 | Correspondence key |
| `XCOLL` | XCOLL_KK | — | CHAR | 1 | 0 | Submission to Collection Agency |
| `RFZAS` | RFZAS_KK | — | CHAR | 30 | 0 | External key payment form |
| `TODAT` | TODAT_KK | — | DATS | 8 | 0 | Date Up to Which Payments Were Considered (Dunning) |
| `STAKZ` | STAKZ_KK | — | CHAR | 1 | 0 | Type of statistical item |
| `CHECKBOX` | CKBOX_KK | — | CHAR | 1 | 0 | Technical Checkbox |
| `SUCPC` | SUCPC_KK | — | DEC | 5 | 2 | Success Percentage Rate Determined for Dunning |
| `ABWTP` | ABWTP_KK | — | CHAR | 1 | 0 | Category of substitute document in FI-CA |
| `ABWBL` | ABWBL_KK | — | CHAR | 12 | 0 | Number of the substitute FI-CA document |
| `STUDT` | STUDT_MAX_KK | — | DATS | 8 | 0 | Maximum Deferral Date for Related Items |
| `SUCDT` | SUCDT_KK | — | DATS | 8 | 0 | Date of Success Valuation |
| `SCDST` | SCDST_KK | — | CHAR | 1 | 0 | Status of Success Valuation |
| `SCORE` | SCORE_CM_KK | — | NUMC | 4 | 0 | Valuation Number |
| `RANK` | RANK_CM_KK | — | NUMC | 4 | 0 | Ranking |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `GPART` | FKKMAKO | MANDT | BUT000 |  | |
| `GPART` | FKKMAKO | GPART | BUT000 |  | |
| `MSTYP` | FKKMAKO | MANDT | TFK047G |  | |
| `MSTYP` | FKKMAKO | MSTYP | TFK047G |  | |
| `STEP` | FKKMAKO | MANDT | TFK047U |  | |
| `STEP` | FKKMAKO | STEP | TFK047U |  | |
| `STEP_LAST` | FKKMAKO | MANDT | TFK047U |  | |
| `STEP_LAST` | FKKMAKO | STEP_LAST | TFK047U |  | |
| `STEP_REPLACED` | FKKMAKO | STEP_REPLACED | TFK047U |  | |
| `STEP_REPLACED` | FKKMAKO | MANDT | TFK047U |  | |
| `STRAT` | FKKMAKO | MANDT | TFK047X |  | |
| `STRAT` | FKKMAKO | STRAT | TFK047X |  | |
| `WAERS` | FKKMAKO | MANDT | TCURC |  | |
| `WAERS` | FKKMAKO | WAERS | TCURC |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ausdt`, `gpart`, `laufd`, `laufi`, `mazae`, `vkont`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `mazae`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_check_dunning_hist.txt`
- `zisbi0097.txt`
- `zisbw0014.txt`
- `ziscs_migration_custcontact_m3.txt`
- `ziscs_migration_custcontact_m4.txt`
- `zisdm0282.txt`
- `zisfi0025.txt`
- `zisfi0040.txt`
- `zisfi0044.txt`
- `zisfi0097.txt`
- `zisfi0101.txt`
- `zisfi0106.txt`
- `zisfi0117.txt`
- `zisfi0120.txt`
- `zisfi0123.txt`
- `zisfi0139.txt`
- `zisfi0146.txt`
- `zisfi0156.txt`
- `zisfi0167.txt`
- `zisfi0272.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_