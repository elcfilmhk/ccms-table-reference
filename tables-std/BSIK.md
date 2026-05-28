# `BSIK`

**Description:** Accounting Document (Open) — open vendor doc
**Category:** Standard SAP Table
**References:** 5 SELECT statements across 2 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `BUKRS` | | 🔑 | Primary key |
| `LIFNR` | | 🔑 | Primary key |
| `BELNR` | | 🔑 | Primary key |
| `GJAHR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `LIFNR`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zbacbe034.txt`
- `zfchzuord_2.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
