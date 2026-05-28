# `ETTIFN`

**Description:** Installation Billing Index — billing history index
**Category:** Standard SAP Table
**References:** 145 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `ANLAGE` | | 🔑 | Primary key |
| `BELNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AB`, `ANLAGE`, `BELNR`, `BETRAG`, `BIS`, `INAKTIV`, `OPERAND`, `WAERS`, `WERT1`, `ab`, `anlage`, `belnr`, `bis`, `inaktiv`, `operand`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ANLAGE`, `anlage`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_bill_csmpt.txt`
- `z_calculate_deposit.txt`
- `z_isdm_get_ami_effective_date.txt`
- `zeedm_ptr.txt`
- `zisbi0026.txt`
- `zisbi0151.txt`
- `zisbiami_calc_bill_costs.txt`
- `zisbw0021.txt`
- `ziscs0090.txt`
- `ziscs0121.txt`
- `ziscs0252f01.txt`
- `ziscsami_get_billing_period.txt`
- `ziscseec_get_adjacent_bills.txt`
- `zisdatveri.txt`
- `zisdm0058.txt`
- `zisdm0089.txt`
- `zisdm0104.txt`
- `zisdm0170.txt`
- `zisdm0278.txt`
- `zreprjt00.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
