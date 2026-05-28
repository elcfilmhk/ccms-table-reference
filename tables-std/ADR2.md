# `ADR2`

**Description:** Phone Number — phone number assignments
**Category:** Standard SAP Table
**References:** 97 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `CLIENT` | | 🔑 | Primary key |
| `ADDRNUMBER` | | 🔑 | Primary key |
| `PERSNUMBER` | | 🔑 | Primary key |
| `CONSNUMBER` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `addrnumber`, `consnumber`, `date_from`, `persnumber`, `r3_user`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `addrnumber`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_account_mgr_by_ca.txt`
- `z_bapi_bp_details.txt`
- `z_update_crm_bp.txt`
- `zadru_create.txt`
- `ziscs0031.txt`
- `ziscs0238.txt`
- `ziscs0297.txt`
- `ziscs0351f01.txt`
- `ziscs0368.txt`
- `ziscs_sms02.txt`
- `ziscseec_comm_frmwrk_dr.txt`
- `ziscv06a.txt`
- `ziscv08nv_f01.txt`
- `ziscv09_f01.txt`
- `zisdm0313_adr.txt`
- `zisfi0214.txt`
- `zisfi0250.txt`
- `zisfi0250_backup.txt`
- `zisfi0250_backup_1.txt`
- `zissd00111.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
