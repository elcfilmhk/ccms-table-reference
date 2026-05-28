# `USR21`

**Description:** User Address Key — user-address mapping
**Category:** Standard SAP Table
**References:** 50 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `BNAME` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ADDRNUMBER`, `BNAME`, `MANDT`, `PERSNUMBER`, `addrnumber`, `bname`, `persnumber`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `BNAME`, `bname`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_account_mgr_by_ca.txt`
- `z_ossnote_436119_adrnum_pernum.txt`
- `zbacbe034.txt`
- `zbacotype.txt`
- `zcazze003.txt`
- `ziscrm0010f01.txt`
- `ziscrm0014.txt`
- `ziscrm0031f01.txt`
- `ziscs0031.txt`
- `ziscs0176.txt`
- `ziscs0176_adj.txt`
- `ziscs0802_f01.txt`
- `ziscs0841.txt`
- `ziscs_rep_log_exec.txt`
- `zisdm0182.txt`
- `zisdm0239f01.txt`
- `zissd00089_f01.txt`
- `zissd00100.txt`
- `zissd00101.txt`
- `zissd00110.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
