# `DFKKZP`

**Description:** CA Payment Plan — installment payment plan
**Category:** Standard SAP Table
**References:** 158 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `OPBEL` | | 🔑 | Primary key |
| `POSZA` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `BETRZ`, `KEYZ1`, `KLAEB`, `POSZA`, `WAERS`, `betrz`, `bldat`, `budat`, `fikey`, `infof`, `keyz1`, `opbel`, `ruear`, `selw2`, `xklae`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `bldat`, `budat`, `selw2`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0127.txt`
- `ziscrm0021.txt`
- `ziscs_migration_payment_mock3.txt`
- `zisdm0104.txt`
- `zisfi0003.txt`
- `zisfi0012.txt`
- `zisfi0015.txt`
- `zisfi0023.txt`
- `zisfi0032.txt`
- `zisfi0041.txt`
- `zisfi0093.txt`
- `zisfi0139.txt`
- `zisfi0163.txt`
- `zisfi0224.txt`
- `zisfi0252.txt`
- `zisfi0311.txt`
- `zisfi0318_lcl.txt`
- `zisfi0323_f01.txt`
- `zisfi0323_top.txt`
- `zisfi_bapi_confirm_mobile_pmt.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
