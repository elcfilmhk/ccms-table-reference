# `CAUFV`

**Description:** Order (All) — combined order view
**Category:** Standard SAP Table
**References:** 5 SELECT statements across 3 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/caufv/) — validated 2026-05-30, schema v1.0
**Schema fields:** 263 fields | **Data types:** CHAR(146), CUKY(1), CURR(1), DATS(32), DEC(8), INT1(1), INT4(1), NUMC(40), QUAN(14), TIMS(14), UNIT(5)

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
| `STDAT` | AUFSTDAT | — | DATS | 8 | 0 | Date of last status change |
| `IDAT1` | AUFIDAT1 | — | DATS | 8 | 0 | Release date |
| `IDAT2` | AUFIDAT2 | — | DATS | 8 | 0 | Technical completion date |
| `IDAT3` | AUFIDAT3 | — | DATS | 8 | 0 | Close date |
| `OBJID` | CCOBJID | — | CHAR | 1 | 0 | Object ID |
| `LOEKZ` | AUFLOEKZ | — | CHAR | 1 | 0 | Deletion flag |
| `PLGKZ` | PLGKZ | — | CHAR | 1 | 0 | Identifier for planning with line items |
| `KVEWE` | KVEWE | T681V | CHAR | 1 | 0 | Usage of the condition table |
| `KAPPL` | KAPPL | T681A | CHAR | 2 | 0 | Application |
| `KALSM` | AUFKALSM | T683 | CHAR | 6 | 0 | Costing Sheet |
| `ZSCHL` | AUFZSCHL | — | CHAR | 6 | 0 | Overhead key |
| `ABKRS` | AUFABKRS | TKO08 | NUMC | 2 | 0 | Processing group |
| `KSTAR` | AUFKSTAR | CSKB | CHAR | 10 | 0 | Settlement cost element |
| `KOSTL` | AUFKOSTL | CSKS | CHAR | 10 | 0 | Cost center for basic settlement |
| `SETNM` | AUFSETNM | — | CHAR | 12 | 0 | Allocation set |
| `CYCLE` | ST_KOSTL | CSKS | CHAR | 10 | 0 | Cost center to which costs are actually posted |
| `SDATE` | SDATE | — | DATS | 8 | 0 | Start Date |
| `SEQNR` | AUFSEQNR | — | NUMC | 4 | 0 | Sequence number |
| `USER4` | AUFUSER4 | — | CURR | 11 | 2 | Estimated total costs of order |
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
| `GLTRP` | CO_GLTRP | — | DATS | 8 | 0 | Basic finish date |
| `GSTRP` | PM_ORDGSTRP | — | DATS | 8 | 0 | Basic Start Date |
| `FTRMS` | CO_FTRMS | — | DATS | 8 | 0 | Scheduled release date |
| `GLTRS` | CO_GLTRS | — | DATS | 8 | 0 | Scheduled finish |
| `GSTRS` | CO_GSTRS | — | DATS | 8 | 0 | Scheduled start |
| `GSTRI` | CO_GSTRI | — | DATS | 8 | 0 | Actual start date |
| `GETRI` | CO_GETRI | — | DATS | 8 | 0 | Confirmed Order Finish Date |
| `GLTRI` | CO_GLTRI | — | DATS | 8 | 0 | Actual finish date |
| `FTRMI` | CO_FTRMI | — | DATS | 8 | 0 | Actual release date |
| `FTRMP` | CO_FTRMP | — | DATS | 8 | 0 | Planned release date |
| `RSNUM` | RSNUM | — | NUMC | 10 | 0 | Number of Reservation/Dependent Requirement |
| `GASMG` | GASMG | — | QUAN | 13 | 3 | Total scrap quantity in the order |
| `GAMNG` | GAMNG | — | QUAN | 13 | 3 | Total order quantity |
| `GMEIN` | MEINS | T006 | UNIT | 3 | 0 | Base Unit of Measure |
| `PLNBEZ` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `PLNTY` | PLNTY | — | CHAR | 1 | 0 | Task List Type |
| `PLNNR` | PLNNR | — | CHAR | 8 | 0 | Key for Task List Group |
| `PLNAW` | PLNAW | TCA09 | CHAR | 1 | 0 | Application of the task list |
| `PLNAL` | PLNAL | — | CHAR | 2 | 0 | Group Counter |
| `PVERW` | PLN_VERWE | T411 | CHAR | 3 | 0 | Task list usage |
| `PLAUF` | CO_PLAUF | — | DATS | 8 | 0 | Date for routing transfer |
| `PLSVB` | LOSGRBIS | — | QUAN | 13 | 3 | To lot size |
| `PLNME` | PLNME | T006 | UNIT | 3 | 0 | Task list unit of measure |
| `PLSVN` | LOSGRVON | — | QUAN | 13 | 3 | From Lot Size |
| `PDATV` | DATUV | — | DATS | 8 | 0 | Valid-From Date |
| `PAENR` | AENNR | AENR | CHAR | 12 | 0 | Change Number |
| `PLGRP` | VAGRP | T024A | CHAR | 3 | 0 | Responsible planner group/department |
| `LODIV` | LOSDIV | — | QUAN | 13 | 3 | Lot size divisor |
| `STLTY` | STLTY | — | CHAR | 1 | 0 | BOM category |
| `STLBEZ` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `STLST` | STLST | T415S | NUMC | 2 | 0 | BOM status |
| `STLNR` | STNUM | — | CHAR | 8 | 0 | Bill of material |
| `SDATV` | DATUV | — | DATS | 8 | 0 | Valid-From Date |
| `SBMNG` | BASMN | — | QUAN | 13 | 3 | Base quantity |
| `SBMEH` | MEINS | T006 | UNIT | 3 | 0 | Base Unit of Measure |
| `SAENR` | AENNR | AENR | CHAR | 12 | 0 | Change Number |
| `STLAL` | STALT | — | CHAR | 2 | 0 | Alternative BOM |
| `STLAN` | STLAN | T416 | CHAR | 1 | 0 | BOM Usage |
| `SLSVN` | LOSVN | — | QUAN | 13 | 3 | From Lot Size |
| `SLSBS` | LOSBS | — | QUAN | 13 | 3 | To Lot Size |
| `AUFLD` | CO_AUFLD | — | DATS | 8 | 0 | Date of BOM Explosion/Routing Transfer |
| `DISPO` | CO_DISPO | T024D | CHAR | 3 | 0 | MRP controller for the order |
| `AUFPL` | CO_AUFPL | — | NUMC | 10 | 0 | Routing number of operations in the order |
| `FEVOR` | FEVOR | T024F | CHAR | 3 | 0 | Production Supervisor |
| `FHORI` | FHORI | T436A | CHAR | 3 | 0 | Scheduling Margin Key for Floats |
| `TERKZ` | TERMKZ | T482 | CHAR | 1 | 0 | Scheduling type |
| `REDKZ` | REDKZ | — | CHAR | 1 | 0 | Reduction indicator for scheduling |
| `APRIO` | CO_APRIO | — | CHAR | 1 | 0 | Order priority |
| `NTZUE` | NETZ_UEBER | AUFK | CHAR | 12 | 0 | Superior network number |
| `VORUE` | VORG_UEBER | — | CHAR | 4 | 0 | Superior activity |
| `PROFID` | PROFIDNZPL | TCN41 | CHAR | 7 | 0 | Network profile |
| `VORGZ` | VORGZ | — | NUMC | 3 | 0 | Float before production (in days) |
| `SICHZ` | SICHZ | — | NUMC | 3 | 0 | Float after production (in days) |
| `FREIZ` | FREIZ | — | NUMC | 3 | 0 | Release period (in days) |
| `UPTER` | CO_UPTER | — | CHAR | 1 | 0 | Indicator: Change to Scheduled Dates |
| `BEDID` | BEDID | — | NUMC | 12 | 0 | ID of the capacity requirements record |
| `PRONR` | PS_PSP_PRO | PROJ | NUMC | 8 | 0 | Project definition |
| `ZAEHL` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `MZAEHL` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `ZKRIZ` | DZKRIZ | — | NUMC | 7 | 0 | Counter for additional criteria |
| `PRUEFLOS` | QPLOS | — | NUMC | 12 | 0 | Inspection Lot Number |
| `KLVARP` | KALKVARPLN | — | CHAR | 4 | 0 | Costing variant for planned costs |
| `KLVARI` | KALKVARIST | — | CHAR | 4 | 0 | Costing variant for actual costs |
| `RGEKZ` | CO_RGEKZ | — | CHAR | 1 | 0 | Indicator: Backflushing for order |
| `PLART` | PS_PLART | — | CHAR | 1 | 0 | Basis for scheduling |
| `FLG_AOB` | FLG_AOB | — | CHAR | 1 | 0 | Indicator: relationships |
| `FLG_ARBEI` | FLG_ARBEI | — | CHAR | 1 | 0 | Indicator: Default value work is relevant |
| `GLTPP` | CO_GLTPP | — | DATS | 8 | 0 | Finish date (forecast) |
| `GSTPP` | CO_GSTPP | — | DATS | 8 | 0 | Forecast start date |
| `GLTPS` | CO_GLTPS | — | DATS | 8 | 0 | Scheduled forecast finish |
| `GSTPS` | CO_GSTPS | — | DATS | 8 | 0 | Scheduled forecast start |
| `FTRPS` | CO_FTRPS | — | DATS | 8 | 0 | Scheduled release date (forecast) |
| `RDKZP` | REDKZP | — | CHAR | 1 | 0 | Reduction indicator for scheduling (forecast) |
| `TRKZP` | TERMKZP | — | CHAR | 1 | 0 | Scheduling type (forecast) |
| `RUECK` | CO_RUECK | — | NUMC | 10 | 0 | Completion confirmation number for the operation |
| `RMZHL` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `IGMNG` | CO_IGMNG | — | QUAN | 13 | 3 | Yield confirmed from order confirmation |
| `RATID` | BEDID | — | NUMC | 12 | 0 | ID of the capacity requirements record |
| `GROID` | BEDID | — | NUMC | 12 | 0 | ID of the capacity requirements record |
| `CUOBJ` | CUOBJ | — | NUMC | 18 | 0 | Configuration (internal object number) |
| `GLUZS` | CO_GLUZS | — | TIMS | 6 | 0 | Scheduled finish time |
| `GSUZS` | CO_GSUZS | — | TIMS | 6 | 0 | Scheduled Start (Time) |
| `REVLV` | REVLV | — | CHAR | 2 | 0 | Revision Level |
| `RSHTY` | CR_OBJTY | — | CHAR | 2 | 0 | Object types of the CIM resource |
| `RSHID` | CR_OBJID | CRID | NUMC | 8 | 0 | Object ID of the resource |
| `RSNTY` | CR_OBJTY | — | CHAR | 2 | 0 | Object types of the CIM resource |
| `RSNID` | CR_OBJID | CRID | NUMC | 8 | 0 | Object ID of the resource |
| `NAUTERM` | CO_NAUTERM | — | CHAR | 1 | 0 | Indicator: Do not schedule automatically |
| `NAUCOST` | CO_NAUCOST | — | CHAR | 1 | 0 | Indicator: Do not cost automatically |
| `STUFE` | HISTU | — | DEC | 2 | 0 | Level (in multi-level BOM explosions) |
| `WEGXX` | WEGXX | — | DEC | 4 | 0 | Path (for multi-level BOM explosions) |
| `VWEGX` | WEGXX | — | DEC | 4 | 0 | Path (for multi-level BOM explosions) |
| `ARSNR` | RSNUM | — | NUMC | 10 | 0 | Number of Reservation/Dependent Requirement |
| `ARSPS` | CO_POSNR | — | NUMC | 4 | 0 | Order Item Number |
| `MAUFNR` | MAUFNR | — | CHAR | 12 | 0 | Number of superior order |
| `LKNOT` | CO_LKNOT | — | CHAR | 12 | 0 | Left node in collective order |
| `RKNOT` | CO_RKNOT | — | CHAR | 12 | 0 | Right node of a collective order |
| `PRODNET` | CO_PRODNET | — | CHAR | 1 | 0 | Indicator: Order is part of collective order |
| `IASMG` | CO_IASMG | — | QUAN | 13 | 3 | Scrap confirmed for order |
| `ABARB` | CO_ABARB | — | NUMC | 3 | 0 | Confirmation: Degree of processing |
| `AUFNT` | CO_TEILNET | — | CHAR | 12 | 0 | Number of superior network |
| `AUFPT` | CO_AUFPL | — | NUMC | 10 | 0 | Routing number of operations in the order |
| `APLZT` | CO_APLZL | — | NUMC | 8 | 0 | General counter for order |
| `NO_DISP` | NO_DISP_PLUS | — | CHAR | 1 | 0 | Effective for Materials Planning |
| `CSPLIT` | CSPLIT | MAKV | CHAR | 4 | 0 | Apportionment Structure |
| `AENNR` | AENNR | AENR | CHAR | 12 | 0 | Change Number |
| `CY_SEQNR` | CY_SEQNR | — | NUMC | 14 | 0 | Seq. number order |
| `BREAKS` | BREAKS | — | CHAR | 1 | 0 | Indicator:  Scheduling allowing for breaks |
| `VORGZ_TRM` | VORGZ_TRM | — | DEC | 6 | 3 | Scheduled float before production in days |
| `SICHZ_TRM` | SICHZ_TRM | — | DEC | 6 | 3 | Scheduled float after production in days |
| `TRMDT` | TRMDT | — | DATS | 8 | 0 | Date of the last scheduling |
| `GLUZP` | CO_GLUZP | — | TIMS | 6 | 0 | Basic finish (time) |
| `GSUZP` | CO_GSUZP | — | TIMS | 6 | 0 | Basic start time |
| `GSUZI` | CO_GSUZI | — | TIMS | 6 | 0 | Actual start time |
| `GEUZI` | CO_GEUZI | — | TIMS | 6 | 0 | Confirmed order finish (time) |
| `GLUPP` | CO_GLUPP | — | TIMS | 6 | 0 | Forecast finish (time) |
| `GSUPP` | CO_GSUPP | — | TIMS | 6 | 0 | Forecast start (time) |
| `GLUPS` | CO_GLUPS | — | TIMS | 6 | 0 | Scheduled forecast finish time |
| `GSUPS` | CO_GSUPS | — | TIMS | 6 | 0 | Scheduled start time (Forecast) |
| `CHSCH` | KALSMA_CH | T683 | CHAR | 6 | 0 | Search procedure for batch determination |
| `KAPT_VORGZ` | KAPT_VORGZ | — | NUMC | 3 | 0 | Float (bef. production) remaining after finite scheduling |
| `KAPT_SICHZ` | KAPT_SICHZ | — | NUMC | 3 | 0 | Remaining float after finite scheduling |
| `LEAD_AUFNR` | CO_LAUFNR | AUFK | CHAR | 12 | 0 | Leading order in current processing |
| `PNETSTARTD` | CO_PSTARTD | — | DATS | 8 | 0 | Outline start of collective network (date) |
| `PNETSTARTT` | CO_PSTARTT | — | TIMS | 6 | 0 | Start time of a collective order |
| `PNETENDD` | CO_PENDD | — | DATS | 8 | 0 | Outline finish of collective order (date) |
| `PNETENDT` | CO_PENDT | — | TIMS | 6 | 0 | Outline finish time |
| `KBED` | KBED_D | — | CHAR | 1 | 0 | Ind: do not create capacity requirements |
| `KKALKR` | COMP_CALC | — | CHAR | 1 | 0 | Indicator: Components will not be costed |
| `SFCPF` | CO_PRODPRF | TCO43 | CHAR | 6 | 0 | Production Scheduling Profile |
| `RMNGA` | RMNGA | — | QUAN | 13 | 3 | Total confirmed rework quantity |
| `GSBTR` | CO_GSBTR | — | DATS | 8 | 0 | Overall commitment date |
| `VFMNG` | CO_VFMNG | — | QUAN | 13 | 3 | Committed quantity for order acc. to ATP check components |
| `NOPCOST` | CO_NOPCOST | — | CHAR | 1 | 0 | Do not calculate planned costs for order |
| `NETZKONT` | NETZKONT | — | CHAR | 1 | 0 | Indicator for the account assignment of a network(hdr/act.) |
| `ATRKZ` | ATRKZ | — | CHAR | 1 | 0 | Request ID |
| `OBJTYPE` | OCM_OBJ_TYPE | — | CHAR | 1 | 0 | Change indicator |
| `CH_PROC` | OCM_CH_PROC | — | CHAR | 1 | 0 | Process that has lead to the change of an object |
| `KAPVERSA` | KAPVERSA | — | NUMC | 2 | 0 | Version of Available Capacity |
| `COLORDPROC` | CO_COLORDPRC | — | CHAR | 1 | 0 | Collective order with/without automatic goods movement |
| `KZERB` | PS_KZERB | — | CHAR | 1 | 0 | Indicator: Project summarization via master data charact. |
| `CONF_KEY` | CC_CONF_KEY | — | NUMC | 8 | 0 | Identical object |
| `ST_ARBID` | OBJEKTID | — | NUMC | 8 | 0 | Object ID |
| `VSNMR_V` | VSNMR_V | — | CHAR | 12 | 0 | Sales document version number |
| `TERHW` | TERHW | — | CHAR | 1 | 0 | Scheduling note from order scheduling |
| `SPLSTAT` | SPLIT_STAT | — | CHAR | 1 | 0 | Status of an order in a split hierarchy |
| `COSTUPD` | CN_COSTUPD | — | CHAR | 1 | 0 | Costs are updated |
| `MAX_GAMNG` | CO_MES_MAX_GAMNG | — | QUAN | 13 | 3 | Maximum Value of Total Order Quantity After Distribution |
| `MES_ROUTINGID` | CO_MES_INT_ROUTINGID | — | CHAR | 64 | 0 | Key of a Routing from an ME System |
| `ADPSP` | ADCOMPARE | — | CHAR | 40 | 0 | PM/PS Reference Element |
| `RMANR` | VBELN | — | CHAR | 10 | 0 | Sales and Distribution Document Number |
| `POSNR_RMA` | POSNR | — | NUMC | 6 | 0 | Item number of the SD document |
| `POSNV_RMA` | POSNR | — | NUMC | 6 | 0 | Item number of the SD document |
| `CFB_MAXLZ` | MAXLZ | — | DEC | 5 | 0 | Maximum Storage Period |
| `CFB_LZEIH` | LZEIH | T006 | UNIT | 3 | 0 | Unit for maximum storage period |
| `CFB_ADTDAYS` | CFB_ADTDAYS | — | DEC | 4 | 0 | Additional Days |
| `CFB_DATOFM` | CFB_DATOFM | — | DATS | 8 | 0 | Date of Manufacture |
| `CFB_BBDPI` | CFB_BBD_PPPI | — | DATS | 8 | 0 | Best-Before Date (BBD)/ Shelf Life Expiration Date (SLED) |
| `MILL_RATIO` | MILL_RATIO | — | INT4 | 10 | 0 | Factor for Quantity-Based Settlement |
| `BMEINS` | MEINS | — | UNIT | 3 | 0 | Base Unit of Measure |
| `BMENGE` | BASMN | — | QUAN | 13 | 3 | Base quantity |
| `MILL_OC_ZUSKZ` | MILL_OC_ZUSKZ | — | CHAR | 1 | 0 | Combination Indicator |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABGSL` | CAUFV | MANDT | TKKAA |  | |
| `ABGSL` | CAUFV | ABGSL | TKKAA |  | |
| `ABKRS` | CAUFV | MANDT | TKO08 |  | |
| `ABKRS` | CAUFV | KOKRS | TKO08 |  | |
| `ABKRS` | CAUFV | ABKRS | TKO08 |  | |
| `ABUKR` | CAUFV | MANDT | T001 |  | |
| `ABUKR` | CAUFV | ABUKR | T001 |  | |
| `AENNR` | CAUFV | MANDT | AENR |  | |
| `AENNR` | CAUFV | AENNR | AENR |  | |
| `AKSTL` | CAUFV | AKSTL | CSKS |  | |
| `AKSTL` | * |  | CSKS |  | |
| `AKSTL` | CAUFV | MANDT | CSKS |  | |
| `AKSTL` | CAUFV | KOKRS | CSKS |  | |
| `ANFAUFNR` | CAUFV | MANDT | AUFK |  | |
| `ANFAUFNR` | CAUFV | ANFAUFNR | AUFK |  | |
| `AUART` | CAUFV | MANDT | T003O |  | |
| `AUART` | CAUFV | AUART | T003O |  | |
| `AUFK_STATUS` | CAUFV | MANDT | ACTCMB_TAB |  | |
| `AUFK_STATUS` | CAUFV | AUFK_STATUS | ACTCMB_TAB |  | |
| `AWSLS` | CAUFV | MANDT | TKV01 |  | |
| `AWSLS` | TKV01 | AWOBA | TKV01 |  | |
| `AWSLS` | CAUFV | AWSLS | TKV01 |  | |
| `BEMOT` | CAUFV | BEMOT | TBMOT |  | |
| `BEMOT` | CAUFV | MANDT | TBMOT |  | |
| `BUKRS` | CAUFV | MANDT | T001 |  | |
| `BUKRS` | CAUFV | BUKRS | T001 |  | |
| `CFB_LZEIH` | SYST | MANDT | T006 |  | |
| `CFB_LZEIH` | CAUFV | CFB_LZEIH | T006 |  | |
| `CHSCH` | CAUFV | MANDT | T683 |  | |
| `CHSCH` | &#039;H&#039; |  | T683 |  | |
| `CHSCH` | &#039;PP&#039; |  | T683 |  | |
| `CHSCH` | CAUFV | CHSCH | T683 |  | |
| `CLAIM_CONTROL` | SYST | MANDT | WTYSCC_CLM_CONT |  | |
| `CLAIM_CONTROL` | CAUFV | CLAIM_CONTROL | WTYSCC_CLM_CONT |  | |
| `CSPLIT` | CAUFV | MANDT | MAKV |  | |
| `CSPLIT` | CAUFV | STLBEZ | MAKV |  | |
| `CSPLIT` | AUFK | WERKS | MAKV |  | |
| `CSPLIT` | CAUFV | CSPLIT | MAKV |  | |
| `CYCLE` | CAUFV | MANDT | CSKS |  | |
| `CYCLE` | CAUFV | KOKRS | CSKS |  | |
| `CYCLE` | CAUFV | CYCLE | CSKS |  | |
| `CYCLE` | * |  | CSKS |  | |
| `DISPO` | CAUFV | MANDT | T024D |  | |
| `DISPO` | AUFK | WERKS | T024D |  | |
| `DISPO` | CAUFV | DISPO | T024D |  | |
| `ETYPE` | GJV_OBJDAT | BUKRS | T8JG |  | |
| `ETYPE` | CAUFV | VNAME | T8JG |  | |
| `ETYPE` | CAUFV | ETYPE | T8JG |  | |
| `ETYPE` | * |  | T8JG |  | |
| `ETYPE` | SYST | MANDT | T8JG |  | |
| `FERC_IND` | CAUFV | MANDT | FERC_C7 |  | |
| `FERC_IND` | CAUFV | FERC_IND | FERC_C7 |  | |
| `FEVOR` | CAUFV | FEVOR | T024F |  | |
| `FEVOR` | CAUFV | MANDT | T024F |  | |
| `FEVOR` | AUFK | WERKS | T024F |  | |
| `FHORI` | CAUFV | MANDT | T436A |  | |
| `FHORI` | AUFK | WERKS | T436A |  | |
| `FHORI` | CAUFV | FHORI | T436A |  | |
| `FUNC_AREA` | CAUFV | MANDT | TFKB |  | |
| `FUNC_AREA` | CAUFV | FUNC_AREA | TFKB |  | |
| `GMEIN` | CAUFV | MANDT | T006 |  | |
| `GMEIN` | CAUFV | GMEIN | T006 |  | |
| `GSBER` | CAUFV | MANDT | TGSB |  | |
| `GSBER` | CAUFV | GSBER | TGSB |  | |
| `IVPRO` | CAUFV | MANDT | TAPRF |  | |
| `IVPRO` | CAUFV | IVPRO | TAPRF |  | |
| `IZWEK` | CAUFV | MANDT | T087I |  | |
| `IZWEK` | CAUFV | IZWEK | T087I |  | |
| `JV_JIBCL` | SYST | MANDT | T8J6A |  | |
| `JV_JIBCL` | GJV_OBJDAT | BUKRS | T8J6A |  | |
| `JV_JIBCL` | CAUFV | JV_JIBCL | T8J6A |  | |
| `JV_JIBSA` | SYST | MANDT | T8J6C |  | |
| `JV_JIBSA` | GJV_OBJDAT | BUKRS | T8J6C |  | |
| `JV_JIBSA` | CAUFV | JV_JIBCL | T8J6C |  | |
| `JV_JIBSA` | CAUFV | JV_JIBSA | T8J6C |  | |
| `KALSM` | CAUFV | KAPPL | T683 |  | |
| `KALSM` | CAUFV | KALSM | T683 |  | |
| `KALSM` | CAUFV | MANDT | T683 |  | |
| `KALSM` | CAUFV | KVEWE | T683 |  | |
| `KAPPL` | CAUFV | KAPPL | T681A |  | |
| `KDAUF` | CAUFV | MANDT | VBUK |  | |
| `KDAUF` | CAUFV | KDAUF | VBUK |  | |
| `KOKRS` | CAUFV | KOKRS | TKA01 |  | |
| `KOKRS` | CAUFV | MANDT | TKA01 |  | |
| `KOSTL` | CAUFV | MANDT | CSKS |  | |
| `KOSTL` | CAUFV | KOKRS | CSKS |  | |
| `KOSTL` | CAUFV | KOSTL | CSKS |  | |
| `KOSTL` | * |  | CSKS |  | |
| `KOSTV` | CAUFV | KOKRS | CSKS |  | |
| `KOSTV` | CAUFV | KOSTV | CSKS |  | |
| `KOSTV` | * |  | CSKS |  | |
| `KOSTV` | CAUFV | MANDT | CSKS |  | |
| `KSTAR` | CAUFV | KOKRS | CSKB |  | |
| `KSTAR` | CAUFV | KSTAR | CSKB |  | |
| `KSTAR` | * |  | CSKB |  | |
| `KSTAR` | CAUFV | MANDT | CSKB |  | |
| `KVEWE` | CAUFV | KVEWE | T681V |  | |
| `LEAD_AUFNR` | CAUFV | LEAD_AUFNR | AUFK |  | |
| `LEAD_AUFNR` | CAUFV | MANDT | AUFK |  | |
| `LOGSYSTEM` | CAUFV | LOGSYSTEM | TBDLS |  | |
| `MANDT` | CAUFV | MANDT | T000 |  | |
| `NTZUE` | CAUFV | MANDT | AUFK |  | |
| `NTZUE` | CAUFV | NTZUE | AUFK |  | |
| `OBJNR` | CAUFV | OBJNR | ONR00 |  | |
| `OBJNR` | CAUFV | MANDT | ONR00 |  | |
| `OIHANTYP` | SYST | MANDT | OIH5 |  | |
| `OIHANTYP` | CAUFV | OIHANTYP | OIH5 |  | |
| `PAENR` | CAUFV | MANDT | AENR |  | |
| `PAENR` | CAUFV | PAENR | AENR |  | |
| `PLGRP` | CAUFV | MANDT | T024A |  | |
| `PLGRP` | AUFK | WERKS | T024A |  | |
| `PLGRP` | CAUFV | PLGRP | T024A |  | |
| `PLNAW` | CAUFV | MANDT | TCA09 |  | |
| `PLNAW` | CAUFV | PLNAW | TCA09 |  | |
| `PLNBEZ` | CAUFV | MANDT | MARA |  | |
| `PLNBEZ` | CAUFV | PLNBEZ | MARA |  | |
| `PLNME` | CAUFV | PLNME | T006 |  | |
| `PLNME` | CAUFV | MANDT | T006 |  | |
| `PRCTR` | CAUFV | MANDT | CEPC |  | |
| `PRCTR` | CAUFV | PRCTR | CEPC |  | |
| `PRCTR` | * |  | CEPC |  | |
| `PRCTR` | CAUFV | KOKRS | CEPC |  | |
| `PROFID` | CAUFV | MANDT | TCN41 |  | |
| `PROFID` | CAUFV | PLNAW | TCN41 |  | |
| `PROFID` | CAUFV | PROFID | TCN41 |  | |
| `PRONR` | CAUFV | MANDT | PROJ |  | |
| `PRONR` | CAUFV | PRONR | PROJ |  | |
| `PSPEL` | CAUFV | MANDT | PRPS |  | |
| `PSPEL` | CAUFV | PSPEL | PRPS |  | |
| `PVERW` | CAUFV | MANDT | T411 |  | |
| `PVERW` | CAUFV | PVERW | T411 |  | |
| `RECID` | CAUFV | RECID | T8JJ |  | |
| `RECID` | SYST | MANDT | T8JJ |  | |
| `RECID` | GJV_OBJDAT | BUKRS | T8JJ |  | |
| `REFNR` | CAUFV | MANDT | AUFK |  | |
| `REFNR` | CAUFV | REFNR | AUFK |  | |
| `RSHID` | CAUFV | RSHID | CRID |  | |
| `RSHID` | CAUFV | MANDT | CRID |  | |
| `RSHID` | CAUFV | RSHTY | CRID |  | |
| `RSNID` | CAUFV | MANDT | CRID |  | |
| `RSNID` | CAUFV | RSNTY | CRID |  | |
| `RSNID` | CAUFV | RSNID | CRID |  | |
| `SAENR` | CAUFV | MANDT | AENR |  | |
| `SAENR` | CAUFV | SAENR | AENR |  | |
| `SBMEH` | CAUFV | MANDT | T006 |  | |
| `SBMEH` | CAUFV | SBMEH | T006 |  | |
| `SFCPF` | CAUFV | MANDT | TCO43 |  | |
| `SFCPF` | AUFK | WERKS | TCO43 |  | |
| `SFCPF` | CAUFV | SFCPF | TCO43 |  | |
| `SIZECL` | CAUFV | SIZECL | TAIF5 |  | |
| `SIZECL` | CAUFV | MANDT | TAIF5 |  | |
| `SOWRK` | CAUFV | SOWRK | T001W |  | |
| `SOWRK` | CAUFV | MANDT | T001W |  | |
| `STLAN` | CAUFV | MANDT | T416 |  | |
| `STLAN` | CAUFV | STLAN | T416 |  | |
| `STLBEZ` | CAUFV | MANDT | MARA |  | |
| `STLBEZ` | CAUFV | STLBEZ | MARA |  | |
| `STLST` | CAUFV | MANDT | T415S |  | |
| `STLST` | CAUFV | STLST | T415S |  | |
| `STORT` | CAUFV | MANDT | T499S |  | |
| `STORT` | CAUFV | SOWRK | T499S |  | |
| `STORT` | CAUFV | STORT | T499S |  | |
| `TERKZ` | CAUFV | MANDT | T482 |  | |
| `TERKZ` | CAUFV | TERKZ | T482 |  | |
| `TXJCD` | CAUFV | MANDT | TTXJ |  | |
| `TXJCD` | * |  | TTXJ |  | |
| `TXJCD` | CAUFV | TXJCD | TTXJ |  | |
| `UMWKZ` | CAUFV | MANDT | T087K |  | |
| `UMWKZ` | CAUFV | UMWKZ | T087K |  | |
| `UPDATE_CONTROL` | SYST | MANDT | WTYSCC_UPDT_CONT |  | |
| `UPDATE_CONTROL` | CAUFV | UPDATE_CONTROL | WTYSCC_UPDT_CONT |  | |
| `VERAA_USER` | * |  | USR02 |  | |
| `VERAA_USER` | CAUFV | VERAA_USER | USR02 |  | |
| `VNAME` | SYST | MANDT | T8JV |  | |
| `VNAME` | GJV_OBJDAT | BUKRS | T8JV |  | |
| `VNAME` | CAUFV | VNAME | T8JV |  | |
| `WAERS` | CAUFV | MANDT | TCURC |  | |
| `WAERS` | CAUFV | WAERS | TCURC |  | |
| `WERKS` | CAUFV | MANDT | T001W |  | |
| `WERKS` | CAUFV | WERKS | T001W |  | |
| `ZSCHM` | CAUFV | MANDT | TPI01 |  | |
| `ZSCHM` | CAUFV | ZSCHM | TPI01 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `ziscs0252f01.txt`
- `zisdm0018.txt`
- `zisdm0019.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_