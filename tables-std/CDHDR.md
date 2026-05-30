# `CDHDR`

**Description:** Change Document Header — change log header
**Category:** Standard SAP Table
**References:** 173 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/cdhdr/) — validated 2026-05-30, schema v1.0
**Schema fields:** 10 fields | **Data types:** CHAR(7), DATS(1), LANG(1), TIMS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `USERNAME` | CDUSERNAME | — | CHAR | 12 | 0 | User name of the person responsible in change document |
| `UDATE` | CDDATUM | — | DATS | 8 | 0 | Creation date of the change document |
| `UTIME` | CDUZEIT | — | TIMS | 6 | 0 | Time changed |
| `TCODE` | CDTCODE | TSTC | CHAR | 20 | 0 | Transaction in which a change was made |
| `PLANCHNGNR` | PLANCHNGNR | — | CHAR | 12 | 0 | Planned change number |
| `ACT_CHNGNO` | CD_CHNGNO | — | CHAR | 10 | 0 | Change number of the document created by this change |
| `WAS_PLANND` | CD_PLANNED | — | CHAR | 1 | 0 | Flag that changes were generated from planned changes |
| `CHANGE_IND` | CDCHNGINDH | — | CHAR | 1 | 0 | Application object change type (U, I, E, D) |
| `LANGU` | LANGU | — | LANG | 1 | 0 | Language Key |
| `VERSION` | CHAR3 | — | CHAR | 3 | 0 | 3-Byte field |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MANDANT` | CDHDR | MANDANT | T000 |  | |
| `TCODE` | CDHDR | TCODE | TSTC |  | |

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