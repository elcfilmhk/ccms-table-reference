# `EASTL`

**Description:** Installation Rate Schedule — rate tariff assignment
**Category:** Standard SAP Table
**References:** 182 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `ANLAGE` | | 🔑 | Primary key |
| `LOGIKNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AB`, `ANLAGE`, `BIS`, `LOGIKNR`, `ab`, `anlage`, `bis`, `logiknr`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ANLAGE`, `LOGIKNR`, `anlage`, `bis`, `logiknr`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `method-eligibility_check.txt`
- `z_iscrm_check_ami_end.txt`
- `z_iscrm_check_ami_mo.txt`
- `ziscs0023.txt`
- `ziscs0108.txt`
- `ziscs0184.txt`
- `ziscs0207.txt`
- `ziscs0254.txt`
- `ziscs0273.txt`
- `ziscs0525_f01.txt`
- `zisdm0091.txt`
- `zisdm0129.txt`
- `zisdm0130.txt`
- `zisdm0135.txt`
- `zisdm0169.txt`
- `zisdm0170.txt`
- `zisdm0177.txt`
- `zisdm0254.txt`
- `zrdm_us_rep.txt`
- `zrvee_pre_bill_validation.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
