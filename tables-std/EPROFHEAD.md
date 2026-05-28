# `EPROFHEAD`

**Description:** Energy Profile Header — rate profile master
**Category:** Standard SAP Table
**References:** 31 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `PROFILE` | | 🔑 | Primary key |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `method-get_data.txt`
- `method-vee_manual_edit.txt`
- `z_conv_kvarh_to_kva_fit.txt`
- `z_isdm_get_formula_profile.txt`
- `z_write_bwami_extractor.txt`
- `z_write_bwfit_extractor.txt`
- `zedm_ext_30int_sub_forms.txt`
- `zisdm0022f01.txt`
- `zisdm0205.txt`
- `zisdm0209_evf01.txt`
- `zisdm0333.txt`
- `zisdm0382.txt`
- `zisdm_profvalday_get.txt`
- `zised0020.txt`
- `zised0040.txt`
- `zised0054_forms.txt`
- `zredm_prof_stat_qual.txt`
- `zredm_prof_val_gen.txt`
- `zredm_status_prof_update.txt`
- `zrmig_zz_profile_update.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
