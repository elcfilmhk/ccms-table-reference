# `EABLG`

**Description:** Installation Register History — historical register records
**Category:** Standard SAP Table
**References:** 216 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eablg/) — validated 2026-05-30, schema v1.0
**Schema fields:** 4 fields | **Data types:** CHAR(2), DATS(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `ABRDATS` | ABRDATS | — | DATS | 8 | 0 | Scheduled Billing Date |
| `ABLEINH` | ABLEINH | — | CHAR | 8 | 0 | Meter reading unit |
| `ADATSOLL` | ADATSOLL | — | DATS | 8 | 0 | Scheduled meter reading date |
| `UNTERDR` | UNTERDR | — | CHAR | 1 | 0 | Suppression indicator |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABLESGR` | EABLG | ABLESGR | TE609 |  | |
| `ANLAGE` | EABLG | MANDT | EANL |  | |
| `ANLAGE` | EABLG | ANLAGE | EANL |  | |
| `MANDT` | EABLG | MANDT | T000 |  | |

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