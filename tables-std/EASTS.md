# `EASTS`

**Description:** Installation Schedule — scheduled tariff/rate periods
**Category:** Standard SAP Table
**References:** 339 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/easts/) — validated 2026-05-30, schema v1.0
**Schema fields:** 12 fields | **Data types:** CHAR(9), DATS(3)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `AB` | ABZEITSCH | — | DATS | 8 | 0 | Date from which time slice is valid |
| `ZWNABR` | E_ZWNABR | — | CHAR | 1 | 0 | Register not relevant to billing |
| `GVERRECH` | GVERRECH | — | CHAR | 1 | 0 | Pay rental price |
| `TARIFART` | TARIFART | TE069 | CHAR | 8 | 0 | Rate Type |
| `KONDIGR` | KONDIGR | — | CHAR | 10 | 0 | Rate fact group |
| `RABZUS` | RABZUS | EDSC | CHAR | 10 | 0 | Discount key |
| `PREISKLA` | PREISKLA | TE431 | CHAR | 10 | 0 | Price Class |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `ZWNSETTL` | E_ZWNSETTL | — | CHAR | 1 | 0 | Register not relevant to settlement |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MANDT` | EASTS | MANDT | T000 |  | |
| `PREISKLA` | EASTS | PREISKLA | TE431 |  | |
| `PREISKLA` | EASTS | MANDT | TE431 |  | |
| `RABZUS` | EASTS | MANDT | EDSC |  | |
| `RABZUS` | EASTS | RABZUS | EDSC |  | |
| `TARIFART` | EASTS | MANDT | TE069 |  | |
| `TARIFART` | EASTS | TARIFART | TE069 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AB`, `ANLAGE`, `BIS`, `LOGIKZW`, `TARIFART`, `ZWNABR`, `ab`, `aedat`, `anlage`, `bis`, `erdat`, `ernam`, `logikzw`, `tarifart`, `zwnabr`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ANLAGE`, `aedat`, `anlage`, `bis`, `logikzw`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_iscrm_check_ami_end.txt`
- `z_iscrm_check_ami_mo.txt`
- `z_isdm_get_ami_effective_date.txt`
- `z_isdm_lpb_ready_check.txt`
- `zisbi0017.txt`
- `ziscs0031.txt`
- `ziscs0273.txt`
- `zisdm0091.txt`
- `zisdm0116.txt`
- `zisdm0159.txt`
- `zisdm0169.txt`
- `zisdm0170.txt`
- `zisdm0201.txt`
- `zisdm0201_sub_lp.txt`
- `zisdm0215.txt`
- `zisdm0282.txt`
- `zisdm0307.txt`
- `zisdm0332.txt`
- `zisdm_bapi_profval_avail_pct.txt`
- `zrvee_pre_bill_validation.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_