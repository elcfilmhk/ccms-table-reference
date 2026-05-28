# `EVBS`

**Description:** Premise — premise/installation location
**Category:** Standard SAP Table
**References:** 317 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VSTELLE` | | 🔑 | Primary key |
| `HAUS` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ERDAT`, `HAU`, `HAUS`, `STR_ERG2`, `VSTELLE`, `aedat`, `erdat`, `floor`, `haus`, `haus_num2`, `loevm`, `roomnumber`, `str_erg2`, `str_erg4`, `vbsart`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `VSTELLE`, `haus`, `loevm`, `vstelle`

## Join Paths
- `EVBS.HAUS` → `EHAUISU.HAUS` — Premise → Connection Object

## Programs Using This Table
- `z_adms_ccms_call_take.txt`
- `z_adms_ccms_cust_query_1a.txt`
- `z_bapi_get_deposit.txt`
- `z_bapi_simple_accinfo.txt`
- `z_iscs_suppressmovein.txt`
- `z_isdm_get_premise_ext.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `zisbi0011.txt`
- `ziscs0048.txt`
- `ziscs0068.txt`
- `ziscs0116.txt`
- `ziscs0125.txt`
- `ziscs0150.txt`
- `ziscs0184.txt`
- `ziscs0251.txt`
- `ziscs0368.txt`
- `zisdm0015f02.txt`
- `zisdm0091.txt`
- `zisdm0116.txt`
- `zismd0002.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
