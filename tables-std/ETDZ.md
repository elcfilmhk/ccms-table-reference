# `ETDZ`

**Description:** Technical Register Data — meter reading register data
**Category:** Standard SAP Table
**References:** 240 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/etdz/) — validated 2026-05-30, schema v1.0
**Schema fields:** 40 fields | **Data types:** CHAR(17), DATS(3), DEC(11), NUMC(7), UNIT(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `AB` | ABZEITSCH | — | DATS | 8 | 0 | Date from which time slice is valid |
| `LOGIKZW` | LOGIKZW | — | NUMC | 18 | 0 | Logical register number |
| `SPARTYP` | SPARTYP | — | NUMC | 2 | 0 | Division category |
| `ZWKENN` | E_ZWKENN | TE065 | CHAR | 2 | 0 | Register identification |
| `KENNZIFF` | KENNZIFF | — | CHAR | 15 | 0 | Code for Identifying a Register |
| `ZWART` | E_ZWART | TE523 | CHAR | 2 | 0 | Register type |
| `ZWFAKT` | E_ZWFAKT | — | DEC | 12 | 5 | Register factor |
| `STANZVOR` | STANZVOR | — | NUMC | 2 | 0 | Places before the decimal point in a register |
| `STANZNAC` | STANZNAC | — | NUMC | 2 | 0 | Places after the decimal in a register |
| `ZWTYP` | E_ZWTYP | — | NUMC | 2 | 0 | Register category |
| `BLIWIRK` | BLIWIRK | — | NUMC | 2 | 0 | Reactive, apparent, or active registers |
| `MASSREAD` | E_MASSREAD | — | UNIT | 3 | 0 | Unit of measurement for meter reading |
| `ANZERG` | ANZERG | — | DEC | 2 | 0 | Number of meter reading results per meter reading |
| `KZMESSW` | KZMESSW | — | CHAR | 1 | 0 | Nonmetering register |
| `UEBERVER` | UEBERVER | — | DEC | 10 | 3 | Transformation ratio |
| `STEUERGRP` | STEUERGRP | — | CHAR | 4 | 0 | Control group for multiple meter reading order creation |
| `NABLESEN` | E_NABLESEN | — | CHAR | 1 | 0 | Do Not Read Register |
| `PRUEFKL` | PRUEFKL | — | CHAR | 4 | 0 | Validation class for independent validations |
| `TEMP_AREA` | TEMP_AREA | TE307 | CHAR | 8 | 0 | Temperature area |
| `PR_AREA_AI` | PR_AREA_AI | TE309 | CHAR | 8 | 0 | Air pressure area |
| `CALOR_AREA` | CALOR_AREA | TE453 | CHAR | 8 | 0 | Calorific value district |
| `HOEKORR` | HOEKORR | — | DEC | 7 | 5 | Altitude correction pressure |
| `THGBER` | THGBER | — | CHAR | 2 | 0 | Inclusion of factors in thermal gas billing |
| `KZAHLE` | KZAHLE | — | DEC | 7 | 5 | Gas law deviation factor (set) |
| `KZAHLT` | KZAHLT | — | DEC | 7 | 5 | Actual gas law deviation factor |
| `GAS_PRS_AR` | GAS_PRS_AR | TE343 | CHAR | 8 | 0 | Gas Pressure Area |
| `CRGPRESS` | CRGPRESS | — | DEC | 7 | 4 | Gas correction pressure |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `MASSBILL` | E_MASSBILL | — | UNIT | 3 | 0 | Unit of measurement for billing |
| `GEWKEY` | GEWKEY | — | CHAR | 8 | 0 | Weighting key |
| `ZSPANNS` | E_ZSPANNS | — | DEC | 4 | 1 | Register factor: secondary transformer voltage |
| `ZSTROMS` | E_ZSTROMS | — | DEC | 5 | 2 | Register factor: secondary transformer current |
| `ZSPANNP` | E_ZSPANNP | — | DEC | 6 | 0 | Register factor: primary transformer voltage |
| `ZSTROMP` | E_ZSTROMP | — | DEC | 5 | 1 | Register factor: primary transformer current |
| `INTSIZEID` | INTSIZEID | — | CHAR | 4 | 0 | Interval Length ID |
| `TOUPERIOD` | E_TOUPERIOD | — | CHAR | 10 | 0 | Time-of-use type |
| `VEE_CODE` | E_AMI_VEE_CODE | — | NUMC | 4 | 0 | External VEE Code |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CALOR_AREA` | * |  | TE453 |  | |
| `CALOR_AREA` | ETDZ | CALOR_AREA | TE453 |  | |
| `EQUNR` | ETDZ | MANDT | EQUI |  | |
| `EQUNR` | ETDZ | EQUNR | EQUI |  | |
| `GAS_PRS_AR` | ETDZ | GAS_PRS_AR | TE343 |  | |
| `GAS_PRS_AR` | * |  | TE343 |  | |
| `MANDT` | ETDZ | MANDT | T000 |  | |
| `PR_AREA_AI` | * |  | TE309 |  | |
| `PR_AREA_AI` | ETDZ | PR_AREA_AI | TE309 |  | |
| `TEMP_AREA` | * |  | TE307 |  | |
| `TEMP_AREA` | ETDZ | TEMP_AREA | TE307 |  | |
| `ZWART` | ETDZ | MANDT | TE523 |  | |
| `ZWART` | ETDZ | ZWART | TE523 |  | |
| `ZWKENN` | ETDZ | MANDT | TE065 |  | |
| `ZWKENN` | ETDZ | SPARTYP | TE065 |  | |
| `ZWKENN` | ETDZ | ZWKENN | TE065 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AB`, `BIS`, `EQUNR`, `LOGIKZW`, `ZWNUMMER`, `ab`, `aedat`, `aenam`, `bis`, `equnr`, `erdat`, `ernam`, `intsizeID`, `intsizeid`, `kennziff`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `EQUNR`, `LOGIKZW`, `ab`, `bis`, `equnr`, `logikzw`

## Join Paths
- `ETDZ.EQUNR` → `EQUI.EQUNR` — Tech Register → Equipment

## Programs Using This Table
- `z_bi_lp_prof_val.txt`
- `ziscs0149.txt`
- `ziscs0534_f01.txt`
- `ziscs0717_form.txt`
- `zisdm0022f01.txt`
- `zisdm0086.txt`
- `zisdm0091.txt`
- `zisdm0136c.txt`
- `zisdm0136d.txt`
- `zisdm0170.txt`
- `zisdm0172.txt`
- `zisdm0215.txt`
- `zisdm0231.txt`
- `zisdm0307.txt`
- `zisdm0427.txt`
- `zisdm_bapi_profval_avail_pct.txt`
- `zisem0004.txt`
- `zrca_ssr_extract.txt`
- `zrmig_recon_report.txt`
- `zwfm_get_mr_order_details.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_