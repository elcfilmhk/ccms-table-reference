# `EPROFHEAD`

**Description:** Energy Profile Header — rate profile master
**Category:** Standard SAP Table
**References:** 31 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eprofhead/) — validated 2026-05-30, schema v1.0
**Schema fields:** 35 fields | **Data types:** CHAR(14), CUKY(1), DATS(6), NUMC(7), TIMS(6), UNIT(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `SPARTE` | SPARTE | TSPA | CHAR | 2 | 0 | Division |
| `PROFTYPE` | PROFTYPE | EPROFTYPE | NUMC | 2 | 0 | Profile type |
| `PROFVALCAT` | E_PROFVALCAT | EPROFVALCAT | NUMC | 2 | 0 | Profile value category |
| `VALUECUM` | VALUECUM | — | CHAR | 1 | 0 | Cumulative values |
| `INTSIZEID` | INTSIZEID | EPROFINTSIZE | CHAR | 4 | 0 | Interval Length ID |
| `MASS` | E_MASS | T006 | UNIT | 3 | 0 | Unit of Measurement |
| `PROFDECIMALS` | PROFDECIMALS | — | NUMC | 2 | 0 | Number of decimal places in a profile value |
| `SOURCE` | E_SOURCE | — | NUMC | 18 | 0 | Source of object |
| `OBJNR` | J_OBJNR | — | CHAR | 22 | 0 | Object number |
| `PROFOFFSET` | PROFOFFSET | — | TIMS | 6 | 0 | Profile value offset |
| `CONCHECKGRP` | E_CONCHECKGRP | EEDMCONGRP | CHAR | 10 | 0 | Consistency check group |
| `FORWARD_ORIENTED` | FORWARD_ORIENTED | — | CHAR | 1 | 0 | Profile values have forward orientation |
| `LASTVERSNO` | CVERSNO | — | NUMC | 6 | 0 | Consecutive number of version |
| `DATEFROM` | E_EDMDATEFROM | — | DATS | 8 | 0 | From-Date |
| `TIMEFROM` | E_EDMTIMEFROM | — | TIMS | 6 | 0 | From-time |
| `DATETO` | E_EDMDATETO | — | DATS | 8 | 0 | To-Date |
| `TIMETO` | E_EDMTIMETO | — | TIMS | 6 | 0 | To-Time |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `BEGRU` | BEGRU | — | CHAR | 4 | 0 | Authorization Group |
| `LOEVM` | LOEVM | — | CHAR | 1 | 0 | Deletion Indicator |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `ARCH_DATEFROM` | E_EDMDATETO_A | — | DATS | 8 | 0 | Date, up to Which Profile Values Have Been Archived |
| `ARCH_TIMEFROM` | E_EDMTIMETO_A | — | TIMS | 6 | 0 | Time until which, profile values are archived. |
| `ARCH_DATETO` | E_EDMDATETO_A | — | DATS | 8 | 0 | Date, up to Which Profile Values Have Been Archived |
| `ARCH_TIMETO` | E_EDMTIMETO_A | — | TIMS | 6 | 0 | Time until which, profile values are archived. |
| `REF_PROFILE` | E_REFPROFILE | EPROFHEAD | NUMC | 18 | 0 | Profile Referenced During Settlement |
| `REPLACEMETHODGRP` | E_REPLACEGRP | EEDMREPLACEGRP | CHAR | 10 | 0 | Replacement Value Procedure Group |
| `DAY_OFFSET` | EDM_DAY_OFFSET | — | TIMS | 6 | 0 | Day Offset |
| `TIME_ZONE` | EDM_TIMEZONE | TTZZ | CHAR | 6 | 0 | Time Zone for EDM Objects |
| `SRCPROFILE` | E_SRCPROFILE | — | NUMC | 18 | 0 | Source Profile for Copy Profile |
| `MDUS_LOCATED` | E_AMI_MDUS_LOCATED_PROFILE | — | CHAR | 1 | 0 | Location of Original Profile Values |
| `TOU_BILLABLE` | E_TOU_BILLABLE | — | CHAR | 1 | 0 | Profile Can Be Billed with TOU Interface |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CONCHECKGRP` | SYST | MANDT | EEDMCONGRP |  | |
| `CONCHECKGRP` | EPROFHEAD | CONCHECKGRP | EEDMCONGRP |  | |
| `INTSIZEID` | SYST | MANDT | EPROFINTSIZE |  | |
| `INTSIZEID` | EPROFHEAD | INTSIZEID | EPROFINTSIZE |  | |
| `MANDT` | EPROFHEAD | MANDT | T000 |  | |
| `MASS` | SYST | MANDT | T006 |  | |
| `MASS` | EPROFHEAD | MASS | T006 |  | |
| `PROFTYPE` | SYST | MANDT | EPROFTYPE |  | |
| `PROFTYPE` | EPROFHEAD | PROFTYPE | EPROFTYPE |  | |
| `PROFVALCAT` | EPROFHEAD | PROFVALCAT | EPROFVALCAT |  | |
| `REF_PROFILE` | SYST | MANDT | EPROFHEAD |  | |
| `REF_PROFILE` | EPROFHEAD | REF_PROFILE | EPROFHEAD |  | |
| `REPLACEMETHODGRP` | SYST | MANDT | EEDMREPLACEGRP |  | |
| `REPLACEMETHODGRP` | EPROFHEAD | REPLACEMETHODGRP | EEDMREPLACEGRP |  | |
| `SPARTE` | SYST | MANDT | TSPA |  | |
| `SPARTE` | EPROFHEAD | SPARTE | TSPA |  | |
| `TIME_ZONE` | SYST | MANDT | TTZZ |  | |
| `TIME_ZONE` | EPROFHEAD | TIME_ZONE | TTZZ |  | |
| `WAERS` | SYST | MANDT | TCURC |  | |
| `WAERS` | EPROFHEAD | WAERS | TCURC |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `method-get_data.txt`
- `method-vee_manual_edit.txt`
- `z_conv_kvarh_to_kva_fit.txt`
- `z_isdm_get_formula_profile.txt`
- `z_write_bwami_extractor.txt`
- `z_write_bwfit_extractor.txt`
- `zedm_ext_30int_sub_forms.txt`
- `zisdm0022f01.txt`
- `zisdm0205.txt`
- `zisdm0209_evf01.txt`
- `zisdm0333.txt`
- `zisdm0382.txt`
- `zisdm_profvalday_get.txt`
- `zised0020.txt`
- `zised0040.txt`
- `zised0054_forms.txt`
- `zredm_prof_stat_qual.txt`
- `zredm_prof_val_gen.txt`
- `zredm_status_prof_update.txt`
- `zrmig_zz_profile_update.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_