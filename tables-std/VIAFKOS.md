# `VIAFKOS`

**Description:** Service Order — service order header
**Category:** Standard SAP Table
**References:** 153 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `AUFNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AUART`, `AUFNR`, `IPHAS`, `KTEXT`, `adrnr`, `aedat`, `auart`, `aufnr`, `aufpl`, `erdat`, `gewrk`, `ilart`, `ingpr`, `iwerk`, `kunum`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `IPHAS`, `aufnr`, `ilart`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_dunning_create_so.txt`
- `ziscs0031.txt`
- `ziscs0149.txt`
- `ziscs0161.txt`
- `ziscs0182.txt`
- `ziscs0254.txt`
- `ziscs0364.txt`
- `ziscsriaufk20.txt`
- `zisdm0067.txt`
- `zisdm0142.txt`
- `zisdm0152.txt`
- `zisdm0169.txt`
- `zisdm0172.txt`
- `zisdm0215.txt`
- `zisdm0315.txt`
- `zisdm0420.txt`
- `zisfi0005_dun.txt`
- `zisfi0009.txt`
- `zisfi0082.txt`
- `zisuorder.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
