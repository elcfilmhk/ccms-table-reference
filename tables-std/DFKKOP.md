# `DFKKOP`

**Description:** CA Open Item — open item line in FI-CA
**Category:** Standard SAP Table
**References:** 951 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `OPBEL` | | 🔑 | Primary key |
| `OPUPK` | | 🔑 | Primary key |
| `OPUPZ` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ABRZO`, `ABRZU`, `ABWBL`, `ABWTP`, `AUGBD`, `AUGBL`, `AUGBT`, `AUGDT`, `AUGRD`, `AUGRS`, `AUGST`, `BETRH`, `BETRW`, `BLART`, `BLDAT`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `AUGBL`, `AUGST`, `BETRH`, `augbl`, `augdt`, `augst`, `bukrs`, `opbel`, `stakz`, `tvorg`, `vkont`

## Join Paths
- `DFKKOP.OPBEL` → `DFKKKO.OPBEL` — Open Item → Doc Header

## Programs Using This Table
- `z_bapi_get_duedate.txt`
- `z_bapi_simple_accinfo.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zfi_insert_locks_to_openitem.txt`
- `zisbi0201_tp.txt`
- `ziscs_migration_deposit_mock3.txt`
- `zisfi0003.txt`
- `zisfi0005_dun.txt`
- `zisfi0069.txt`
- `zisfi0082.txt`
- `zisfi0083.txt`
- `zisfi0083_1t.txt`
- `zisfi0116_test3.txt`
- `zisfi0124.txt`
- `zisfi0132.txt`
- `zisfi0139.txt`
- `zisfi0142.txt`
- `zisfi0207.txt`
- `zisfi0235.txt`
- `zisfi0258.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
