# `EABLG`

**Description:** Installation Register History — historical register records
**Category:** Standard SAP Table
**References:** 216 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `ABLBELNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ABLBELNR`, `ABLESGR`, `ADATSOLL`, `ANLAGE`, `ablbelnr`, `ableinh`, `ablesgr`, `abrdats`, `adatsoll`, `anlage`, `unterdr`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ANLAGE`, `ablbelnr`, `ableinh`, `ablesgr`, `abrdats`, `anlage`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `ziscs0023.txt`
- `ziscs0184.txt`
- `ziscs0207.txt`
- `ziscs0273.txt`
- `zisdh0026.txt`
- `zisdm0091.txt`
- `zisdm0136c.txt`
- `zisdm0159.txt`
- `zisdm0170.txt`
- `zisdm0177.txt`
- `zisdm0183.txt`
- `zisdm0278.txt`
- `zisdm0332.txt`
- `zismd0038_extract.txt`
- `zismd0038_recon.txt`
- `zisuorder.txt`
- `zrdm_us_rep.txt`
- `zrvee_pre_bill_validation.txt`
- `ztectest1.txt`
- `zwfm_get_mr_order_details.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
