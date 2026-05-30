# `AUFK`

**Description:** Order Header — maintenance/service order
**Category:** Standard SAP Table
**References:** 88 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/aufk/) — validated 2026-05-30, schema v1.0
**Schema fields:** 121 fields | **Data types:** CHAR(92), CUKY(1), CURR(1), DATS(13), DEC(1), INT1(1), NUMC(10), TIMS(2)

## Key Fields
`BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `AUART` | AUFART | T003O | CHAR | 4 | 0 | Order Type |
| `AUTYP` | AUFTYP | — | NUMC | 2 | 0 | Order category |
| `REFNR` | AUFREFNR | AUFK | CHAR | 12 | 0 | Reference order number |
| `ERNAM` | AUFERFNAM | — | CHAR | 12 | 0 | Entered by |
| `ERDAT` | AUFERFDAT | — | DATS | 8 | 0 | Created on |
| `AENAM` | AUFAENAM | — | CHAR | 12 | 0 | Last changed by |
| `AEDAT` | AUFAEDAT | — | DATS | 8 | 0 | Change date for Order Master |
| `KTEXT` | AUFTEXT | — | CHAR | 40 | 0 | Description |
| `LTEXT` | AUFLTEXT | — | CHAR | 1 | 0 | Long Text Exists |
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `WERKS` | WERKS_D | T001W | CHAR | 4 | 0 | Plant |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `KOKRS` | KOKRS | TKA01 | CHAR | 4 | 0 | Controlling Area |
| `CCKEY` | CCKEY | — | CHAR | 23 | 0 | Cost collector key |
| `KOSTV` | AUFKOSTV | CSKS | CHAR | 10 | 0 | Responsible cost center |
| `STORT` | AUFSTORT | T499S | CHAR | 10 | 0 | Location |
| `SOWRK` | AUFSOWRK | T001W | CHAR | 4 | 0 | Location plant |
| `ASTKZ` | AUFSTKZ | — | CHAR | 1 | 0 | Identifier for statistical order |
| `WAERS` | AUFWAERS | TCURC | CUKY | 5 | 0 | Order Currency |
| `ASTNR` | AUFASTNR | — | NUMC | 2 | 0 | Order status |
| `STDAT` | AUFSTDAT | — | DATS | 8 | 0 | Date of last status change |
| `ESTNR` | AUFESTNR | TKO03 | NUMC | 2 | 0 | Status reached so far |
| `PHAS0` | AUFPHAS0 | — | CHAR | 1 | 0 | Phase &quot;Order created&quot; |
| `PHAS1` | AUFPHAS1 | — | CHAR | 1 | 0 | Phase &quot;Order released&quot; |
| `PHAS2` | AUFPHAS2 | — | CHAR | 1 | 0 | Phase &quot;order completed&quot; |
| `PHAS3` | AUFPHAS3 | — | CHAR | 1 | 0 | Phase &quot;order closed&quot; |
| `PDAT1` | AUFPDAT1 | — | DATS | 8 | 0 | Planned release date |
| `PDAT2` | AUFPDAT2 | — | DATS | 8 | 0 | Planned completion date |
| `PDAT3` | AUFPDAT3 | — | DATS | 8 | 0 | Planned closing date |
| `IDAT1` | AUFIDAT1 | — | DATS | 8 | 0 | Release date |
| `IDAT2` | AUFIDAT2 | — | DATS | 8 | 0 | Technical completion date |
| `IDAT3` | AUFIDAT3 | — | DATS | 8 | 0 | Close date |
| `OBJID` | CCOBJID | — | CHAR | 1 | 0 | Object ID |
| `VOGRP` | AUFSPSET | TKAVG | CHAR | 4 | 0 | Group of disallowed transactions |
| `LOEKZ` | AUFLOEKZ | — | CHAR | 1 | 0 | Deletion flag |
| `PLGKZ` | PLGKZ | — | CHAR | 1 | 0 | Identifier for planning with line items |
| `KVEWE` | KVEWE | T681V | CHAR | 1 | 0 | Usage of the condition table |
| `KAPPL` | KAPPL | T681A | CHAR | 2 | 0 | Application |
| `KALSM` | AUFKALSM | T683 | CHAR | 6 | 0 | Costing Sheet |
| `ZSCHL` | AUFZSCHL | — | CHAR | 6 | 0 | Overhead key |
| `ABKRS` | AUFABKRS | TKO08 | NUMC | 2 | 0 | Processing group |
| `KSTAR` | AUFKSTAR | CSKB | CHAR | 10 | 0 | Settlement cost element |
| `KOSTL` | AUFKOSTL | CSKS | CHAR | 10 | 0 | Cost center for basic settlement |
| `SAKNR` | AUFSAKNR | SKB1 | CHAR | 10 | 0 | G/L account for basic settlement |
| `SETNM` | AUFSETNM | — | CHAR | 12 | 0 | Allocation set |
| `CYCLE` | ST_KOSTL | CSKS | CHAR | 10 | 0 | Cost center to which costs are actually posted |
| `SDATE` | SDATE | — | DATS | 8 | 0 | Start Date |
| `SEQNR` | AUFSEQNR | — | NUMC | 4 | 0 | Sequence number |
| `USER0` | AUFUSER0 | — | CHAR | 20 | 0 | Applicant |
| `USER1` | AUFUSER1 | — | CHAR | 20 | 0 | Applicant&#039;s telephone number |
| `USER2` | AUFUSER2 | — | CHAR | 20 | 0 | Person responsible |
| `USER3` | AUFUSER3 | — | CHAR | 20 | 0 | Telephone number of person in charge |
| `USER4` | AUFUSER4 | — | CURR | 11 | 2 | Estimated total costs of order |
| `USER5` | AUFUSER5 | — | DATS | 8 | 0 | Application Date |
| `USER6` | AUFUSER6 | — | CHAR | 15 | 0 | Department |
| `USER7` | AUFUSER7 | — | DATS | 8 | 0 | Work Start |
| `USER8` | AUFUSER8 | — | DATS | 8 | 0 | End of Work |
| `USER9` | AUFUSER9 | — | CHAR | 1 | 0 | Identifier for work permit issued |
| `OBJNR` | J_OBJNR | ONR00 | CHAR | 22 | 0 | Object number |
| `PRCTR` | PRCTR | CEPC | CHAR | 10 | 0 | Profit Center |
| `PSPEL` | PS_PSP_ELE | PRPS | NUMC | 8 | 0 | Work breakdown structure element (WBS element) |
| `AWSLS` | AWSLS | TKV01 | CHAR | 6 | 0 | Variance Key |
| `ABGSL` | ABGR_SCHL | TKKAA | CHAR | 6 | 0 | Results Analysis Key |
| `TXJCD` | TXJCD | TTXJ | CHAR | 15 | 0 | Tax Jurisdiction |
| `FUNC_AREA` | FKBER | TFKB | CHAR | 16 | 0 | Functional Area |
| `SCOPE` | SCOPE_CV | — | CHAR | 2 | 0 | Object Class |
| `PLINT` | PLINT | — | CHAR | 1 | 0 | Indicator for Integrated Planning |
| `KDAUF` | KDAUF | VBUK | CHAR | 10 | 0 | Sales Order Number |
| `KDPOS` | KDPOS | — | NUMC | 6 | 0 | Item Number in Sales Order |
| `AUFEX` | AUFEX | — | CHAR | 20 | 0 | External order number |
| `IVPRO` | IM_PROFIL | TAPRF | CHAR | 6 | 0 | Investment measure profile |
| `LOGSYSTEM` | LOGSYSTEM | TBDLS | CHAR | 10 | 0 | Logical System |
| `FLG_MLTPS` | CO_MLTPS | — | CHAR | 1 | 0 | Order with multiple items |
| `ABUKR` | IM_ABUKRS | T001 | CHAR | 4 | 0 | Requesting company code |
| `AKSTL` | PS_AKSTL | CSKS | CHAR | 10 | 0 | Requesting cost center |
| `SIZECL` | IM_SIZECL | TAIF5 | CHAR | 2 | 0 | Scale of investment objects |
| `IZWEK` | IZWEK | T087I | CHAR | 2 | 0 | Reason for investment |
| `UMWKZ` | AM_UMWKZ | T087K | CHAR | 5 | 0 | Reason for environmental investment |
| `KSTEMPF` | CO_KSTEMPF | — | CHAR | 1 | 0 | Indicator: Direct cost collector |
| `ZSCHM` | PS_ZSCHM | TPI01 | CHAR | 7 | 0 | Interest Profile for Project/Order Interest Calculation |
| `PKOSA` | PKOSA_D | — | CHAR | 12 | 0 | Cost collector for production process PROCNR |
| `ANFAUFNR` | AUFANFNR | AUFK | CHAR | 12 | 0 | Requesting order |
| `PROCNR` | CKML_F_PROCNR | — | NUMC | 12 | 0 | Production Process |
| `PROTY` | CKML_PROZESS_TYP | — | CHAR | 4 | 0 | Process Category (Procurement/Consumption) |
| `RSORD` | RSORD | — | CHAR | 1 | 0 | Refurbishment order indicator (PM) |
| `BEMOT` | BEMOT | TBMOT | CHAR | 2 | 0 | Accounting Indicator |
| `ADRNRA` | AD_ADDRNUM | — | CHAR | 10 | 0 | Address number |
| `ERFZEIT` | CO_INS_TIME | — | TIMS | 6 | 0 | Time created |
| `AEZEIT` | CO_CHG_TIME | — | TIMS | 6 | 0 | Changed at |
| `CSTG_VRNT` | CK_KLVAR | — | CHAR | 4 | 0 | Costing Variant |
| `COSTESTNR` | CK_KALNR | — | NUMC | 12 | 0 | Cost Estimate Number for Cost Est. w/o Qty Structure |
| `VERAA_USER` | VERAA_USER | USR02 | CHAR | 12 | 0 | Person Responsible for CO Internal Order |
| `DUMMY_CI_AUFK` | CHAR1 | — | CHAR | 1 | 0 | Single-Character Indicator |
| `VNAME` | JV_NAME | T8JV | CHAR | 6 | 0 | Joint Venture |
| `RECID` | JV_RECIND | T8JJ | CHAR | 2 | 0 | Recovery Indicator |
| `ETYPE` | JV_ETYPE | T8JG | CHAR | 3 | 0 | Equity type |
| `OTYPE` | JV_OTYPE | — | CHAR | 4 | 0 | Joint Venture Object Type |
| `JV_JIBCL` | JV_JIBCL | T8J6A | CHAR | 3 | 0 | JIB/JIBE Class |
| `JV_JIBSA` | JV_JIBSA | T8J6C | CHAR | 5 | 0 | JIB/JIBE Subclass A |
| `JV_OCO` | JV_OR_CO | — | CHAR | 1 | 0 | JV original cost object |
| `CPD_UPDAT` | /CPD/PFP_TSTMP | — | DEC | 15 | 0 | Time Stamp |
| `/CUM/INDCU` | /CUM/INDCU | — | CHAR | 1 | 0 | CU: Order is Used for Compatible Units |
| `/CUM/CMNUM` | /CUM/CMNUM | — | CHAR | 12 | 0 | CU: Construction Measure Number |
| `/CUM/AUEST` | /CUM/AUEST | — | CHAR | 1 | 0 | CU: Automatic Copy of Estimated Costs |
| `/CUM/DESNUM` | /CUM/DESNUM | — | CHAR | 12 | 0 | CU: Design Number |
| `/MRSS/PL_STRU_ID` | /MRSS/T_PLAN_STRUCT_ID | — | NUMC | 8 | 0 | Resource planning nodes |
| `/MRSS/PL_MAN_TYP` | /MRSS/T_MANAGER_TYPE | — | CHAR | 1 | 0 | Assignment to resource planner or contact person |
| `/MRSS/ORDER_PROB` | /MRSS/T_ORDER_PROB | — | CHAR | 3 | 0 | Order probability in percent |
| `/MRSS/ACT_TYPE` | /MRSS/T_ACTIVITY_TYPE | — | CHAR | 1 | 0 | Process variant |
| `/MRSS/INIT_DONE` | /MRSS/T_INIT_DONE | — | CHAR | 1 | 0 | Internal initialization carried out once |
| `/MRSS/DATACHANGE` | /MRSS/T_USCREENCTL_DATACHANGED | — | CHAR | 1 | 0 | Data was changed in the controls on the user screen |
| `/MRSS/SALES_ORG` | VKORG | — | CHAR | 4 | 0 | Sales Organization |
| `/MRSS/NW_BOOKED` | /MRSS/T_NW_BOOKED | — | CHAR | 1 | 0 | Network Set to &quot;Booked&quot; |
| `VAPLZ` | GEWRK | — | CHAR | 8 | 0 | Main work center for maintenance tasks |
| `WAWRK` | WERGW | — | CHAR | 4 | 0 | Plant associated with main work center |
| `FERC_IND` | FE_IND | FERC_C7 | CHAR | 4 | 0 | Regulatory indicator |
| `AUFK_STATUS` | ACTCMB_DELE | ACTCMB_TAB | INT1 | 3 | 0 | Status Combination |
| `OIHANTYP` | OIH_HANTYP | OIH5 | CHAR | 2 | 0 | Excise Duty Handling Type |
| `CLAIM_CONTROL` | WTYSC_CLAIM_CONTROL | WTYSCC_CLM_CONT | CHAR | 1 | 0 | Claim creation control indicator |
| `UPDATE_NEEDED` | WTYSC_UPDATE_NEEDED | — | CHAR | 1 | 0 | Claim inconsistency with order indicator |
| `UPDATE_CONTROL` | WTYSC_UPDATE_CONTROL | WTYSCC_UPDT_CONT | CHAR | 1 | 0 | Claim update trigger point from service order |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABGSL` | AUFK | MANDT | TKKAA |  | |
| `ABGSL` | AUFK | ABGSL | TKKAA |  | |
| `ABKRS` | AUFK | MANDT | TKO08 |  | |
| `ABKRS` | AUFK | KOKRS | TKO08 |  | |
| `ABKRS` | AUFK | ABKRS | TKO08 |  | |
| `ABUKR` | AUFK | ABUKR | T001 |  | |
| `ABUKR` | AUFK | MANDT | T001 |  | |
| `AKSTL` | AUFK | AKSTL | CSKS |  | |
| `AKSTL` | * |  | CSKS |  | |
| `AKSTL` | AUFK | MANDT | CSKS |  | |
| `AKSTL` | AUFK | KOKRS | CSKS |  | |
| `ANFAUFNR` | AUFK | MANDT | AUFK |  | |
| `ANFAUFNR` | AUFK | ANFAUFNR | AUFK |  | |
| `AUART` | AUFK | MANDT | T003O |  | |
| `AUART` | AUFK | AUART | T003O |  | |
| `AUFK_STATUS` | AUFK | MANDT | ACTCMB_TAB |  | |
| `AUFK_STATUS` | AUFK | AUFK_STATUS | ACTCMB_TAB |  | |
| `AWSLS` | AUFK | AWSLS | TKV01 |  | |
| `AWSLS` | AUFK | MANDT | TKV01 |  | |
| `AWSLS` | TKV01 | AWOBA | TKV01 |  | |
| `BEMOT` | AUFK | MANDT | TBMOT |  | |
| `BEMOT` | AUFK | BEMOT | TBMOT |  | |
| `BUKRS` | AUFK | MANDT | T001 |  | |
| `BUKRS` | AUFK | BUKRS | T001 |  | |
| `CLAIM_CONTROL` | AUFK | CLAIM_CONTROL | WTYSCC_CLM_CONT |  | |
| `CLAIM_CONTROL` | SYST | MANDT | WTYSCC_CLM_CONT |  | |
| `CYCLE` | AUFK | MANDT | CSKS |  | |
| `CYCLE` | AUFK | KOKRS | CSKS |  | |
| `CYCLE` | AUFK | CYCLE | CSKS |  | |
| `CYCLE` | * |  | CSKS |  | |
| `ESTNR` | AUFK | MANDT | TKO03 |  | |
| `ESTNR` | AUFK | AUART | TKO03 |  | |
| `ESTNR` | AUFK | ESTNR | TKO03 |  | |
| `ETYPE` | AUFK | ETYPE | T8JG |  | |
| `ETYPE` | * |  | T8JG |  | |
| `ETYPE` | SYST | MANDT | T8JG |  | |
| `ETYPE` | GJV_OBJDAT | BUKRS | T8JG |  | |
| `ETYPE` | AUFK | VNAME | T8JG |  | |
| `FERC_IND` | AUFK | MANDT | FERC_C7 |  | |
| `FERC_IND` | AUFK | FERC_IND | FERC_C7 |  | |
| `FUNC_AREA` | AUFK | MANDT | TFKB |  | |
| `FUNC_AREA` | AUFK | FUNC_AREA | TFKB |  | |
| `GSBER` | AUFK | MANDT | TGSB |  | |
| `GSBER` | AUFK | GSBER | TGSB |  | |
| `IVPRO` | AUFK | IVPRO | TAPRF |  | |
| `IVPRO` | AUFK | MANDT | TAPRF |  | |
| `IZWEK` | AUFK | MANDT | T087I |  | |
| `IZWEK` | AUFK | IZWEK | T087I |  | |
| `JV_JIBCL` | SYST | MANDT | T8J6A |  | |
| `JV_JIBCL` | GJV_OBJDAT | BUKRS | T8J6A |  | |
| `JV_JIBCL` | AUFK | JV_JIBCL | T8J6A |  | |
| `JV_JIBSA` | AUFK | JV_JIBCL | T8J6C |  | |
| `JV_JIBSA` | AUFK | JV_JIBSA | T8J6C |  | |
| `JV_JIBSA` | SYST | MANDT | T8J6C |  | |
| `JV_JIBSA` | GJV_OBJDAT | BUKRS | T8J6C |  | |
| `KALSM` | AUFK | KALSM | T683 |  | |
| `KALSM` | AUFK | MANDT | T683 |  | |
| `KALSM` | AUFK | KVEWE | T683 |  | |
| `KALSM` | AUFK | KAPPL | T683 |  | |
| `KAPPL` | AUFK | KAPPL | T681A |  | |
| `KDAUF` | AUFK | MANDT | VBUK |  | |
| `KDAUF` | AUFK | KDAUF | VBUK |  | |
| `KOKRS` | AUFK | MANDT | TKA01 |  | |
| `KOKRS` | AUFK | KOKRS | TKA01 |  | |
| `KOSTL` | AUFK | MANDT | CSKS |  | |
| `KOSTL` | AUFK | KOKRS | CSKS |  | |
| `KOSTL` | AUFK | KOSTL | CSKS |  | |
| `KOSTL` | * |  | CSKS |  | |
| `KOSTV` | AUFK | KOKRS | CSKS |  | |
| `KOSTV` | AUFK | KOSTV | CSKS |  | |
| `KOSTV` | * |  | CSKS |  | |
| `KOSTV` | AUFK | MANDT | CSKS |  | |
| `KSTAR` | AUFK | KOKRS | CSKB |  | |
| `KSTAR` | AUFK | KSTAR | CSKB |  | |
| `KSTAR` | * |  | CSKB |  | |
| `KSTAR` | AUFK | MANDT | CSKB |  | |
| `KVEWE` | AUFK | KVEWE | T681V |  | |
| `LOGSYSTEM` | AUFK | LOGSYSTEM | TBDLS |  | |
| `MANDT` | AUFK | MANDT | T000 |  | |
| `OBJNR` | AUFK | MANDT | ONR00 |  | |
| `OBJNR` | AUFK | OBJNR | ONR00 |  | |
| `OIHANTYP` | SYST | MANDT | OIH5 |  | |
| `OIHANTYP` | AUFK | OIHANTYP | OIH5 |  | |
| `PRCTR` | AUFK | MANDT | CEPC |  | |
| `PRCTR` | AUFK | PRCTR | CEPC |  | |
| `PRCTR` | * |  | CEPC |  | |
| `PRCTR` | AUFK | KOKRS | CEPC |  | |
| `PSPEL` | AUFK | MANDT | PRPS |  | |
| `PSPEL` | AUFK | PSPEL | PRPS |  | |
| `RECID` | SYST | MANDT | T8JJ |  | |
| `RECID` | GJV_OBJDAT | BUKRS | T8JJ |  | |
| `RECID` | AUFK | RECID | T8JJ |  | |
| `REFNR` | AUFK | MANDT | AUFK |  | |
| `REFNR` | AUFK | REFNR | AUFK |  | |
| `SAKNR` | AUFK | MANDT | SKB1 |  | |
| `SAKNR` | AUFK | BUKRS | SKB1 |  | |
| `SAKNR` | AUFK | SAKNR | SKB1 |  | |
| `SIZECL` | AUFK | MANDT | TAIF5 |  | |
| `SIZECL` | AUFK | SIZECL | TAIF5 |  | |
| `SOWRK` | AUFK | MANDT | T001W |  | |
| `SOWRK` | AUFK | SOWRK | T001W |  | |
| `STORT` | AUFK | MANDT | T499S |  | |
| `STORT` | AUFK | SOWRK | T499S |  | |
| `STORT` | AUFK | STORT | T499S |  | |
| `TXJCD` | AUFK | MANDT | TTXJ |  | |
| `TXJCD` | * |  | TTXJ |  | |
| `TXJCD` | AUFK | TXJCD | TTXJ |  | |
| `UMWKZ` | AUFK | MANDT | T087K |  | |
| `UMWKZ` | AUFK | UMWKZ | T087K |  | |
| `UPDATE_CONTROL` | SYST | MANDT | WTYSCC_UPDT_CONT |  | |
| `UPDATE_CONTROL` | AUFK | UPDATE_CONTROL | WTYSCC_UPDT_CONT |  | |
| `VERAA_USER` | * |  | USR02 |  | |
| `VERAA_USER` | AUFK | VERAA_USER | USR02 |  | |
| `VNAME` | SYST | MANDT | T8JV |  | |
| `VNAME` | GJV_OBJDAT | BUKRS | T8JV |  | |
| `VNAME` | AUFK | VNAME | T8JV |  | |
| `VOGRP` | AUFK | MANDT | TKAVG |  | |
| `VOGRP` | AUFK | OBJID | TKAVG |  | |
| `VOGRP` | AUFK | VOGRP | TKAVG |  | |
| `VOGRP` | * |  | TKAVG |  | |
| `WAERS` | AUFK | WAERS | TCURC |  | |
| `WAERS` | AUFK | MANDT | TCURC |  | |
| `WERKS` | AUFK | MANDT | T001W |  | |
| `WERKS` | AUFK | WERKS | T001W |  | |
| `ZSCHM` | AUFK | MANDT | TPI01 |  | |
| `ZSCHM` | AUFK | ZSCHM | TPI01 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AUART`, `AUFNR`, `ERDAT`, `IDAT2`, `LOEKZ`, `OBJNR`, `adrnra`, `aedat`, `auart`, `aufnr`, `idat2`, `objnr`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `auart`, `aufnr`, `idat2`

## Join Paths
- `AUFK.AUFNR` → `AFIH.AUFNR` — Order → Maintenance Order

## Programs Using This Table
- `method-read_serv_ord_stat_info.txt`
- `z_bapi_get_cl_status.txt`
- `z_bapi_updateso.txt`
- `zdiscon.txt`
- `zggbr000.txt`
- `zisbi0013.txt`
- `zisbi0186.txt`
- `ziscrm0318forms.txt`
- `ziscs0002.txt`
- `ziscs0007.txt`
- `ziscs0014.txt`
- `ziscs0014_adj.txt`
- `ziscs0021.txt`
- `ziscs0341.txt`
- `ziscs1119.txt`
- `zisdm0051.txt`
- `zisdm0175.txt`
- `zisdm0297_sub.txt`
- `zisdm_so_approval_f01.txt`
- `zrpm_mwfm_so_create.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_