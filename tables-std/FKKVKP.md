# `FKKVKP`

**Description:** Contract Account Header — FI-CA contract account master
**Category:** Standard SAP Table
**References:** 1503 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/fkkvkp/) — validated 2026-05-30, schema v1.0
**Schema fields:** 85 fields | **Data types:** CHAR(73), CUKY(1), CURR(1), DATS(7), NUMC(2), RAW(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `VKBEZ` | VKBEZ_KK | — | CHAR | 35 | 0 | Contract account name |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDATP` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAMP` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `FDZTG` | FDZTG_KK | — | NUMC | 2 | 0 | Additional Days for Cash Management |
| `STOPD` | STOPD_KK | — | DATS | 8 | 0 | Processing lock until |
| `QSZDT` | QSZDT | — | DATS | 8 | 0 | Validity Date for Withholding Tax Exemption Certificate |
| `GUID` | BUAG_GUID | — | RAW | 16 | 0 | Business Agreement GUID |
| `DDLAM` | DDLAM_KK | — | CURR | 13 | 2 | Direct Debit Limit |
| `DDLCU` | DDLCU_KK | TCURC | CUKY | 5 | 0 | Currency of Direct Debit Limit |
| `DDLNM` | DDLNM_KK | — | NUMC | 2 | 0 | Number of Months for Calculation of Direct Debit Limit |
| `INV_CYCLE_START` | CYCLE_STARTDATE_KK | — | DATS | 8 | 0 | Start Date of Billing Cycle in Contract Account |
| `INV_CHGDISC_X` | CHGDISC_X_KK | — | CHAR | 1 | 0 | Int: Charges and Discounts Exist for BP-CrtAcct Relations |
| `BPL_XPOCL` | BPL_XPOCL_KK | — | CHAR | 1 | 0 | Business Partner Lock for Postings/Clearing |
| `BPL_FDATE` | FDATE_KK | — | DATS | 8 | 0 | Lock valid from |
| `BPL_TDATE` | TDATE_KK | — | DATS | 8 | 0 | Lock valid to |
| `EXVKO` | EXVKO_KK | — | CHAR | 25 | 0 | Reference number for business partner |
| `OPBUK` | OPBUK_KK | TFK001G | CHAR | 4 | 0 | Company Code Group |
| `STDBK` | STDBK_KK | — | CHAR | 4 | 0 | Standard Company Code |
| `ABWRE` | ABWRE_KK | BUT000 | CHAR | 10 | 0 | Alternative Payer |
| `ABWRA` | ABWRA_KK | BUT000 | CHAR | 10 | 0 | Alternative Payee |
| `ABWMA` | ABWMA_KK | BUT000 | CHAR | 10 | 0 | Alternative dunning recipient |
| `EBVTY` | EBVTY_KK | — | CHAR | 4 | 0 | Bank Details ID for Incoming Payments |
| `ABVTY` | ABVTY_KK | — | CHAR | 4 | 0 | Bank Details ID for Outgoing Payments |
| `EZAWE` | EZAWE_KK | — | CHAR | 1 | 0 | Incoming Payment Method |
| `EZASP` | EZASP_OLD_KK | TFK008 | CHAR | 1 | 0 | Lock Reason for Incoming Payments |
| `AZAWE` | AZAWE_KK | — | CHAR | 5 | 0 | Outgoing Payment Methods |
| `AZASP` | AZASP_OLD_KK | TFK008 | CHAR | 1 | 0 | Lock Reason for Outgoing Payments |
| `EIGBV` | EIGBV_KK | — | CHAR | 25 | 0 | Own Bank Details |
| `VWNZA` | VWNZA_KK | — | CHAR | 1 | 0 | Create Where-Used List For Line Items |
| `LOEVM` | LOEVM_KK | — | CHAR | 1 | 0 | Mark Contract Account for Deletion |
| `ABWVK` | ABWVK_KK | FKKVK | CHAR | 12 | 0 | Alternative contract account for collective bills |
| `IKEY` | IKEY_KK | TFK056A | CHAR | 2 | 0 | Interest Key |
| `MAHNV` | MAHNV_KK | TFK047A | CHAR | 2 | 0 | Dunning Procedure |
| `MANSP` | MANSP_OLD_KK | TFK047S | CHAR | 1 | 0 | Dunning Lock Reason |
| `MGRUP` | MGRUP_KK | TFK047F | CHAR | 2 | 0 | Grouping fur Dunning Notices |
| `FDGRP` | FDGRP_KK | T035 | CHAR | 10 | 0 | Planning Group |
| `VKPBZ` | VKPBZ_KK | TFK002F | CHAR | 2 | 0 | Relationship of Business Partner to Contract Account |
| `ADRNB` | AD_ADDRNUM | — | CHAR | 10 | 0 | Address number |
| `VKONV` | VKONV_KK | FKKVK | CHAR | 12 | 0 | Contract account used for payment transactions |
| `GPARV` | GPARV_KK | BUT000 | CHAR | 10 | 0 | Business Partner Acting as Payer in Payment Transactions |
| `ADRRE` | ADRRE_KK | — | CHAR | 10 | 0 | Address Number for Alternative Payer |
| `ADRRA` | ADRRA_KK | — | CHAR | 10 | 0 | Address Number for Alternative Payee |
| `ADRMA` | ADRMA_KK | — | CHAR | 10 | 0 | Address number for alternative dunning notice recipient |
| `ABWRH` | ABWRH_KK | BUT000 | CHAR | 10 | 0 | Alternative Invoice Recipient |
| `ADRRH` | ADRRH_KK | — | CHAR | 10 | 0 | Address number for alternative bill recipient |
| `ADRJDC` | ADRJDC_KK | — | CHAR | 10 | 0 | Address Number for Jurisdiction Code Address |
| `BEGRU` | BEGRU | — | CHAR | 4 | 0 | Authorization Group |
| `TOGRU` | TOGRU_KK | TFK043 | CHAR | 4 | 0 | Tolerance group for contract account |
| `STOPG` | STOPG_KK | TFK001S | CHAR | 1 | 0 | Reason for Processing Lock |
| `TXJCD` | TXJCD_NOCD_KK | — | CHAR | 15 | 0 | Jurisdiction for Tax Calculation - Tax Jurisdiction Code |
| `COPRC` | COPRC_KK | TFK070B | CHAR | 4 | 0 | Correspondence Variant |
| `VBUND` | RASSC | — | CHAR | 6 | 0 | Company ID of trading partner |
| `CCARD_ID` | CCID_IN_KK | — | CHAR | 6 | 0 | Payment Card ID for Incoming Payments |
| `CCARD_OUT` | CCID_OUT_KK | — | CHAR | 6 | 0 | Payment Card ID for Outgoing Payments |
| `UEBTR` | XUEBTR_KK | — | CHAR | 1 | 0 | Items Transferred To Another Account |
| `DEF_REC` | DEF_CORR_PARTNER_KK | BUT000 | CHAR | 10 | 0 | Alternative Correspondence Recipient for Standard Case |
| `DEF_REC_IND` | DEF_CORR_ACKEY_KK | TFK070L | CHAR | 4 | 0 | FI-CA correspondence - activity key |
| `QSSKZ_A` | QSSKZ_A_KK | — | CHAR | 2 | 0 | Witholding Tax Code For Outgoing Payments |
| `QSSKZ_E` | QSSKZ_E_KK | — | CHAR | 2 | 0 | Withholding Tax Code For Incoming Payments |
| `QSZNR` | QSZNR | — | CHAR | 10 | 0 | Certificate Number of the Withholding Tax Exemption |
| `CORR_MAHNV` | CORR_MAHNV_KK | — | CHAR | 2 | 0 | Correspondence Dunning Procedure |
| `FITYP` | J_1AFITP_D | J_1AFITPV | CHAR | 2 | 0 | Tax type |
| `PROVINCE` | REGIO | T005S | CHAR | 3 | 0 | Region (State, Province, County) |
| `COUNTY` | COUNC | T005E | CHAR | 3 | 0 | County Code |
| `VERTYP` | VERTYP_KK | TFK111 | CHAR | 4 | 0 | Clearing Category For Clearing Postings |
| `AUGRS_DEF` | AUGRS_DEF_KK | — | CHAR | 1 | 0 | Clearing Restriction |
| `LANDL` | LANDL_KK | T005 | CHAR | 3 | 0 | Country Supplied (for Tax Notifications) |
| `BUPLA` | BUPLA | J_1BBRANCH | CHAR | 4 | 0 | Business Place |
| `BPTAXTYPE1` | BPTAXTYPE1 | — | CHAR | 4 | 0 | Tax Number Type 1 for Business Partner |
| `BPTAXTYPE2` | BPTAXTYPE2 | — | CHAR | 4 | 0 | Tax Number type 2 for Business Partner |
| `PERSR` | PERSR_KK | BUT000 | CHAR | 10 | 0 | Clerk Responsible |
| `INV_CATEGORY` | INV_CATEGORY_KK | TFK2604 | CHAR | 4 | 0 | Invoicing Category |
| `DDLXG` | DDLXG_KK | — | CHAR | 1 | 0 | Rolling Calculation of Direct Debit Limit |
| `CMGRP` | CMGRP_CM_KK | — | CHAR | 2 | 0 | Collection Management: Master Data Group |
| `STRAT` | STRAT_CM_KK | — | CHAR | 2 | 0 | Collection Strategy |
| `CPERS` | CPERS_CM_KK | — | CHAR | 10 | 0 | Collections Contact Person |
| `BPCL_SUCC` | BPCL_SUCC_KK | — | CHAR | 1 | 0 | Duplicate Processing: Predecessor/Successor Business Partner |
| `INV_SCHEDULE` | INV_SCHEDULE_KK | TFK2606 | CHAR | 4 | 0 | Selection Characteristic for Scheduling |
| `INV_CYCLE` | CYCLE_KK | TFK2607 | CHAR | 4 | 0 | Billing Cycle |
| `INV_CYCLE_RULE` | CYCLE_RULE_KK | — | CHAR | 4 | 0 | Field Is Not Used - CHAR4 |
| `INV_CYCLE_DAY` | CYCLE_DAY_KK | — | CHAR | 2 | 0 | Day of Period End |
| `INV_CYCLE_MONTH` | NOT_USED_CHAR2_KK | — | CHAR | 2 | 0 | Field Is Not Used - CHAR2 |
| `MNDID` | SEPA_MNDID | — | CHAR | 35 | 0 | Unique Referene to Mandate per Payment Recipient |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABWMA` | SYST | MANDT | BUT000 |  | |
| `ABWMA` | FKKVKP | ABWMA | BUT000 |  | |
| `ABWRA` | SYST | MANDT | BUT000 |  | |
| `ABWRA` | FKKVKP | ABWRA | BUT000 |  | |
| `ABWRE` | SYST | MANDT | BUT000 |  | |
| `ABWRE` | FKKVKP | ABWRE | BUT000 |  | |
| `ABWRH` | SY | MANDT | BUT000 |  | |
| `ABWRH` | FKKVKP | ABWRH | BUT000 |  | |
| `ABWVK` | SY | MANDT | FKKVK |  | |
| `ABWVK` | FKKVKP | ABWVK | FKKVK |  | |
| `AZASP` | FKKVKP | AZASP | TFK008 |  | |
| `AZASP` | SYST | MANDT | TFK008 |  | |
| `BUPLA` | SYST | MANDT | J_1BBRANCH |  | |
| `BUPLA` | FKKVKP | STDBK | J_1BBRANCH |  | |
| `BUPLA` | FKKVKP | BUPLA | J_1BBRANCH |  | |
| `COPRC` | SY | MANDT | TFK070B |  | |
| `COPRC` | FKKVKP | COPRC | TFK070B |  | |
| `COUNTY` | FKKVKP | PROVINCE | T005E |  | |
| `COUNTY` | FKKVKP | COUNTY | T005E |  | |
| `COUNTY` | SY | MANDT | T005E |  | |
| `COUNTY` | * |  | T005E |  | |
| `DDLCU` | FKKVKP | MANDT | TCURC |  | |
| `DDLCU` | FKKVKP | DDLCU | TCURC |  | |
| `DEF_REC` | SYST | MANDT | BUT000 |  | |
| `DEF_REC` | FKKVKP | DEF_REC | BUT000 |  | |
| `DEF_REC_IND` | FKKVKP | DEF_REC_IND | TFK070L |  | |
| `DEF_REC_IND` | SY | MANDT | TFK070L |  | |
| `EZASP` | SYST | MANDT | TFK008 |  | |
| `EZASP` | FKKVKP | EZASP | TFK008 |  | |
| `FDGRP` | FKKVKP | FDGRP | T035 |  | |
| `FDGRP` | SY | MANDT | T035 |  | |
| `FITYP` | SY | MANDT | J_1AFITPV |  | |
| `FITYP` | FKKVKP | FITYP | J_1AFITPV |  | |
| `GPART` | FKKVKP | GPART | BUT000 |  | |
| `GPART` | FKKVKP | MANDT | BUT000 |  | |
| `GPARV` | SYST | MANDT | BUT000 |  | |
| `GPARV` | FKKVKP | GPARV | BUT000 |  | |
| `IKEY` | SY | MANDT | TFK056A |  | |
| `IKEY` | FKKVKP | IKEY | TFK056A |  | |
| `INV_CATEGORY` | SYST | MANDT | TFK2604 |  | |
| `INV_CATEGORY` | FKKVKP | INV_CATEGORY | TFK2604 |  | |
| `INV_CYCLE` | SYST | MANDT | TFK2607 |  | |
| `INV_CYCLE` | FKKVKP | INV_CYCLE | TFK2607 |  | |
| `INV_SCHEDULE` | FKKVKP | INV_SCHEDULE | TFK2606 |  | |
| `INV_SCHEDULE` | SYST | MANDT | TFK2606 |  | |
| `LANDL` | SYST | MANDT | T005 |  | |
| `LANDL` | FKKVKP | LANDL | T005 |  | |
| `MAHNV` | FKKVKP | MAHNV | TFK047A |  | |
| `MAHNV` | SY | MANDT | TFK047A |  | |
| `MANDT` | FKKVKP | MANDT | T000 |  | |
| `MANSP` | SY | MANDT | TFK047S |  | |
| `MANSP` | FKKVKP | MANSP | TFK047S |  | |
| `MGRUP` | SY | MANDT | TFK047F |  | |
| `MGRUP` | FKKVKP | MGRUP | TFK047F |  | |
| `OPBUK` | SYST | MANDT | TFK001G |  | |
| `OPBUK` | FKKVKP | OPBUK | TFK001G |  | |
| `PERSR` | SYST | MANDT | BUT000 |  | |
| `PERSR` | FKKVKP | PERSR | BUT000 |  | |
| `PROVINCE` | SY | MANDT | T005S |  | |
| `PROVINCE` | * |  | T005S |  | |
| `PROVINCE` | FKKVKP | PROVINCE | T005S |  | |
| `STOPG` | SY | MANDT | TFK001S |  | |
| `STOPG` | FKKVKP | STOPG | TFK001S |  | |
| `TOGRU` | SY | MANDT | TFK043 |  | |
| `TOGRU` | FKKVKP | TOGRU | TFK043 |  | |
| `VERTYP` | SY | MANDT | TFK111 |  | |
| `VERTYP` | FKKVKP | VERTYP | TFK111 |  | |
| `VKONT` | FKKVKP | MANDT | FKKVK |  | |
| `VKONT` | FKKVKP | VKONT | FKKVK |  | |
| `VKONV` | SYST | MANDT | FKKVK |  | |
| `VKONV` | FKKVKP | VKONV | FKKVK |  | |
| `VKPBZ` | FKKVKP | MANDT | TFK002F |  | |
| `VKPBZ` | FKKVKP | VKPBZ | TFK002F |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ADRNB`, `EZAWE`, `GPART`, `KTOKL`, `SENDCONTROL_GP`, `VKONT`, `ZAHLKOND`, `ZZPREM_FUNC`, `ZZTRADE_CAT`, `ZZTRADE_CLASS`, `abwrh`, `abwvk`, `ebvty`, `erdat`, `ezawe`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ADRNB`, `VKONT`, `abwvk`, `ebvty`, `erdat`, `ezawe`, `gpart`, `ktokl`, `loevm`, `vkont`, `zahlkond`, `zzacctmngr`

## Join Paths
- `FKKVKP.GPART` → `BUT000.PARTNER` — CA → Business Partner
- `FKKVKP.VKONT` → `DFKKOP.VKONTO` — CA → Open Items
- `FKKVKP.VKONT` → `FKKVK.VKONT` — CA Header
- `FKKVKP.VKONT` → `FKK_SEC.VKONT` — CA → Security

## Programs Using This Table
- `z_bapi_get_bp_id.txt`
- `z_bapi_get_duedate.txt`
- `z_bapi_mcrs_real_time_refund.txt`
- `z_iscs_get_ca_by_bp.txt`
- `z_isu_sample_z705.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zisbi0110.txt`
- `zisbi0142.txt`
- `zisbi0189.txt`
- `ziscs0807.txt`
- `ziscs_pc_customer_det.txt`
- `ziscsami_get_contact_info.txt`
- `ziscseec_get_eher_settings.txt`
- `zisdm0369_ssr_f01_mod.txt`
- `zisfi0039.txt`
- `zisfi0116_test3.txt`
- `zisfi0207.txt`
- `zisfi0219.txt`
- `zisfi0336.txt`
- `zrcs_remove_cons_af.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_