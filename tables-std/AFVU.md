# `AFVU`

**Description:** Order Operation User Fields — operation extensions
**Category:** Standard SAP Table
**References:** 25 SELECT statements across 13 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/afvu/) — validated 2026-05-30, schema v1.0
**Schema fields:** 65 fields | **Data types:** CHAR(39), CUKY(2), CURR(2), DATS(6), NUMC(6), QUAN(2), TIMS(4), UNIT(4)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `SLWID` | SLWID | TCN00 | CHAR | 7 | 0 | Key word ID for user-defined fields |
| `USR00` | USRCHAR20 | — | CHAR | 20 | 0 | User field with 20 characters |
| `USR01` | USRCHAR20 | — | CHAR | 20 | 0 | User field with 20 characters |
| `USR02` | USRCHAR10 | — | CHAR | 10 | 0 | User field with 10 characters |
| `USR03` | USRCHAR10 | — | CHAR | 10 | 0 | User field with 10 characters |
| `USR04` | USRQUAN13 | — | QUAN | 13 | 3 | User field for quantity (length 10.3) |
| `USE04` | USRUNIT | T006 | UNIT | 3 | 0 | User field: Unit for quantity fields |
| `USR05` | USRQUAN13 | — | QUAN | 13 | 3 | User field for quantity (length 10.3) |
| `USE05` | USRUNIT | T006 | UNIT | 3 | 0 | User field: Unit for quantity fields |
| `USR06` | USRCURR13 | — | CURR | 13 | 3 | User-defined field for values (length 10,3) |
| `USE06` | USRCUKY | TCURC | CUKY | 5 | 0 | User field: Unit for value fields |
| `USR07` | USRCURR13 | — | CURR | 13 | 3 | User-defined field for values (length 10,3) |
| `USE07` | USRCUKY | TCURC | CUKY | 5 | 0 | User field: Unit for value fields |
| `USR08` | USRDATE | — | DATS | 8 | 0 | User field for date |
| `USR09` | USRDATE | — | DATS | 8 | 0 | User field for date |
| `USR10` | USRFLAG | — | CHAR | 1 | 0 | User-defined field: Indicator for reports |
| `USR11` | USRFLAG | — | CHAR | 1 | 0 | User-defined field: Indicator for reports |
| `VNAME` | JV_NAME | T8JV | CHAR | 6 | 0 | Joint Venture |
| `RECID` | JV_RECIND | T8JJ | CHAR | 2 | 0 | Recovery Indicator |
| `ETYPE` | JV_ETYPE | T8JG | CHAR | 3 | 0 | Equity type |
| `JV_OTYPE` | JV_OTYPE | — | CHAR | 4 | 0 | Joint Venture Object Type |
| `JV_JIBCL` | JV_JIBCL | T8J6A | CHAR | 3 | 0 | JIB/JIBE Class |
| `JV_JIBSA` | JV_JIBSA | T8J6C | CHAR | 5 | 0 | JIB/JIBE Subclass A |
| `JV_OCO` | JV_OR_CO | — | CHAR | 1 | 0 | JV original cost object |
| `DUMMY_CI_AFVU` | CHAR1 | — | CHAR | 1 | 0 | Single-Character Indicator |
| `SPARAMETER1` | SPARAMETER | TSCHEDULEPARAM1 | CHAR | 4 | 0 | Scheduling Parameters for External Scheduling |
| `SPARAMETER2` | SPARAMETER | TSCHEDULEPARAM2 | CHAR | 4 | 0 | Scheduling Parameters for External Scheduling |
| `SPARAMETER3` | SPARAMETER | TSCHEDULEPARAM3 | CHAR | 4 | 0 | Scheduling Parameters for External Scheduling |
| `/MRSS/ID_PROFILE` | /MRSS/T_REQU_UPD | — | CHAR | 1 | 0 | Requirements Profile Was Changed Manually |
| `/MRSS/PROF_KEY` | /MRSS/T_RSG_REQUID | — | CHAR | 10 | 0 | Profile Key |
| `/MRSS/PROF_GUID` | CHAR32 | — | CHAR | 32 | 0 | Character field, length 32 |
| `/MRSS/ACT_TYPE` | /MRSS/T_ACTIVITY_TYPE | — | CHAR | 1 | 0 | Process variant |
| `/MRSS/ORDER_PROB` | /MRSS/T_ORDER_PROB | — | CHAR | 3 | 0 | Order probability in percent |
| `/MRSS/INIT_DONE` | /MRSS/T_INIT_DONE | — | CHAR | 1 | 0 | Internal initialization carried out once |
| `/MRSS/DATACHANGE` | /MRSS/T_USCREENCTL_DATACHANGED | — | CHAR | 1 | 0 | Data was changed in the controls on the user screen |
| `/MRSS/DEM_COUNT` | /MRSS/T_DEM_COUNT | — | NUMC | 4 | 0 | Counter for Demands in Operation |
| `/MRSS/SUPERV_CNT` | /MRSS/T_RAP_SUPERVISOR_COUNT | — | CHAR | 2 | 0 | Number of Site Supervisors |
| `/MRSS/RULE_ID` | /MRSS/T_RSG_TIME_RULE_ID | — | CHAR | 25 | 0 | Time Rule Id |
| `/MRSS/SALES_ORG` | VKORG | — | CHAR | 4 | 0 | Sales Organization |
| `/MRSS/REFF_RCNT` | /MRSS/T_REM_EFFORT_RES_COUNT | — | NUMC | 3 | 0 | Determination of Remaining Demand: No. of Resources |
| `/MRSS/REFF_E_BEG` | /MRSS/T_TIMESTAMP_BEGIN | — | NUMC | 14 | 0 | Time stamp: start |
| `/MRSS/REFF_E_END` | /MRSS/T_TIMESTAMP_END | — | NUMC | 14 | 0 | Time stamp: end |
| `/MRSS/REFF_L_BEG` | /MRSS/T_TIMESTAMP_BEGIN | — | NUMC | 14 | 0 | Time stamp: start |
| `/MRSS/REFF_L_END` | /MRSS/T_TIMESTAMP_END | — | NUMC | 14 | 0 | Time stamp: end |
| `/MRSS/RELEVANT` | /MRSS/T_RELEVANT_FOR_MRS | — | CHAR | 1 | 0 | Operation Set as MRS-Relevant |
| `/MRSS/TEAM_PLAN` | /MRSS/T_RSG_TEAM_PLANNING | — | CHAR | 1 | 0 | Team Planning flag for Demand |
| `/MRSS/SINGL_RES` | /MRSS/T_RSG_FORCE_SINGLE_RES | — | CHAR | 1 | 0 | Indicator for Forcing a Single Resource |
| `/MRSS/TO_BEGDAT` | DATS | — | DATS | 8 | 0 | Field of type DATS |
| `/MRSS/TO_BEGTIM` | TIMS | — | TIMS | 6 | 0 | Field of type TIMS |
| `/MRSS/TO_ENDDAT` | DATS | — | DATS | 8 | 0 | Field of type DATS |
| `/MRSS/TO_ENDTIM` | TIMS | — | TIMS | 6 | 0 | Field of type TIMS |
| `/MRSS/TO_DURAT` | CHAR10 | — | CHAR | 10 | 0 | Character Field Length = 10 |
| `/MRSS/TO_DUNIT` | MEINS | — | UNIT | 3 | 0 | Base Unit of Measure |
| `/MRSS/TO_DISTAN` | CHAR19 | — | CHAR | 19 | 0 | 19 Characters |
| `/MRSS/TO_MANUAL` | /MRSS/T_RSG_BOOLEAN | — | CHAR | 1 | 0 | Boolean Variable |
| `/MRSS/FR_BEGDAT` | DATS | — | DATS | 8 | 0 | Field of type DATS |
| `/MRSS/FR_BEGTIM` | TIMS | — | TIMS | 6 | 0 | Field of type TIMS |
| `/MRSS/FR_ENDDAT` | DATS | — | DATS | 8 | 0 | Field of type DATS |
| `/MRSS/FR_ENDTIM` | TIMS | — | TIMS | 6 | 0 | Field of type TIMS |
| `/MRSS/FR_DURAT` | CHAR10 | — | CHAR | 10 | 0 | Character Field Length = 10 |
| `/MRSS/FR_DUNIT` | MEINS | — | UNIT | 3 | 0 | Base Unit of Measure |
| `/MRSS/FR_DISTAN` | CHAR19 | — | CHAR | 19 | 0 | 19 Characters |
| `/MRSS/FR_MANUAL` | /MRSS/T_RSG_BOOLEAN | — | CHAR | 1 | 0 | Boolean Variable |
| `ILART_OP` | ILA | — | CHAR | 3 | 0 | Maintenance activity type |
| `FERC_IND` | FE_IND | FERC_C7 | CHAR | 4 | 0 | Regulatory indicator |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `APLZL` | AFVU | MANDT | AFVC |  | |
| `APLZL` | AFVU | AUFPL | AFVC |  | |
| `APLZL` | AFVU | APLZL | AFVC |  | |
| `ETYPE` | SYST | MANDT | T8JG |  | |
| `ETYPE` | GJV_OBJDAT | BUKRS | T8JG |  | |
| `ETYPE` | AFVU | VNAME | T8JG |  | |
| `ETYPE` | AFVU | ETYPE | T8JG |  | |
| `ETYPE` | * |  | T8JG |  | |
| `FERC_IND` | SYST | MANDT | FERC_C7 |  | |
| `FERC_IND` | AFVU | FERC_IND | FERC_C7 |  | |
| `JV_JIBCL` | GJV_OBJDAT | BUKRS | T8J6A |  | |
| `JV_JIBCL` | AFVU | JV_JIBCL | T8J6A |  | |
| `JV_JIBCL` | SYST | MANDT | T8J6A |  | |
| `JV_JIBSA` | AFVU | JV_JIBSA | T8J6C |  | |
| `JV_JIBSA` | SYST | MANDT | T8J6C |  | |
| `JV_JIBSA` | GJV_OBJDAT | BUKRS | T8J6C |  | |
| `JV_JIBSA` | AFVU | JV_JIBCL | T8J6C |  | |
| `MANDT` | AFVU | MANDT | T000 |  | |
| `RECID` | SYST | MANDT | T8JJ |  | |
| `RECID` | GJV_OBJDAT | BUKRS | T8JJ |  | |
| `RECID` | AFVU | RECID | T8JJ |  | |
| `SLWID` | AFVUK | MANDT | TCN00 |  | |
| `SLWID` | AFVU | SLWID | TCN00 |  | |
| `SPARAMETER1` | AFVU | MANDT | TSCHEDULEPARAM1 |  | |
| `SPARAMETER1` | AFVU | SPARAMETER1 | TSCHEDULEPARAM1 |  | |
| `SPARAMETER2` | AFVU | MANDT | TSCHEDULEPARAM2 |  | |
| `SPARAMETER2` | AFVU | SPARAMETER2 | TSCHEDULEPARAM2 |  | |
| `SPARAMETER3` | AFVU | MANDT | TSCHEDULEPARAM3 |  | |
| `SPARAMETER3` | AFVU | SPARAMETER3 | TSCHEDULEPARAM3 |  | |
| `USE04` | AFVGI | MANDT | T006 |  | |
| `USE04` | AFVU | USE04 | T006 |  | |
| `USE05` | AFVGI | MANDT | T006 |  | |
| `USE05` | AFVU | USE05 | T006 |  | |
| `USE06` | AFVKI | MANDT | TCURC |  | |
| `USE06` | AFVU | USE06 | TCURC |  | |
| `USE07` | AFVKI | MANDT | TCURC |  | |
| `USE07` | AFVU | USE07 | TCURC |  | |
| `VNAME` | AFVU | VNAME | T8JV |  | |
| `VNAME` | SYST | MANDT | T8JV |  | |
| `VNAME` | GJV_OBJDAT | BUKRS | T8JV |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0013.txt`
- `ziscs0005.txt`
- `ziscs0007.txt`
- `ziscs0007_gprs.txt`
- `ziscs0031.txt`
- `ziscs0039.txt`
- `ziscs0060.txt`
- `ziscs0287.txt`
- `ziscs0355.txt`
- `ziscs0465.txt`
- `ziscsriaufk20.txt`
- `zisfi0030.txt`
- `zisuorder.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_