# `JEST`

**Description:** Object Status — system status entries
**Category:** Standard SAP Table
**References:** 79 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/jest/) — validated 2026-05-30, schema v1.0
**Schema fields:** 2 fields | **Data types:** CHAR(1), NUMC(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `INACT` | J_INACT | — | CHAR | 1 | 0 | Indicator: Status Is Inactive |
| `CHGNR` | J_CHGNR | — | NUMC | 3 | 0 | Change number |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MANDT` | JEST | MANDT | T000 |  | |
| `OBJNR` | JEST | MANDT | ONR00 |  | |
| `OBJNR` | JEST | OBJNR | ONR00 |  | |

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