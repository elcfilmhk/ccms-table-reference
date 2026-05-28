# `VIAUFKST`

**Description:** Order Tracking — order status tracking
**Category:** Standard SAP Table
**References:** 59 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `AUFNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `addat`, `aedat`, `auart`, `aufnr`, `erdat`, `erfzeit`, `ernam`, `gewrk`, `ilart`, `ingpr`, `iphas`, `loekz`, `objnr`, `priok`, `qmnum`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `auart`, `erdat`, `ingpr`

## Join Paths
- `VIAUFKST.AUFNR` → `AUFK.AUFNR` — WO Tracking → Order
- `VIAUFKST.OBJNR` → `JEST.OBJNR` — WO Tracking → Status

## Programs Using This Table
- `z_bapi_get_cl_status.txt`
- `z_bapi_get_ft_status.txt`
- `z_bapi_get_mi_status.txt`
- `z_bapi_get_track_cl.txt`
- `z_bapi_get_track_mi.txt`
- `zdiscon.txt`
- `zisbi0013.txt`
- `ziscs0026.txt`
- `ziscs0026a.txt`
- `ziscs0039.txt`
- `ziscs0157.txt`
- `ziscs0176.txt`
- `ziscs0176_adj.txt`
- `ziscs0200.txt`
- `ziscs0209_f01.txt`
- `ziscs0287.txt`
- `ziscs0328.txt`
- `ziscsriaufk20.txt`
- `zisfi0030.txt`
- `zisfi0038.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
