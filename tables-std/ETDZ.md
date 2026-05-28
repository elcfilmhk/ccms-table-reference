# `ETDZ`

**Description:** Technical Register Data — meter reading register data
**Category:** Standard SAP Table
**References:** 240 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `EQUNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AB`, `BIS`, `EQUNR`, `LOGIKZW`, `ZWNUMMER`, `ab`, `aedat`, `aenam`, `bis`, `equnr`, `erdat`, `ernam`, `intsizeID`, `intsizeid`, `kennziff`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `EQUNR`, `LOGIKZW`, `ab`, `bis`, `equnr`, `logikzw`

## Join Paths
- `ETDZ.EQUNR` → `EQUI.EQUNR` — Tech Register → Equipment

## Programs Using This Table
- `z_bi_lp_prof_val.txt`
- `ziscs0149.txt`
- `ziscs0534_f01.txt`
- `ziscs0717_form.txt`
- `zisdm0022f01.txt`
- `zisdm0086.txt`
- `zisdm0091.txt`
- `zisdm0136c.txt`
- `zisdm0136d.txt`
- `zisdm0170.txt`
- `zisdm0172.txt`
- `zisdm0215.txt`
- `zisdm0231.txt`
- `zisdm0307.txt`
- `zisdm0427.txt`
- `zisdm_bapi_profval_avail_pct.txt`
- `zisem0004.txt`
- `zrca_ssr_extract.txt`
- `zrmig_recon_report.txt`
- `zwfm_get_mr_order_details.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
