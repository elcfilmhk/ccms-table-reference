# `EASTS`

**Description:** Installation Schedule — scheduled tariff/rate periods
**Category:** Standard SAP Table
**References:** 339 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `ANLAGE` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AB`, `ANLAGE`, `BIS`, `LOGIKZW`, `TARIFART`, `ZWNABR`, `ab`, `aedat`, `anlage`, `bis`, `erdat`, `ernam`, `logikzw`, `tarifart`, `zwnabr`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ANLAGE`, `aedat`, `anlage`, `bis`, `logikzw`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_iscrm_check_ami_end.txt`
- `z_iscrm_check_ami_mo.txt`
- `z_isdm_get_ami_effective_date.txt`
- `z_isdm_lpb_ready_check.txt`
- `zisbi0017.txt`
- `ziscs0031.txt`
- `ziscs0273.txt`
- `zisdm0091.txt`
- `zisdm0116.txt`
- `zisdm0159.txt`
- `zisdm0169.txt`
- `zisdm0170.txt`
- `zisdm0201.txt`
- `zisdm0201_sub_lp.txt`
- `zisdm0215.txt`
- `zisdm0282.txt`
- `zisdm0307.txt`
- `zisdm0332.txt`
- `zisdm_bapi_profval_avail_pct.txt`
- `zrvee_pre_bill_validation.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
