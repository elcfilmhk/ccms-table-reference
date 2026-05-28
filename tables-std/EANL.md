# `EANL`

**Description:** Installation — premise/installation master
**Category:** Standard SAP Table
**References:** 499 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `ANLAGE` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ABLSPERR`, `ANLAGE`, `VST`, `VSTELLE`, `ableinh`, `ablesartst`, `ablsperr`, `anlage`, `anlart`, `bis`, `erdat`, `loevm`, `sparte`, `spebene`, `tariftyp`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ANLAGE`, `ablsperr`, `anlage`, `loevm`, `vstelle`

## Join Paths
- `EANL.ANLAGE` → `EANLH.ANLAGE` — Installation → History
- `EANL.VSTELLE` → `EVBS.VSTELLE` — Installation → Premise
- `EANL.EQUNR` → `EQUI.EQUNR` — Installation → Equipment

## Programs Using This Table
- `z_bapi_get_deposit.txt`
- `z_bapi_get_mr_info_by_premise.txt`
- `z_bapi_get_track_result_mi.txt`
- `z_bapi_zsr_popup.txt`
- `z_check_meter_type.txt`
- `z_iscs_wis_prem_info.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `zisbi0033.txt`
- `ziscs0014.txt`
- `ziscs0031.txt`
- `ziscs0151.txt`
- `ziscs0315f01.txt`
- `zisdm0015f02.txt`
- `zisdm0020.txt`
- `zisdm0025.txt`
- `zisdm0067.txt`
- `zisdm0135.txt`
- `zisdm0177.txt`
- `zisdm0261.txt`
- `zsdsoc001.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
