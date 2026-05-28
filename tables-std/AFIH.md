# `AFIH`

**Description:** Maintenance Order Header — PM order header
**Category:** Standard SAP Table
**References:** 45 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `AUFNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `addat`, `aufnr`, `gewrk`, `ilart`, `iloan`, `iphas`, `priok`, `qmnum`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `aufnr`, `ilart`

## Join Paths
- `AFIH.ILOA` → `EITR.ILOA` — Maint Order → Tech Location

## Programs Using This Table
- `method-check_open_order_exists.txt`
- `method-read_pmacttype.txt`
- `z_bapi_get_cl_status.txt`
- `z_bapi_isusmorder_exch.txt`
- `z_validate_n_transfer_mt.txt`
- `zisbi0104.txt`
- `ziscrm0318forms.txt`
- `ziscs0016.txt`
- `ziscs0027.txt`
- `ziscs0153.txt`
- `ziscs0229.txt`
- `ziscs0507_f01.txt`
- `ziscs1119.txt`
- `ziscs_get_digital_customer.txt`
- `zisdh0026.txt`
- `zisdm0028.txt`
- `zisdm0043.txt`
- `zisdm0050.txt`
- `zisfi0005_dun.txt`
- `zisfi0009.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
