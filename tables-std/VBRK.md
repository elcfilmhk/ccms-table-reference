# `VBRK`

**Description:** Billing Document Header — billing/invoice header
**Category:** Standard SAP Table
**References:** 32 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VBELN` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `aedat`, `erdat`, `fkart`, `fkdat`, `fksto`, `fktyp`, `kunag`, `rfbsk`, `sfakn`, `vbeln`, `vbtyp`, `vkont`, `vkorg`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `erdat`, `fkdat`, `vbtyp`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0013.txt`
- `ziscs0040.txt`
- `zissd00002.txt`
- `zissd00004.txt`
- `zissd00006.txt`
- `zissd00007.txt`
- `zissd00011.txt`
- `zissd00012.txt`
- `zissd00016.txt`
- `zissd00023.txt`
- `zissd00045.txt`
- `zissd00048.txt`
- `zissd00050.txt`
- `zissd00054.txt`
- `zissd00063.txt`
- `zissd00065.txt`
- `zmmpri000.txt`
- `zsdisqry02.txt`
- `zsdslcrm01.txt`
- `zsdsodl05.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
