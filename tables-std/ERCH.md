# `ERCH`

**Description:** Billing Document — invoice/bill header
**Category:** Standard SAP Table
**References:** 301 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `BELNR` | | 🔑 | Primary key |
| `GJAHR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ABRVORG`, `AEDAT`, `BCREASON`, `BELEGART`, `BELNR`, `ENDABRPE`, `ERDAT`, `HVORG`, `SC_BELNR_H`, `SC_BELNR_N`, `TOBRELEASD`, `VERTRAG`, `VKONT`, `ableinh`, `abrdats`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `BELEGART`, `BELNR`, `VERTRAG`, `ableinh`, `abrvorg`, `belnr`, `endabrpe`, `erdat`, `vertrag`, `vkont`

## Join Paths
- `ERCH.BELNR` → `ERCHC.BELNR` — Bill Doc → Bill Doc Line
- `ERCH.OPBEL` → `ERDK.OPBEL` — Bill Doc → FI-CA Doc

## Programs Using This Table
- `z_iscrm_check_ami_end.txt`
- `z_select_rfi38_data.txt`
- `zisbi0011.txt`
- `zisbi0057.txt`
- `zisbi0091.txt`
- `zisbi0099.txt`
- `zisbi0110.txt`
- `zisbi0214f01.txt`
- `zisbi0224_status_0200o01.txt`
- `zisbi0226_f01.txt`
- `zisbi239f01.txt`
- `zisbi_upd_ind.txt`
- `zisdm0089.txt`
- `zisdm0091.txt`
- `zisdm0170.txt`
- `zisdm0172.txt`
- `zisdm0183.txt`
- `zisdm0201.txt`
- `zisdm0278.txt`
- `zisfi0113_upd.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
