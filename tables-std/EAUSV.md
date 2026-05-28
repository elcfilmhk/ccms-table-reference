# `EAUSV`

**Description:** Move-Out Document V — end of supply extended
**Category:** Standard SAP Table
**References:** 47 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VERTRAG` | | 🔑 | Primary key |
| `AUSZBELEG` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ANLAGE`, `AUSZBELEG`, `AUSZDAT`, `STORAUSZ`, `VERTRAG`, `VSTELLE`, `aedat`, `aenam`, `anlage`, `auszbeleg`, `auszdat`, `erdat`, `ernam`, `storausz`, `vertrag`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `VSTELLE`, `anlage`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_crm_isu_contracts.txt`
- `z_iscs_contract_chng_doc.txt`
- `z_isu_moveout_revrevt.txt`
- `ziscs0019.txt`
- `ziscs0028.txt`
- `ziscs0038.txt`
- `ziscs0067.txt`
- `ziscs0184.txt`
- `ziscs0252f01.txt`
- `ziscs0436.txt`
- `ziscs_sms02.txt`
- `zisdm0151f01.txt`
- `zisdm0153f01.txt`
- `zisdm0154.txt`
- `zisdm0190.txt`
- `zisdm_csmp_from_move_out.txt`
- `zisfi0038.txt`
- `zissd00101.txt`
- `zmoveindoc.txt`
- `zmoveinout.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
