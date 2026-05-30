# `EPROFASS`

**Description:** Energy Profile Assignment — rate profile assignment
**Category:** Standard SAP Table
**References:** 91 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eprofass/) — validated 2026-05-30, schema v1.0
**Schema fields:** 9 fields | **Data types:** CHAR(3), DATS(3), NUMC(2), TIMS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `DATEFROM` | E_EDMDATEFROM | — | DATS | 8 | 0 | From-Date |
| `TIMEFROM` | E_EDMTIMEFROM | — | TIMS | 6 | 0 | From-time |
| `PROFILE` | E_PROFILE | EPROFHEAD | NUMC | 18 | 0 | Number of EDM Profile |
| `CONTEXTCATEGORY` | E_CONTEXTCATEGORY | EEDMPROFCONTEXT | NUMC | 2 | 0 | Context Category for Profile Allocation Role |
| `PROFROLECONTEXT` | PROFROLECONTEXT | — | CHAR | 22 | 0 | Context for Profile Allocation |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CONTEXTCATEGORY` | EPROFASS | CONTEXTCATEGORY | EEDMPROFCONTEXT |  | |
| `PROFILE` | EPROFASS | MANDT | EPROFHEAD |  | |
| `PROFILE` | EPROFASS | PROFILE | EPROFHEAD |  | |
| `PROFROLE` | EPROFASS | MANDT | EPROFASSROLE |  | |
| `PROFROLE` | EPROFASS | PROFROLE | EPROFASSROLE |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `datefrom`, `dateto`, `logikzw`, `profile`, `timeto`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `logikzw`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_cs_cxt_add_consum.txt`
- `z_isdm_consumption_details.txt`
- `z_isdm_registers_validation.txt`
- `z_write_bwfit_extractor.txt`
- `zisdm0102.txt`
- `zisdm0128f01.txt`
- `zisdm0201.txt`
- `zisdm0201_sub_lp.txt`
- `zisdm0212.txt`
- `zisdm0213.txt`
- `zisdm0214.txt`
- `zisdm0284.txt`
- `zisdm0310_adr.txt`
- `zisdm0361.txt`
- `zised0047.txt`
- `zised0058.txt`
- `zisu_edm_formula_fitreb.txt`
- `zrca_ssr_premise_upload.txt`
- `zredm_profile_stat_rep.txt`
- `zrmig_recon_report.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_