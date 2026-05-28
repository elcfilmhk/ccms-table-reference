# `DPAYP`

**Description:** Direct Debit Line — DD payment line item
**Category:** Standard SAP Table
**References:** 13 SELECT statements across 10 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `LAUFD` | | 🔑 | Primary key |
| `LAUFZ` | | 🔑 | Primary key |
| `SEQNO` | | 🔑 | Primary key |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_paymedium_cheque_refund.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zbacbt600.txt`
- `ziscs_migration_adjustment_m4.txt`
- `zisfi0028.txt`
- `zisfi0081.txt`
- `zisfi0099.txt`
- `zisfi0204.txt`
- `zisfi0238.txt`
- `zisfi0240.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
