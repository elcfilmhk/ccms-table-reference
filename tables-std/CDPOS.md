# `CDPOS`

**Description:** Change Document Position — change log line items
**Category:** Standard SAP Table
**References:** 196 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `OBJCLAS` | | 🔑 | Primary key |
| `OBJID` | | 🔑 | Primary key |
| `CHANGENR` | | 🔑 | Primary key |
| `TABNAME` | | 🔑 | Primary key |
| `FNAME` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `CHANGENR`, `FNAME`, `OBJECTCLAS`, `OBJECTID`, `TABNAME`, `changenr`, `chngind`, `fname`, `objectclas`, `objectid`, `tabname`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `OBJECTCLAS`, `objectid`

## Join Paths
- `CDPOS.OBJECTID` → `EVER.VKONTO` — Change Docs → Contract

## Programs Using This Table
- `zbacbe034.txt`
- `zfi_defer_to_by_changeid.txt`
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

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
