# `VBPA`

**Description:** Sales Document Partner — partner addresses
**Category:** Standard SAP Table
**References:** 99 SELECT statements across 5 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VBELN` | | 🔑 | Primary key |
| `POSNR` | | 🔑 | Primary key |
| `PARVW` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `kunnr`, `parvw`, `vbeln`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zissd00100.txt`
- `zissd00101.txt`
- `zsdisn001.txt`
- `zsdsodl02.txt`
- `zsdsopoc1.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
