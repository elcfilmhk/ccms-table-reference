# `BUT0CC`

**Description:** BP Credit Card — credit card info
**Category:** Standard SAP Table
**References:** 68 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `CLIENT` | | 🔑 | Primary key |
| `PARTNER` | | 🔑 | Primary key |
| `BANKCT` | | 🔑 | Primary key |

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
