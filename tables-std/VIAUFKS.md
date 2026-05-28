# `VIAUFKS`

**Description:** Order (IS-U) — IS-U order master
**Category:** Standard SAP Table
**References:** 71 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `AUFNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AUART`, `AUFNR`, `ERDAT`, `GSTRP`, `IDAT2`, `ILART`, `ILOAN`, `IPHAS`, `TPLNR`, `auart`, `aufnr`, `idat2`, `ilart`, `iloan`, `iphas`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `AUART`, `AUFNR`, `aufnr`, `idat2`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_premise_validation_f.txt`
- `z_bapi_validate_premise.txt`
- `zdiscon.txt`
- `zisbi0173.txt`
- `zisbi0198.txt`
- `zisbw0043.txt`
- `ziscrm0318forms.txt`
- `ziscs0038.txt`
- `ziscs0153.txt`
- `ziscs0273.txt`
- `ziscs0283.txt`
- `ziscs0283a.txt`
- `ziscs0341.txt`
- `zisdm0409.txt`
- `zisdm_so_approval_f01.txt`
- `zisdmreaufk20f10.txt`
- `zisfi0124.txt`
- `zrdm_dr_rep.txt`
- `zrdm_mr_rep.txt`
- `zrpm_mwfm_so_create.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
