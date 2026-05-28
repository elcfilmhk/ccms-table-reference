# `VBAP`

**Description:** Sales Document Item — sales order item
**Category:** Standard SAP Table
**References:** 105 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VBELN` | | 🔑 | Primary key |
| `POSNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `abgru`, `arktx`, `cuobj`, `erdat`, `kondm`, `kwmeng`, `matnr`, `mvgr1`, `netwr`, `posnr`, `uepos`, `vbeln`, `vkaus`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `cuobj`, `vbeln`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `ziscs0522_f01.txt`
- `ziscseec_comm_frmwrk_eeus_ea.txt`
- `zisfi0121.txt`
- `zissd00003.txt`
- `zissd00005.txt`
- `zissd00008.txt`
- `zissd00013.txt`
- `zissd00015.txt`
- `zissd00018.txt`
- `zissd00048.txt`
- `zissd00056.txt`
- `zissd00059.txt`
- `zissd00066.txt`
- `zissd00091.txt`
- `zissd00101.txt`
- `zsdisqry02.txt`
- `zsdisqry04.txt`
- `zsdsoblk1.txt`
- `zsdsoc001.txt`
- `zsdsopoc1.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
