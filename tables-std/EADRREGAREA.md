# `EADRREGAREA`

**Description:** SAP standard table
**Category:** Standard SAP Table
**References:** 1 SELECT statements across 1 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eadrregarea/) — validated 2026-05-30, schema v1.0
**Schema fields:** 3 fields | **Data types:** CHAR(1), CLNT(1), NUMC(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `CLIENT` | MANDT | T000 | CLNT | 3 | 0 | Client |
| `ROLE` | ISUROLE | HRS1000 | NUMC | 8 | 0 | Role |
| `REGIOAREA` | REGIOAREA | — | CHAR | 8 | 0 | Regional structure area |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CLIENT` | EADRREGAREA | CLIENT | T000 |  | |
| `ROLE` | &#039;AC&#039; |  | HRS1000 |  | |
| `ROLE` | EADRREGAREA | ROLE | HRS1000 |  | |
| `ROLE` | SY | LANGU | HRS1000 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0007.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_