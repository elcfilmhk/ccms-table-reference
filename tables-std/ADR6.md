# `ADR6`

**Description:** Email Address — email addresses
**Category:** Standard SAP Table
**References:** 48 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `CLIENT` | | 🔑 | Primary key |
| `ADDRNUMBER` | | 🔑 | Primary key |
| `PERSNUMBER` | | 🔑 | Primary key |
| `CONSNUMBER` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `addrnumber`, `consnumber`, `date_from`, `flgdefault`, `persnumber`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `addrnumber`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_account_mgr_by_ca.txt`
- `z_wy_lfa1_single_read.txt`
- `zisbi0120.txt`
- `ziscrm0014.txt`
- `ziscs0151.txt`
- `ziscs0195.txt`
- `ziscs0297.txt`
- `ziscs0351f01.txt`
- `ziscs0467.txt`
- `ziscs0807_test_radica_f01.txt`
- `ziscv06a.txt`
- `ziscv08nv_f01.txt`
- `ziscv09_f01.txt`
- `zisdm0172.txt`
- `zisdm0356_form.txt`
- `zissd00089_f01.txt`
- `zissd00100.txt`
- `zmmprsi01.txt`
- `zsdbidl01.txt`
- `ztecfaxchg.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
