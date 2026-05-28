# `EPROFASS`

**Description:** Energy Profile Assignment — rate profile assignment
**Category:** Standard SAP Table
**References:** 91 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `PROFILE` | | 🔑 | Primary key |
| `LOGIKZW` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `datefrom`, `dateto`, `logikzw`, `profile`, `timeto`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `logikzw`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_cs_cxt_add_consum.txt`
- `z_isdm_consumption_details.txt`
- `z_isdm_registers_validation.txt`
- `z_write_bwfit_extractor.txt`
- `zisdm0102.txt`
- `zisdm0128f01.txt`
- `zisdm0201.txt`
- `zisdm0201_sub_lp.txt`
- `zisdm0212.txt`
- `zisdm0213.txt`
- `zisdm0214.txt`
- `zisdm0284.txt`
- `zisdm0310_adr.txt`
- `zisdm0361.txt`
- `zised0047.txt`
- `zised0058.txt`
- `zisu_edm_formula_fitreb.txt`
- `zrca_ssr_premise_upload.txt`
- `zredm_profile_stat_rep.txt`
- `zrmig_recon_report.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
