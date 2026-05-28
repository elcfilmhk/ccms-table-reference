# `EBAN`

**Description:** Purchase Requisition — purchase requisition
**Category:** Standard SAP Table
**References:** 16 SELECT statements across 9 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `BANFN` | | 🔑 | Primary key |
| `BNFPO` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ADRN2`, `ADRNR`, `ADVCODE`, `AFNAM`, `AKTNR`, `ARSNR`, `ARSPS`, `ATTYP`, `BADAT`, `BANFN`, `BANFN_CS`, `BANPR`, `BATOL`, `BEDAT`, `BEDNR`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zissd00040.txt`
- `zissd00072.txt`
- `zissd00079.txt`
- `zissd00081.txt`
- `zissd00086.txt`
- `zissd00098.txt`
- `zissd00108.txt`
- `zmmprsi01.txt`
- `zmmprsi13.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
