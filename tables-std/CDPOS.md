# `CDPOS`

**Description:** Change Document Position — change log line items
**Category:** Standard SAP Table
**References:** 196 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/cdpos/) — validated 2026-05-30, schema v1.0
**Schema fields:** 7 fields | **Data types:** CHAR(3), CUKY(2), UNIT(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `TEXT_CASE` | CDXFELD | — | CHAR | 1 | 0 | Flag: X=Text change |
| `UNIT_OLD` | CDUNIT | — | UNIT | 3 | 0 | Change documents, unit referenced |
| `UNIT_NEW` | CDUNIT | — | UNIT | 3 | 0 | Change documents, unit referenced |
| `CUKY_OLD` | CDCUKY | TCURC | CUKY | 5 | 0 | Change documents, referenced currency |
| `CUKY_NEW` | CDCUKY | TCURC | CUKY | 5 | 0 | Change documents, referenced currency |
| `VALUE_NEW` | CDFLDVALN | — | CHAR | 254 | 0 | New contents of changed field |
| `VALUE_OLD` | CDFLDVALO | — | CHAR | 254 | 0 | Old contents of changed field |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CHANGENR` | CDPOS | MANDANT | CDHDR |  | |
| `CHANGENR` | CDPOS | OBJECTCLAS | CDHDR |  | |
| `CHANGENR` | CDPOS | OBJECTID | CDHDR |  | |
| `CHANGENR` | CDPOS | CHANGENR | CDHDR |  | |
| `CUKY_NEW` | CDPOS | CUKY_NEW | TCURC |  | |
| `CUKY_NEW` | CDPOS | MANDANT | TCURC |  | |
| `CUKY_OLD` | CDPOS | MANDANT | TCURC |  | |
| `CUKY_OLD` | CDPOS | CUKY_OLD | TCURC |  | |
| `MANDANT` | CDPOS | MANDANT | T000 |  | |

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