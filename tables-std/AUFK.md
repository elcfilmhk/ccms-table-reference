# `AUFK`

**Description:** Order Header — maintenance/service order
**Category:** Standard SAP Table
**References:** 88 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `AUFNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AUART`, `AUFNR`, `ERDAT`, `IDAT2`, `LOEKZ`, `OBJNR`, `adrnra`, `aedat`, `auart`, `aufnr`, `idat2`, `objnr`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `auart`, `aufnr`, `idat2`

## Join Paths
- `AUFK.AUFNR` → `AFIH.AUFNR` — Order → Maintenance Order

## Programs Using This Table
- `method-read_serv_ord_stat_info.txt`
- `z_bapi_get_cl_status.txt`
- `z_bapi_updateso.txt`
- `zdiscon.txt`
- `zggbr000.txt`
- `zisbi0013.txt`
- `zisbi0186.txt`
- `ziscrm0318forms.txt`
- `ziscs0002.txt`
- `ziscs0007.txt`
- `ziscs0014.txt`
- `ziscs0014_adj.txt`
- `ziscs0021.txt`
- `ziscs0341.txt`
- `ziscs1119.txt`
- `zisdm0051.txt`
- `zisdm0175.txt`
- `zisdm0297_sub.txt`
- `zisdm_so_approval_f01.txt`
- `zrpm_mwfm_so_create.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
