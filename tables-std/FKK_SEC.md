# `FKK_SEC`

**Description:** Security Deposit — CA security deposit
**Category:** Standard SAP Table
**References:** 109 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VKONT` | | 🔑 | Primary key |
| `SECID` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ACC`, `NON_CASH`, `SECURITY`, `VKONT`, `aedat`, `aenam`, `ernam`, `non_cash`, `objkey`, `objtype`, `opbel`, `reason`, `rev_reason`, `sec_return`, `sec_start`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `VKONT`, `vkont`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_calculate_deposit.txt`
- `z_isu_event_0830.txt`
- `z_sec_rep_rel.txt`
- `zis_security_deposit.txt`
- `zisbi0030.txt`
- `ziscs_migration_deposit_mock3.txt`
- `zisdatveri.txt`
- `zisfi0010.txt`
- `zisfi0025_corr_print.txt`
- `zisfi0039.txt`
- `zisfi0041.txt`
- `zisfi0052.txt`
- `zisfi0093.txt`
- `zisfi0101.txt`
- `zisfi0132.txt`
- `zisfi0158.txt`
- `zisfi0159.txt`
- `zisfi0165.txt`
- `zisfi0214.txt`
- `zisfi0217.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
