# `FKKMAZE`

**Description:** CA Line Item — FI-CA document line items
**Category:** Standard SAP Table
**References:** 46 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `OPBEL` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `gpart`, `laufd`, `laufi`, `mahns`, `opbel`, `opupk`, `opupw`, `opupz`, `vkont`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `laufd`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0079.txt`
- `zisbi0224forms.txt`
- `ziscs0065.txt`
- `zisdm0282.txt`
- `zisfi0005_dun.txt`
- `zisfi0038.txt`
- `zisfi0040.txt`
- `zisfi0040_perf_tuning.txt`
- `zisfi0042.txt`
- `zisfi0101.txt`
- `zisfi0106.txt`
- `zisfi0111.txt`
- `zisfi0139.txt`
- `zisfi0146.txt`
- `zisfi0148f01.txt`
- `zisfi0152.txt`
- `zisfi0190.txt`
- `zisfi0214.txt`
- `zisfi0215.txt`
- `zisfi0243_d.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
