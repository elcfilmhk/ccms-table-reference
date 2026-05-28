# `VBRP`

**Description:** Billing Document Item — billing line item
**Category:** Standard SAP Table
**References:** 31 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VBELN` | | 🔑 | Primary key |
| `POSNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `aubel`, `aupos`, `erdat`, `erzet`, `matnr`, `netwr`, `posnr`, `vbeln`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `aubel`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `ziscs0523_f01.txt`
- `zisfi0030.txt`
- `zisfi0235.txt`
- `zissd00002.txt`
- `zissd00004.txt`
- `zissd00006.txt`
- `zissd00007.txt`
- `zissd00011.txt`
- `zissd00016.txt`
- `zissd00023.txt`
- `zissd00045.txt`
- `zissd00048.txt`
- `zissd00050.txt`
- `zissd00054.txt`
- `zissd00072.txt`
- `zsdbidl01.txt`
- `zsdbidl02.txt`
- `zsdisqry02.txt`
- `zsdslcrm01.txt`
- `zsdsodl05.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
