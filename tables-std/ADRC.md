# `ADRC`

**Description:** Address — address master data
**Category:** Standard SAP Table
**References:** 276 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `CLIENT` | | 🔑 | Primary key |
| `ADDRNUMBER` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ADDRNUMBER`, `CITY2`, `HOUSE_NUM1`, `NATION`, `STREET`, `STR_SUPPL1`, `STR_SUPPL2`, `addrnumber`, `city1`, `city2`, `country`, `date_from`, `date_to`, `floor`, `house_num1`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `nation`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_mo_status.txt`
- `z_get_chin_supply_address_ws.txt`
- `z_get_supply_address_ws.txt`
- `zisbi0011.txt`
- `ziscrm0048.txt`
- `ziscs0031.txt`
- `ziscs0088.txt`
- `ziscs0108.txt`
- `ziscs0150.txt`
- `ziscs0151.txt`
- `ziscs0195.txt`
- `ziscs0207.txt`
- `ziscs0243.txt`
- `ziscs0525_f01.txt`
- `ziscs0805_f01.txt`
- `ziscsriaufk20.txt`
- `zisdm0135.txt`
- `zisfi0131.txt`
- `zisfi0132.txt`
- `zissd00076.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
