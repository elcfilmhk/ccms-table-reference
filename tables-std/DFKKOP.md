# `DFKKOP`

**Description:** CA Open Item — open item line in FI-CA
**Category:** Standard SAP Table
**References:** 951 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkop/) — validated 2026-05-30, schema v1.0
**Schema fields:** 141 fields | **Data types:** CHAR(95), CUKY(3), CURR(19), DATS(12), DEC(2), NUMC(10)

## Key Fields
`BUKRS` | `VKONT` | `PERNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BUKRS` | BUKRS | — | CHAR | 4 | 0 | Company Code |
| `GSBER` | GSBER | — | CHAR | 4 | 0 | Business Area |
| `BUPLA` | BUPLA | J_1BBRANCH | CHAR | 4 | 0 | Business Place |
| `SEGMENT` | SEGMT_KK | — | CHAR | 10 | 0 | Segment for Segmental Reporting |
| `PRCTR` | PRCTR | — | CHAR | 10 | 0 | Profit Center |
| `AUGST` | AUGST_KK | — | CHAR | 1 | 0 | Clearing status |
| `GPART` | GPART_KK | — | CHAR | 10 | 0 | Business Partner Number |
| `VTREF` | VTREF_KK | — | CHAR | 20 | 0 | Reference Specifications from Contract |
| `VTPOS` | VTPOS_KK | — | NUMC | 6 | 0 | Contract: Item Number |
| `VTRE2` | VTRE2_KK | — | CHAR | 20 | 0 | Additional Reference Information |
| `VKONT` | VKONT_KK | — | CHAR | 12 | 0 | Contract Account Number |
| `ABWBL` | ABWBL_KK | — | CHAR | 12 | 0 | Number of the substitute FI-CA document |
| `ABWTP` | ABWTP_KK | — | CHAR | 1 | 0 | Category of substitute document in FI-CA |
| `ABWKT` | ABWVK_KK | — | CHAR | 12 | 0 | Alternative contract account for collective bills |
| `APPLK` | APPLK_KK | — | CHAR | 1 | 0 | Application area |
| `HVORG` | HVORG_KK | — | CHAR | 4 | 0 | Main Transaction for Line Item |
| `TVORG` | TVORG_KK | — | CHAR | 4 | 0 | Subtransaction for Document Item |
| `KOFIZ` | KOFIZ_KK | — | CHAR | 2 | 0 | Account Determination ID |
| `SPART` | SPART_KK | — | CHAR | 2 | 0 | Division |
| `HKONT` | HKONT_KK | — | CHAR | 10 | 0 | General ledger account |
| `MWSKZ` | MWSKZ | — | CHAR | 2 | 0 | Tax on sales/purchases code |
| `MWSZKZ` | MWSZKZ_KK | — | CHAR | 2 | 0 | Supplementary Tax |
| `XANZA` | XANZA_KK | — | CHAR | 1 | 0 | Item is a Down Payment/Down Payment Request |
| `STAKZ` | STAKZ_KK | — | CHAR | 1 | 0 | Type of statistical item |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `BUDAT` | BUDAT | — | DATS | 8 | 0 | Posting Date in the Document |
| `OPTXT` | OPTXT_KK | — | CHAR | 50 | 0 | Item text |
| `WAERS` | BLWAE_KK | — | CUKY | 5 | 0 | Transaction Currency |
| `FAEDN` | FAEDN_KK | — | DATS | 8 | 0 | Due date for net payment |
| `FAEDS` | FAEDS_KK | — | DATS | 8 | 0 | Due Date for Cash Discount |
| `VERKZ` | VERKZ_KK | — | CHAR | 1 | 0 | Item Can Only Be Cleared |
| `STUDT` | STUDT_KK | — | DATS | 8 | 0 | Deferral to |
| `SKTPZ` | SKTPZ_KK | — | DEC | 5 | 3 | Cash discount rate |
| `XMANL` | XMANL_KK | — | CHAR | 1 | 0 | Exclude Item from Dunning Run |
| `KURSF` | KURSF_KK | — | DEC | 9 | 5 | Exchange rate |
| `BETRH` | BETRH_KK | — | CURR | 13 | 2 | Amount In Local Currency With +/- Signs |
| `BETRW` | BETRW_KK | — | CURR | 13 | 2 | Amount in Transaction Currency with +/- Sign |
| `BETR2` | BETR2_KK | — | CURR | 13 | 2 | Amount in second parallel currency with +/- sign |
| `BETR3` | BETR3_KK | — | CURR | 13 | 2 | Amount in third parallel currency with +/- sign |
| `SKFBT` | SKFBT_KK | — | CURR | 13 | 2 | Amount eligible for cash discount in document currency |
| `SBETH` | SBETH_KK | — | CURR | 13 | 2 | Tax Amount in Local Currency With +/- Sign |
| `SBETW` | SBETW_KK | — | CURR | 13 | 2 | Tax Amount in Transaction Currency with +/- Sign |
| `SBET2` | SBET2_KK | — | CURR | 13 | 2 | Tax amount in second parallel currency |
| `SBET3` | SBET3_KK | — | CURR | 13 | 2 | Tax amount in third parallel currency |
| `MWSKO` | MWSKO_KK | — | CHAR | 10 | 0 | Account for posting taxes for down payments |
| `MWVKO` | MWVKO_KK | — | CHAR | 10 | 0 | Account for offsetting tax posting in down payments |
| `TXRUL` | TXRUL_KK | — | CHAR | 1 | 0 | Update Rule for Tax and Tax Clearing |
| `SPZAH` | SPZAH_KK | — | CHAR | 1 | 0 | Lock Reason for Automatic Payment |
| `PYMET` | PYMET_KK | — | CHAR | 1 | 0 | Payment Method |
| `PYBUK` | PYBUK_KK | T001 | CHAR | 4 | 0 | Company Code for Automatic Payment Transactions |
| `PERNR` | PERNR_D | — | NUMC | 8 | 0 | Personnel Number |
| `GRKEY` | GRKEY_KK | — | CHAR | 3 | 0 | Grouping Key for Displaying Open Items |
| `PERSL` | PERSL_KK | — | CHAR | 4 | 0 | Key for Period Assignment |
| `XAESP` | XAESP_KK | — | CHAR | 1 | 0 | Printing - No Changes Possible |
| `AUGDT` | AUGDT_KK | — | DATS | 8 | 0 | Clearing date |
| `AUGBL` | AUGBL_KK | — | CHAR | 12 | 0 | Clearing Document or Printed Document |
| `AUGBD` | AUGBD_KK | — | DATS | 8 | 0 | Clearing document posting date |
| `AUGRD` | AUGRD_KK | — | CHAR | 2 | 0 | Clearing Reason |
| `AUGWA` | AUGWA_KK | — | CUKY | 5 | 0 | Clearing currency |
| `AUGBT` | AUGBT_KK | — | CURR | 13 | 2 | Clearing amount in clearing currency |
| `AUGBS` | AUGBS_KK | — | CURR | 13 | 2 | Tax amount in clearing currency |
| `AUGSK` | AUGSK_KK | — | CURR | 13 | 2 | Cash Discount Granted/Surcharge Levied in Clearing Currency |
| `AUGVD` | AUGVD_KK | — | DATS | 8 | 0 | Value date for clearing |
| `AUGOB` | AUGOB_KK | — | CHAR | 1 | 0 | Item Canceled |
| `WHANG` | WHANG_KK | — | NUMC | 3 | 0 | Number of repetition items |
| `WHGRP` | WHGRP_KK | DFKKOPW | NUMC | 3 | 0 | Repetition group |
| `XEIPH` | XEIPH_KK | — | CHAR | 1 | 0 | Create Line Item in General Ledger |
| `MAHNV` | MAHNV_KK | — | CHAR | 2 | 0 | Dunning Procedure |
| `MANSP` | MANSP_KK | — | CHAR | 1 | 0 | Dunning Lock Reason |
| `XAUGP` | XAUGP_KK | — | CHAR | 1 | 0 | Check Sample Record Clearing |
| `ABRZU` | ABRZU_KK | — | DATS | 8 | 0 | Lower Limit of Settlement Period |
| `ABRZO` | ABRZO_KK | — | DATS | 8 | 0 | Upper Limit of the Billing Period |
| `FDGRP` | FDGRP_KK | — | CHAR | 10 | 0 | Planning Group |
| `FDLEV` | FDLEV_KK | — | CHAR | 2 | 0 | Planning level |
| `FDZTG` | FDZTG_KK | — | NUMC | 2 | 0 | Additional Days for Cash Management |
| `FDWBT` | FDWBT | — | CURR | 13 | 2 | Planning amount in document currency |
| `XTAUS` | XTAUS_KK | — | CHAR | 1 | 0 | Item Split |
| `AUGRS` | AUGRS_KK | — | CHAR | 1 | 0 | Clearing restriction |
| `PYGRP` | PYGRP_KK | — | CHAR | 10 | 0 | Grouping field for automatic payments |
| `PDTYP` | PDTYP_KK | — | CHAR | 1 | 0 | Category of Payment Specification |
| `SPERZ` | SPERZ_KK | — | CHAR | 1 | 0 | Interest Lock Reason |
| `INFOZ` | INFOZ_KK | — | NUMC | 3 | 0 | Doubtful Item Entry/Individual Value Adjustment |
| `TXJCD` | TXJCD | — | CHAR | 15 | 0 | Tax Jurisdiction |
| `TXDAT` | TXDAT_KK | — | DATS | 8 | 0 | Decisive Date for Calculating Taxes |
| `VBUND` | RASSC | — | CHAR | 6 | 0 | Company ID of trading partner |
| `KONTT` | KONTT_KK | — | CHAR | 2 | 0 | Account Assignment Category |
| `KONTL` | KONTL_KK | — | CHAR | 50 | 0 | Acct assnmnt string for industry-specific account assngments |
| `OPSTA` | OPSTA_KK | — | CHAR | 3 | 0 | Dunning indicator |
| `BLART` | BLART_KK | — | CHAR | 2 | 0 | Document Type |
| `EMGPA` | EMGPA_KK | — | CHAR | 10 | 0 | Alternative Business Partner for Payments |
| `EMBVT` | EMBVT_KK | — | CHAR | 4 | 0 | Bank Details ID of Payee |
| `EMADR` | AD_ADDRNUM | — | CHAR | 10 | 0 | Address number |
| `IKEY` | IKEY_KK | — | CHAR | 2 | 0 | Interest Key |
| `EUROU` | EUROU_KK | — | CHAR | 1 | 0 | Status of Euro Conversion |
| `XRAGL` | XRAGL_KK | — | CHAR | 1 | 0 | Clearing posting reversed |
| `ASTKZ` | ASTKZ_KK | — | CHAR | 1 | 0 | Statistical Key of the Initiating Item |
| `ASBLG` | ASBLG_KK | — | CHAR | 12 | 0 | Number of Triggering Document |
| `XBLNR` | XBLNR_KK | — | CHAR | 16 | 0 | Reference document number |
| `INKPS` | INKPS_KK | — | NUMC | 3 | 0 | Collection Item |
| `RNDPS` | RNDPS_KK | — | CHAR | 1 | 0 | Type of Rounding Item |
| `QSSKZ` | QSSKZ | — | CHAR | 2 | 0 | Withholding Tax Code |
| `QSSEW` | QSSEW_KK | — | CHAR | 2 | 0 | Withholding Tax Supplement |
| `QSPTP` | QSPTP_KK | — | CHAR | 1 | 0 | Line Item Category From Withholding Tax View |
| `QSSHB` | QSSHB_KK | — | CURR | 13 | 2 | Tax Base Amount |
| `QBSHB` | QBSHB_KK | — | CURR | 13 | 2 | Withholding Tax Amount (in Document Currency) |
| `QSZNR` | QSZNR | — | CHAR | 10 | 0 | Certificate Number of the Withholding Tax Exemption |
| `XWHEX` | XWHEX_KK | — | CHAR | 1 | 0 | Variable Withholding Tax in DFKKOPWH |
| `RFUPK` | RFUPK_KK | — | NUMC | 4 | 0 | Reference Item In FI-CA Document |
| `STRKZ` | STRKZ_KK | — | CHAR | 2 | 0 | Tax Code for Other Taxes |
| `FITPR` | J_1AFITP_D | — | CHAR | 2 | 0 | Tax type |
| `XPYOR` | XPYOR_KK | — | CHAR | 1 | 0 | Item Included in a Payment Order |
| `LANDL` | LANDL_KK | — | CHAR | 3 | 0 | Country Supplied (for Tax Notifications) |
| `INTBU` | INTBU_KK | — | CHAR | 1 | 0 | Reason for Automatic Creation of Posting |
| `EMCRD` | EMCRD_KK | — | CHAR | 6 | 0 | Alternative Payment Card ID in Document |
| `C4EYE` | C4EYE_KK | — | CHAR | 2 | 0 | Check Reason for Workflows Acc. to Dual Control Principle |
| `C4EYP` | C4EYP_KK | — | CHAR | 1 | 0 | Editing Process To Be Confirmed |
| `SCTAX` | SCTAX_KK | — | CURR | 13 | 2 | Tax Portion in FI-CA Local Currency |
| `STTAX` | STTAX_KK | — | CURR | 13 | 2 | Tax Amount as Statistical Information in Document Currency |
| `STZAL` | STZAL_KK | — | CHAR | 1 | 0 | Status of Payment Processing |
| `ORUPZ` | ORUPZ_KK | — | CHAR | 3 | 0 | Subitem Number before Item Split |
| `NEGBU` | NEGBU_KK | — | NUMC | 1 | 0 | Control Field for Negative Posting |
| `SUBAP` | SUBAP_KK | — | CHAR | 1 | 0 | Subapplication in Contract Accounts Receivable and Payable |
| `PSWSL` | PSWSL_KK | — | CUKY | 5 | 0 | Update Currency for General Ledger Transaction Figures |
| `PSWBT` | PSWBT_KK | — | CURR | 13 | 2 | Amount for Updating in General Ledger |
| `PSWTX` | PSWTX_KK | — | CURR | 13 | 2 | Tax Amount for Update in General Ledger |
| `PSGRP` | PSGRP_KK | — | CHAR | 4 | 0 | Grouping Key for Document Items |
| `XCOLC` | XCOLC_KK | — | CHAR | 1 | 0 | Item Is Included in Collection Case |
| `AASTA` | AASTA_KK | — | CHAR | 1 | 0 | Control Field for Account Assignment Distributions |
| `XCSHA` | XCSHA_KK | — | CHAR | 1 | 0 | Document Contains Assignments from Cash Flows |
| `REACC` | REACC_KK | — | CHAR | 10 | 0 | Originating Account in Cash Flow Anlaysis |
| `REBUK` | REBUK_KK | — | CHAR | 4 | 0 | Partner Company Code for Cash Flow Analysis |
| `XUSTPD` | XUSTPD_KK | — | CHAR | 1 | 0 | Tax on Sales/Purchases Was Calculated by Document |
| `PTITM` | PTITM_KK | — | CHAR | 1 | 0 | Status of Partner Settlement Using Billable Items |
| `EMMND` | EMMND_KK | — | NUMC | 6 | 0 | SEPA Mandate Identifier |
| `PNNUM` | PNNUM_KK | — | CHAR | 16 | 0 | SEPA: Number of Direct Debit Pre-Notification |
| `PNHKF` | PNHKF_KK | — | CHAR | 2 | 0 | SEPA: Origin of Direct Debit Pre-Notification |
| `PNEXD` | PNEXD_KK | — | DATS | 8 | 0 | SEPA: Date of Execution of Direct Debit Pre-Notifcation |
| `PNCTR` | PNCTR_KK | — | CHAR | 1 | 0 | SEPA: Requirement for a Pre-Notification |
| `FINRE` | FINRE_KK | — | CHAR | 12 | 0 | Contract Account of Final Recipient |
| `RDSTA` | RDSTA_KK | — | CHAR | 1 | 0 | Current Distribution Status |
| `RDSTB` | RDSTB_KK | — | CHAR | 1 | 0 | Last Distribution Status Reported |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `BUPLA` | DFKKOP | BUPLA | J_1BBRANCH |  | |
| `BUPLA` | DFKKOP | MANDT | J_1BBRANCH |  | |
| `BUPLA` | DFKKOP | BUKRS | J_1BBRANCH |  | |
| `PYBUK` | DFKKOP | MANDT | T001 |  | |
| `PYBUK` | DFKKOP | PYBUK | T001 |  | |
| `WHGRP` | DFKKOP | MANDT | DFKKOPW |  | |
| `WHGRP` | DFKKOP | OPBEL | DFKKOPW |  | |
| `WHGRP` | DFKKOP | WHGRP | DFKKOPW |  | |
| `WHGRP` | * |  | DFKKOPW |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ABRZO`, `ABRZU`, `ABWBL`, `ABWTP`, `AUGBD`, `AUGBL`, `AUGBT`, `AUGDT`, `AUGRD`, `AUGRS`, `AUGST`, `BETRH`, `BETRW`, `BLART`, `BLDAT`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `AUGBL`, `AUGST`, `BETRH`, `augbl`, `augdt`, `augst`, `bukrs`, `opbel`, `stakz`, `tvorg`, `vkont`

## Join Paths
- `DFKKOP.OPBEL` → `DFKKKO.OPBEL` — Open Item → Doc Header

## Programs Using This Table
- `z_bapi_get_duedate.txt`
- `z_bapi_simple_accinfo.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zfi_insert_locks_to_openitem.txt`
- `zisbi0201_tp.txt`
- `ziscs_migration_deposit_mock3.txt`
- `zisfi0003.txt`
- `zisfi0005_dun.txt`
- `zisfi0069.txt`
- `zisfi0082.txt`
- `zisfi0083.txt`
- `zisfi0083_1t.txt`
- `zisfi0116_test3.txt`
- `zisfi0124.txt`
- `zisfi0132.txt`
- `zisfi0139.txt`
- `zisfi0142.txt`
- `zisfi0207.txt`
- `zisfi0235.txt`
- `zisfi0258.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_