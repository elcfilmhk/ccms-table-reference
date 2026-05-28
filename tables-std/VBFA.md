# `VBFA`

**Description:** Sales Document Flow — document flow/log
**Category:** Standard SAP Table
**References:** 24 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VBELN` | | 🔑 | Primary key |
| `POSNR` | | 🔑 | Primary key |
| `VBTYP_N` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ZO1`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisfi0121.txt`
- `zisfi0238.txt`
- `zisfi0238_bw.txt`
- `zissd00017.txt`
- `zissd00018.txt`
- `zissd00019.txt`
- `zissd00020.txt`
- `zissd00058.txt`
- `zissd00059.txt`
- `zissd00060.txt`
- `zissd00061.txt`
- `zissd00062.txt`
- `zissd00086.txt`
- `zissd00088.txt`
- `zissd00097.txt`
- `zissd00100.txt`
- `zsdisqry05.txt`
- `zsdsoblk1.txt`
- `zsdsodl01.txt`
- `zsdsodl05.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
