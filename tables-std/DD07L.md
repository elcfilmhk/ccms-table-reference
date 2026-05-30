# `DD07L`

**Description:** Fixed Values — domain fixed values
**Category:** Standard SAP Table
**References:** 3 SELECT statements across 3 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dd07l/) — validated 2026-05-30, schema v1.0
**Schema fields:** 3 fields | **Data types:** CHAR(3)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `DOMVALUE_L` | DOMVALUE_L | — | CHAR | 10 | 0 | Values for Domains: Single Value / Upper Limit |
| `DOMVALUE_H` | DOMVALUE_H | — | CHAR | 10 | 0 | Values for domains, upper limit |
| `APPVAL` | DDAPPVAL | — | CHAR | 1 | 0 | DD: Defines whether value of appender belongs to append |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `DOMNAME` | DD07L | DOMNAME | DD01L |  | |
| `DOMNAME` | * |  | DD01L |  | |
| `DOMNAME` | * |  | DD01L |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `ziscs0083.txt`
- `zisfi0197.txt`
- `zisfi0197_smis.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_