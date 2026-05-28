# `EAUS`

**Description:** Move-Out Document — end of supply document
**Category:** Standard SAP Table
**References:** 65 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VERTRAG` | | 🔑 | Primary key |
| `AUSZBELEG` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AUSZBELEG`, `ERDAT`, `KUNDE`, `STORAUSZ`, `VKONT`, `aedat`, `auszbeleg`, `departuredate`, `erdat`, `kunde`, `loevm`, `storausz`, `vkont`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ERDAT`, `VKONT`, `aedat`, `erdat`, `vkont`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_track_mo.txt`
- `z_calculate_deposit.txt`
- `z_get_ca_bp_modoc.txt`
- `z_isu_moveout_revrevt.txt`
- `ziscs0161.txt`
- `ziscs0177.txt`
- `ziscs0184.txt`
- `ziscs0289f.txt`
- `ziscs0436.txt`
- `zisfi0027.txt`
- `zisfi0038.txt`
- `zisfi0039.txt`
- `zisfi0093.txt`
- `zisfi0103.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test.txt`
- `zisfi0116_test3.txt`
- `zisfi0341.txt`
- `zisfiecau01_1.txt`
- `zissd00101.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
