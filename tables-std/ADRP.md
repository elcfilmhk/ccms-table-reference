# `ADRP`

**Description:** Address Person — person master data
**Category:** Standard SAP Table
**References:** 9 SELECT statements across 8 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `CLIENT` | | 🔑 | Primary key |
| `PERSNUMBER` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `name_text`, `persnumber`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_ossnote_445575.txt`
- `ziscv08_f01.txt`
- `ziscv08nv_f01.txt`
- `ziscv08nv_test_f01.txt`
- `zisdm0239f01.txt`
- `zissd00089_f01.txt`
- `zmmpre030s.txt`
- `zmmprsi01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
