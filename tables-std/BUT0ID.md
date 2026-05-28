# `BUT0ID`

**Description:** BP Identification — ID documents
**Category:** Standard SAP Table
**References:** 74 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `CLIENT` | | 🔑 | Primary key |
| `PARTNER` | | 🔑 | Primary key |
| `TYPE` | | 🔑 | Primary key |
| `IDNUMBER` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `idnumber`, `partner`, `type`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `idnumber`, `partner`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_bp_id.txt`
- `z_bapi_get_track_result_mi.txt`
- `z_bapi_get_track_result_mo.txt`
- `z_bapi_val_iden.txt`
- `z_bp_id_validation.txt`
- `ziscrm0006f01.txt`
- `ziscrm0008f01.txt`
- `ziscrm0010f01.txt`
- `ziscrm0031f01.txt`
- `ziscs0244.txt`
- `ziscs0285.txt`
- `ziscs0322.txt`
- `ziscs0368.txt`
- `ziscs0802_f01.txt`
- `ziscseec_eec_elig_check.txt`
- `ziscspc_sdu_reg_ben.txt`
- `ziscv06a.txt`
- `ziscv08nv_f01.txt`
- `ziscvdatamskdatabackup.txt`
- `zisfi0305_f01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
