# `VBAK`

**Description:** Sales Document Header — sales order header
**Category:** Standard SAP Table
**References:** 137 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VBELN` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `auart`, `audat`, `bnddt`, `erdat`, `ernam`, `knumv`, `kunnr`, `kvgr3`, `mandt`, `netwr`, `spart`, `vbeln`, `vkbur`, `vkgrp`, `vkorg`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `auart`, `vbeln`

## Join Paths
- `VBAK.VBELN` → `VBAP.VBELN` — Sales Header → Item
- `VBAK.VBELN` → `VBPA.VBELN` — Sales Header → Partner
- `VBAK.VBELN` → `VBKD.VBELN` — Sales Header → Conditions
- `VBAK.VBELN` → `VBRK.VBELN` — Sales → Billing

## Programs Using This Table
- `zisfi0121.txt`
- `zisfi0238_bw.txt`
- `zissd00003.txt`
- `zissd00005.txt`
- `zissd00008.txt`
- `zissd00013.txt`
- `zissd00015.txt`
- `zissd00018.txt`
- `zissd00048.txt`
- `zissd00056.txt`
- `zissd00059.txt`
- `zissd00060.txt`
- `zissd00091.txt`
- `zissd00098.txt`
- `zissd00100.txt`
- `zissd00110.txt`
- `zsdisqry02.txt`
- `zsdisqry04.txt`
- `zsdsoblk1.txt`
- `zsdsopoc1.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
