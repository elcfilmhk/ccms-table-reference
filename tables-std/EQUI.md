# `EQUI`

**Description:** Equipment — equipment master
**Category:** Standard SAP Table
**References:** 425 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `EQUNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `EQUNR`, `OBJNR`, `SERNR`, `aedat`, `aenam`, `eqart`, `equnr`, `erdat`, `ernam`, `groes`, `herst`, `invnr`, `matnr`, `objnr`, `sernr`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `SERNR`, `aedat`, `equnr`, `erdat`, `matnr`, `sernr`

## Join Paths
- `EQUI.EQUNR` → `EGPL.EQUNR` — Equipment → Device

## Programs Using This Table
- `z_iscs_update_meter_so.txt`
- `z_isdm_create_grpbill_chkread.txt`
- `z_isdm_lpb_ready_check.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `ziscs0273.txt`
- `zisdatveri.txt`
- `zisdm0091.txt`
- `zisdm0130.txt`
- `zisdm0152.txt`
- `zisdm0169.txt`
- `zisdm0191.txt`
- `zisdm0235_sub.txt`
- `zisdm0282.txt`
- `zisdm0316.txt`
- `zisdm0382.txt`
- `zisdm0394.txt`
- `zisdm_mru_smp_conn_status.txt`
- `zisem0004.txt`
- `zismd0037_extract.txt`
- `zwfm_get_mr_order_details.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
