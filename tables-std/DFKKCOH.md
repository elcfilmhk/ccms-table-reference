# `DFKKCOH`

**Description:** Collection History — collection/payment history
**Category:** Standard SAP Table
**References:** 12 SELECT statements across 10 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkcoh/) — validated 2026-05-30, schema v1.0
**Schema fields:** 72 fields | **Data types:** CHAR(57), CUKY(1), CURR(1), DATS(6), DEC(1), LANG(1), NUMC(2), RAW(1), TIMS(2)

## Key Fields
`VKONT` | `BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `UNAME` | SYUNAME | — | CHAR | 12 | 0 | User Name |
| `CDATE` | COCDT_KK | — | DATS | 8 | 0 | Created On |
| `CTIME` | COCTM_KK | — | TIMS | 6 | 0 | Time of Creation (to the Second) |
| `GPART` | CREC_GP_KK | — | CHAR | 10 | 0 | Correspondence Recipient |
| `GPART_GUID` | CREC_GP_GUID_KK | — | CHAR | 32 | 0 | Correspondence Recipient (GUID) |
| `GPART_ADR_KIND` | CORR_ADR_KIND_KK | — | CHAR | 10 | 0 | Address Type Of Correspondence Recipient |
| `ORG_GPART` | CREC_ORG_GP_KK | — | CHAR | 10 | 0 | Original Correspondence Recipient |
| `ORG_GPART_GUID` | CREC_ORG_GP_GUID_KK | — | CHAR | 32 | 0 | Original Correspondence Recipient (GUID) |
| `ADD_GPART` | CREC_GP_ADD_KK | — | CHAR | 10 | 0 | Additional Business Partner for Correspondence Recipient |
| `ADD_GPART_GUID` | CREC_GP_ADD_GUID_KK | — | CHAR | 32 | 0 | Addit. Business Partner for Correspondence Recipient GUID |
| `ADD_GPART_CAT` | CREC_GP_ADD_CAT_KK | — | CHAR | 1 | 0 | Type of Additional Correspondence Recipient |
| `VKONT` | CORR_VKONT_KK | — | CHAR | 12 | 0 | Contract Account Number |
| `VTREF` | CORR_VTREF_KK | — | CHAR | 20 | 0 | Reference Specifications from Contract |
| `ADR_VALID_ON` | CREC_AD_VALID_ON_KK | — | DEC | 15 | 0 | Address of Correspondence Recipient Valid On |
| `ADRNR` | CREC_AD_KK | — | CHAR | 10 | 0 | Address Number of Correspondence Recipient |
| `ADR_GUID` | CREC_AD_GUID_KK | — | CHAR | 32 | 0 | Address GUID of Correspondence Recipient |
| `ADRNR_INDEP_COMM` | CREC_AD_INDEP_COMM_KK | — | CHAR | 10 | 0 | Address Number for Address-Independent Communication |
| `AGPART` | CSEN_GP_KK | — | CHAR | 10 | 0 | Sending Business Partner |
| `AGPART_GUID` | CSEN_GP_GUID_KK | — | CHAR | 32 | 0 | Sender (GUID) |
| `AGPART_ADR_KIND` | CORR_ADR_KIND_KK | — | CHAR | 10 | 0 | Address Type Of Correspondence Recipient |
| `AADRNR` | CSEN_AD_KK | — | CHAR | 10 | 0 | Address Number of Correspondence Sender |
| `AADR_GUID` | CSEN_AD_GUID_KK | — | CHAR | 32 | 0 | Address GUID of Correspondence Sender |
| `FORMKEY` | FORMKEY | — | CHAR | 30 | 0 | Application form |
| `FORMKEY_RDI` | FORMKEY | — | CHAR | 30 | 0 | Application form |
| `ENTID1` | ENTID_KK | — | CHAR | 4 | 0 | Correspondence data |
| `DATA1` | CDATA_KK | — | CHAR | 32 | 0 | Correspondence Data Field |
| `ENTID2` | ENTID_KK | — | CHAR | 4 | 0 | Correspondence data |
| `DATA2` | CDATA_KK | — | CHAR | 32 | 0 | Correspondence Data Field |
| `ENTID3` | ENTID_KK | — | CHAR | 4 | 0 | Correspondence data |
| `DATA3` | CDATA_KK | — | CHAR | 32 | 0 | Correspondence Data Field |
| `ENTID4` | ENTID_KK | — | CHAR | 4 | 0 | Correspondence data |
| `DATA4` | CDATA_KK | — | CHAR | 32 | 0 | Correspondence Data Field |
| `CSORT` | CSORT_KK | — | CHAR | 50 | 0 | Correspondence Sort Field |
| `XCODT` | XCODT_KK | — | CHAR | 1 | 0 | Data Part Is Used |
| `XCODT_CLUST` | XCODT_CLUST_KK | — | CHAR | 1 | 0 | Cluster Data Part is Used |
| `LAUFD` | CORR_LAUFD_KK | — | DATS | 8 | 0 | Date ID for Creation Run |
| `LAUFI` | CORR_LAUFI_KK | — | CHAR | 6 | 0 | Additional ID Characteristic for Creation Run |
| `XTEST` | XTEST_KK | — | CHAR | 1 | 0 | Correspondence is Result of Test |
| `COPRI` | COPRI_KK | — | DATS | 8 | 0 | Print Date |
| `COIDT` | COIDT_KK | — | DATS | 8 | 0 | Date of Issue |
| `COITM` | COITM_KK | — | TIMS | 6 | 0 | Issue Time to the Second |
| `SPRAS` | SPRAS | — | LANG | 1 | 0 | Language Key |
| `SALWA` | CORR_BLWAE_KK | — | CUKY | 5 | 0 | Transaction Currency |
| `SALBE` | CORR_BETRH_KK | — | CURR | 13 | 2 | Amount in Local Currency with +/- Signs |
| `SENDCONTROL` | SENDCONTROL | ESENDCONTROL | CHAR | 4 | 0 | Dispatch Control |
| `PERSNUMBER` | AD_PERSNUM | — | CHAR | 10 | 0 | Person number |
| `APERSNUMBER` | AD_PERSNUM | — | CHAR | 10 | 0 | Person number |
| `BUKRS` | CORR_BUKRS | — | CHAR | 4 | 0 | Company Code in Correspondence |
| `CORR_ROLE` | CORR_ROLE_KK | TFK070M | CHAR | 4 | 0 | Correspondence Roles |
| `COPRI_LAUFD` | COPRI_LAUFD_KK | — | DATS | 8 | 0 | Date ID for Print Run |
| `COPRI_LAUFI` | COPRI_LAUFID_KK | — | CHAR | 6 | 0 | ID Characteristic for Run |
| `PROCESS_ID_` | CORR_PROCESS_ID_KK | — | CHAR | 36 | 0 | Business Process ID |
| `NO_DOCPARTS` | CORR_NO_DOCPARTS_KK | — | NUMC | 4 | 0 | Number of Document Parts |
| `DOCPART_ROLE` | CORR_DOCPART_ROLE_KK | — | CHAR | 1 | 0 | Document Part Role |
| `XTRIAL` | XTRIAL_KK | — | CHAR | 1 | 0 | Correspondence Request is Test |
| `XREPRINT` | XREPRINT_KK | — | CHAR | 1 | 0 | Recreate Correspondence |
| `SUBAP` | CORR_SUBAP_KK | — | CHAR | 1 | 0 | Subapplication Indicator in Correspondence |
| `XDELETE` | X_CORR_DELETE_KK | — | CHAR | 1 | 0 | Correspondence Is Logically Deleted |
| `PRINT_MODE` | PRINT_MODE_KK | — | CHAR | 1 | 0 | Business Partner Print Format |
| `X_NO_ARC` | X_NO_ARC_KK | — | CHAR | 1 | 0 | SAP ArchiveLink Object ID Part Is Not Used |
| `X_DOCPART_LIST` | X_DOCPART_LIST_KK | — | CHAR | 1 | 0 | Document Part List Is Used |
| `BKKRS` | BKK_BKKRS | — | CHAR | 4 | 0 | Bank Area |
| `ACNUM_INT` | BKK_ACCNT | — | CHAR | 10 | 0 | Internal Account Number for Current Account |
| `OBJECT_IDCMS` | CMS_DTE_OBJECT_ID | — | RAW | 16 | 0 | Object Identification Number |
| `FLG_ORIGINALCMS` | CMS_DTE_FLG_ORIG | — | CHAR | 1 | 0 | Flag to indicate if the document is original or duplicate |
| `SENDCONTROLCMS` | SENDCONTROL | — | CHAR | 4 | 0 | Dispatch Control |
| `PRODUCTTYPEFVD` | VVSART | — | CHAR | 3 | 0 | Product Type |
| `BP_ROLEFVD` | BU_PARTNERROLE | — | CHAR | 6 | 0 | BP Role |
| `BP_ROLETYPEFVD` | BP_ROLE | — | CHAR | 4 | 0 | Business Partner Role Type |
| `SOBJECTFVD` | VVKEYOBJ | — | CHAR | 10 | 0 | Internal key for object |
| `CORR_ACTIVITYFVD` | KORRVORF | — | NUMC | 4 | 0 | Correspondence activity |
| `REFERENCEDATEFVD` | TB_CORR_REFERENCE_DATE | — | DATS | 8 | 0 | Reference Date for Creating Correspondence |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CORR_ROLE` | DFKKCOH | MANDT | TFK070M |  | |
| `CORR_ROLE` | DFKKCOH | CORR_ROLE | TFK070M |  | |
| `COTYP` | DFKKCOH | COTYP | TFK070A |  | |
| `SENDCONTROL` | DFKKCOH | MANDT | ESENDCONTROL |  | |
| `SENDCONTROL` | DFKKCOH | SENDCONTROL | ESENDCONTROL |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0077.txt`
- `zisbi0083.txt`
- `zisbi0157.txt`
- `ziscs0124.txt`
- `ziscs0156.txt`
- `ziscs0437.txt`
- `zisfi0014.txt`
- `zisfi0025_corr_print.txt`
- `zisfi0198.txt`
- `zrdm_letter_2.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_