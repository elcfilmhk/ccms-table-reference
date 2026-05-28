# `FKKVK`

**Description:** Contract Account — CA master record
**Category:** Standard SAP Table
**References:** 214 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VKONT` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ERDAT`, `VKONT`, `VKTYP`, `loevm`, `vkont`, `vktyp`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `VKTYP`, `vkont`, `vktyp`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_bp_id.txt`
- `z_bapi_get_gs_info.txt`
- `z_bapi_simple_accinfo.txt`
- `z_bapi_webid_forget.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zisbi0006.txt`
- `zisbi0142.txt`
- `ziscrm0006f01.txt`
- `ziscs0151.txt`
- `ziscs0169.txt`
- `ziscs0173.txt`
- `ziscs0195.txt`
- `zisdm0255f01.txt`
- `zisdm0382.txt`
- `zisfi0005_dun.txt`
- `zisfi0039.txt`
- `zisfi0108.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test3.txt`
- `zisfi0149.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
