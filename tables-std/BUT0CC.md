# `BUT0CC`

**Description:** BP Credit Card — credit card info
**Category:** Standard SAP Table
**References:** 68 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/but0cc/) — validated 2026-05-30, schema v1.0
**Schema fields:** 6 fields | **Data types:** CHAR(6)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `CCINS` | CC_INSTITUTE | TB033 | CHAR | 4 | 0 | Payment card type |
| `CCNUM` | BU_CCNUM | — | CHAR | 25 | 0 | Payment Cards: Card Number |
| `CCDEF` | BU_CCDEF | — | CHAR | 1 | 0 | BP: Standard Payment Card |
| `CCACCNAME` | BU_CREDITCNAME | — | CHAR | 40 | 0 | Description of Credit Card Details |
| `CARD_GUID` | BU_CARD_GUID_MAP | — | CHAR | 32 | 0 | Mapping DTEL for Payment Card GUID |
| `BP_EEW_BUT0CC` | DUMMY | — | CHAR | 1 | 0 | Dummy function in length 1 |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CCINS` | BUT0CC | MANDT | TB033 |  | |
| `CCINS` | BUT0CC | CCINS | TB033 |  | |
| `PARTNER` | BUT0CC | MANDT | BUT000 |  | |
| `PARTNER` | BUT0CC | PARTNER | BUT000 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `CC2`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_chk_but0bk_but0cc.txt`
- `z_check_ca_ebill_autopay.txt`
- `z_get_bank_name.txt`
- `ziscrm_patch_bp_payment_card.txt`
- `ziscs0322.txt`
- `ziscv03.txt`
- `ziscv06a.txt`
- `ziscv11_f01.txt`
- `ziscv11nv_f01.txt`
- `ziscv13_f01.txt`
- `ziscv13nv_f01.txt`
- `ziscvdatamskdatabackup.txt`
- `zisfi0092.txt`
- `zisfi0112.txt`
- `zisfi0142.txt`
- `zisfi0143.txt`
- `zisfi0193.txt`
- `zisfi0255.txt`
- `zisfi0333_f01.txt`
- `zisfibocsetup.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_