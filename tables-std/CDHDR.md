# `CDHDR`

**Description:** Change Document Header — change log header
**Category:** Standard SAP Table
**References:** 173 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `OBJCLAS` | | 🔑 | Primary key |
| `OBJID` | | 🔑 | Primary key |
| `CHANGENR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `OBJECTCLAS`, `UDATE`, `changenr`, `objectclas`, `objectid`, `username`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `OBJECTCLAS`, `changenr`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zbacbe034.txt`
- `zisbi0075.txt`
- `zisbi0091.txt`
- `zisbi0142.txt`
- `zisbw0030.txt`
- `ziscs0093.txt`
- `ziscs0151.txt`
- `ziscs0169.txt`
- `ziscs0169_old.txt`
- `ziscs0173.txt`
- `ziscs0251.txt`
- `ziscs0836_f01.txt`
- `zisfi0014.txt`
- `zisfi0036.txt`
- `zisfi0039.txt`
- `zisfi0050.txt`
- `zisfi0069.txt`
- `zisfi0149.txt`
- `zisfi0219.txt`
- `zissd00101.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
