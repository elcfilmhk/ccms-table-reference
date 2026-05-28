# `EKKO`

**Description:** Purchasing Document Header — PO header
**Category:** Standard SAP Table
**References:** 32 SELECT statements across 16 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `EBELN` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AEDAT`, `BSART`, `BSTYP`, `BUKRS`, `EBELN`, `EKGRP`, `EKORG`, `ERNAM`, `INCO1`, `LIFNR`, `LOEKZ`, `STATU`, `WAERS`, `ZTERM`, `ZZVESTINC`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ebeln`

## Join Paths
- `EKKO.EBELN` → `EKPO.EBELN` — PO Header → PO Item
- `EKKO.EBELN` → `EKBE.EBELN` — PO → History

## Programs Using This Table
- `z_create_ekrs.txt`
- `zbacbe034.txt`
- `zissd00072.txt`
- `zissd00079.txt`
- `zissd00081.txt`
- `zissd00086.txt`
- `zissd00096.txt`
- `zissd00097.txt`
- `zissd00108.txt`
- `zissd_get_oa_validity_price.txt`
- `zissd_recover_ekrs_for_ers.txt`
- `zmmpri000.txt`
- `zmmpri001.txt`
- `zmmprsi01.txt`
- `zsdsodl02.txt`
- `zsdsodl06.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
