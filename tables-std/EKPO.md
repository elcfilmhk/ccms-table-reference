# `EKPO`

**Description:** Purchasing Document Item — PO item
**Category:** Standard SAP Table
**References:** 42 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `EBELN` | | 🔑 | Primary key |
| `EBELP` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AEDAT`, `ANFNR`, `ANFPS`, `BANFN`, `BNFPO`, `BPRME`, `BRTWR`, `EBELN`, `EBELP`, `KNTTP`, `KONNR`, `KTPNR`, `LGORT`, `LMEIN`, `LOEKZ`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `EBELN`, `LOEKZ`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_create_ekrs.txt`
- `zdemo.txt`
- `ziscs0120.txt`
- `zissd00031.txt`
- `zissd00041.txt`
- `zissd00079.txt`
- `zissd00081.txt`
- `zissd00086.txt`
- `zissd00096.txt`
- `zissd00097.txt`
- `zissd00098.txt`
- `zissd00099.txt`
- `zissd00103.txt`
- `zissd00108.txt`
- `zissd00111.txt`
- `zmmpri000.txt`
- `zmmpri001.txt`
- `zmmprsi01.txt`
- `zsdsodl02.txt`
- `zsdsodl06.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
