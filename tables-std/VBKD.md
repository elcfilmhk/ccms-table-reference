# `VBKD`

**Description:** Sales Document Business Data — business conditions
**Category:** Standard SAP Table
**References:** 85 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VBELN` | | 🔑 | Primary key |
| `POSNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `posnr`, `vbeln`, `vkont`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `vkont`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_multi_ecodata_profile.txt`
- `ziscseec_eeus_reb_det.txt`
- `zissd00001.txt`
- `zissd00005.txt`
- `zissd00013.txt`
- `zissd00017.txt`
- `zissd00018.txt`
- `zissd00024.txt`
- `zissd00042.txt`
- `zissd00047.txt`
- `zissd00052.txt`
- `zissd00058.txt`
- `zissd00060.txt`
- `zissd00061.txt`
- `zissd00062.txt`
- `zissd00065.txt`
- `zissd00101.txt`
- `zissd00115.txt`
- `zmmpri000.txt`
- `zsdisqry01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
