# `EASTI`

**Description:** SAP standard table
**Category:** Standard SAP Table
**References:** 12 SELECT statements across 6 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/easti/) — validated 2026-05-30, schema v1.0
**Schema fields:** 4 fields | **Data types:** CHAR(1), DATS(1), NUMC(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `AB` | ABZEITSCH | — | DATS | 8 | 0 | Date from which time slice is valid |
| `ZWZUART` | E_ZWZUART | — | NUMC | 2 | 0 | Register relationship type |
| `OPCODE` | E_OPCODE | — | NUMC | 2 | 0 | Operation code: Role of register in relationship |
| `ONLY_BILLING_REL` | ONLY_BILLING_REL | — | CHAR | 1 | 0 | Read together only if MR reason triggers billing |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AB`, `BIS`, `INDEXNR`, `LOGIKZW`, `indexnr`, `logikzw`, `opcode`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `indexnr`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_isdm_get_meter_relationship.txt`
- `zisdm0022_bulk.txt`
- `zisdm0024.txt`
- `zisdm0036.txt`
- `zisdm0216f01.txt`
- `zisdm0307.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_