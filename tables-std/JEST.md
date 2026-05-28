# `JEST`

**Description:** Object Status — system status entries
**Category:** Standard SAP Table
**References:** 79 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `OBJNR` | | 🔑 | Primary key |
| `STAT` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `INACT`, `OBJNR`, `STAT`, `inact`, `objnr`, `stat`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `OBJNR`, `objnr`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_ft_status.txt`
- `z_bapi_iia_change_a.txt`
- `z_bapi_iia_dates_getlist_d.txt`
- `z_bapi_srvord_chg.txt`
- `z_isdm_get_meter_reg.txt`
- `z_isu_create_order.txt`
- `zisbi0025.txt`
- `zisbi0025_1.txt`
- `ziscs0002.txt`
- `ziscs0005.txt`
- `ziscs0007.txt`
- `ziscs0021.txt`
- `ziscs0283.txt`
- `ziscs0355.txt`
- `zisdm0022_bulk.txt`
- `zisdm0050.txt`
- `zisdm0069.txt`
- `zisdm0133.txt`
- `zrdm_ami_devmod.txt`
- `zredm_prof_stat_qual.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
