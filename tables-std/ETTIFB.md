# `ETTIFB`

**Description:** Installation Billing Item — billing line items
**Category:** Standard SAP Table
**References:** 10 SELECT statements across 7 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `ANLAGE` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `anlage`, `bis`, `operand`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `anlage`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0016.txt`
- `zisbi0025.txt`
- `zisbi0025_1.txt`
- `zisbi0105.txt`
- `ziscs0049.txt`
- `ziscs_migration_unmetered_sp.txt`
- `zreprjt00.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
