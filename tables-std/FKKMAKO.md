# `FKKMAKO`

**Description:** Direct Debit Agreement — payment method setup
**Category:** Standard SAP Table
**References:** 32 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `LAUFD` | | 🔑 | Primary key |
| `LAUFI` | | 🔑 | Primary key |
| `VKONT` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ausdt`, `gpart`, `laufd`, `laufi`, `mazae`, `vkont`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `mazae`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_check_dunning_hist.txt`
- `zisbi0097.txt`
- `zisbw0014.txt`
- `ziscs_migration_custcontact_m3.txt`
- `ziscs_migration_custcontact_m4.txt`
- `zisdm0282.txt`
- `zisfi0025.txt`
- `zisfi0040.txt`
- `zisfi0044.txt`
- `zisfi0097.txt`
- `zisfi0101.txt`
- `zisfi0106.txt`
- `zisfi0117.txt`
- `zisfi0120.txt`
- `zisfi0123.txt`
- `zisfi0139.txt`
- `zisfi0146.txt`
- `zisfi0156.txt`
- `zisfi0167.txt`
- `zisfi0272.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
