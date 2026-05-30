# `JCDS`

**Description:** Status Profile — status change log
**Category:** Standard SAP Table
**References:** 20 SELECT statements across 9 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/jcds/) — validated 2026-05-30, schema v1.0
**Schema fields:** 7 fields | **Data types:** CHAR(5), DATS(1), TIMS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `USNAM` | CDUSERNAME | — | CHAR | 12 | 0 | User name of the person responsible in change document |
| `UDATE` | CDDATUM | — | DATS | 8 | 0 | Creation date of the change document |
| `UTIME` | CDUZEIT | — | TIMS | 6 | 0 | Time changed |
| `TCODE` | OLD_TCODE | — | CHAR | 4 | 0 | Transaction code |
| `CDTCODE` | CDTCODE | TSTC | CHAR | 20 | 0 | Transaction in which a change was made |
| `INACT` | J_INACT | — | CHAR | 1 | 0 | Indicator: Status Is Inactive |
| `CHIND` | J_CHIND | — | CHAR | 1 | 0 | Change Indicator |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CDTCODE` | JCDS | CDTCODE | TSTC |  | |
| `MANDT` | JCDS | MANDT | T000 |  | |
| `OBJNR` | JCDS | MANDT | JEST |  | |
| `OBJNR` | JCDS | OBJNR | JEST |  | |
| `OBJNR` | JCDS | STAT | JEST |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0173.txt`
- `ziscs0014.txt`
- `ziscs0014_adj.txt`
- `ziscs0039.txt`
- `ziscs0287.txt`
- `ziscs0340.txt`
- `ziscs0341.txt`
- `zisdm0080.txt`
- `zisdm0089.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_