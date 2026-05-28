# `BUT0BK`

**Description:** BP Bank Details — bank account info
**Category:** Standard SAP Table
**References:** 71 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `CLIENT` | | 🔑 | Primary key |
| `PARTNER` | | 🔑 | Primary key |
| `BANKN` | | 🔑 | Primary key |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_bank_details.txt`
- `z_bapi_bank_details_noname.txt`
- `z_bapi_get_ap_status.txt`
- `z_bapi_get_track_mo.txt`
- `z_bapi_get_track_result_mo.txt`
- `z_check_ca_ebill_autopay.txt`
- `z_get_bank_name.txt`
- `z_paymedium_eft_30.txt`
- `ziscs0184.txt`
- `ziscs0802_f01.txt`
- `ziscs0815forms.txt`
- `ziscs0817forms.txt`
- `ziscspc_sdu_ben_view.txt`
- `ziscspc_sdu_reg_ben.txt`
- `ziscv03.txt`
- `ziscv06a.txt`
- `ziscv08nv_f01.txt`
- `ziscvdatamskdatabackup.txt`
- `zisfi0219.txt`
- `zvkk_acct_mgr_bp_dchck.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
