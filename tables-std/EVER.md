# `EVER`

**Description:** Contract — master contract between customer and utility
**Category:** Standard SAP Table
**References:** 1628 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `VKONTO` | | 🔑 | Primary key |
| `VERTRAG` | | 🔑 | Primary key |
| `ANLAGE` | | 🔑 | Primary key |
| `MANDT` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ANL`, `ANLAGE`, `AUSZDAT`, `EINZDAT`, `EINZDAT_ALT`, `LOEVM`, `STAGRUVER`, `VERTRAG`, `VKO`, `VKONTO`, `ZZFIXDATE`, `abrsperr`, `aedat`, `anlage`, `auszdat`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ANLAGE`, `AUSZDAT`, `LOEVM`, `VERTRAG`, `VKONTO`, `anlage`, `auszdat`, `erdat`, `loevm`, `stagruver`, `vertrag`, `vkonto`

## Join Paths
- `EVER.VKONTO` → `FKKVKP.VKONT` — Contract → CA
- `EVER.ANLAGE` → `EANL.ANLAGE` — Contract → Installation

## Programs Using This Table
- `z_bapi_get_bp_id.txt`
- `z_iscs_wis_prem_info.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `zisbi0033.txt`
- `zisbi0119.txt`
- `zisbi0219f01.txt`
- `ziscs0083.txt`
- `ziscs0151.txt`
- `ziscs0807.txt`
- `zisdm0020.txt`
- `zisdm0169.txt`
- `zisdm0358.txt`
- `zisfi0036.txt`
- `zisfi0039.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test3.txt`
- `zisfi0207.txt`
- `zrcs_remove_cons_af.txt`
- `zsdsoc001.txt`
- `zwfm_get_mr_order_details.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
