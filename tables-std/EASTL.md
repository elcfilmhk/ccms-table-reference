# `EASTL`

**Description:** Installation Rate Schedule — rate tariff assignment
**Category:** Standard SAP Table
**References:** 182 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eastl/) — validated 2026-05-30, schema v1.0
**Schema fields:** 10 fields | **Data types:** CHAR(7), DATS(3)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `AB` | ABZEITSCH | — | DATS | 8 | 0 | Date from which time slice is valid |
| `PREISKLA` | PREISKLA | TE431 | CHAR | 10 | 0 | Price Class |
| `GVERRECH` | GVERRECH | — | CHAR | 1 | 0 | Pay rental price |
| `TARIFART` | TARIFART | — | CHAR | 8 | 0 | Rate Type |
| `KONDIGR` | KONDIGR | — | CHAR | 10 | 0 | Rate fact group |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `DEVICE_NBR` | E_DEVICE_NBR | — | CHAR | 1 | 0 | Device Not Relevant for Billing |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `PREISKLA` | EASTL | MANDT | TE431 |  | |
| `PREISKLA` | EASTL | PREISKLA | TE431 |  | |

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