# `VIAUFKST`

**Description:** Order Tracking — order status tracking
**Category:** Standard SAP Table
**References:** 59 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/viaufkst/) — validated 2026-05-30, schema v1.0
**Schema fields:** 227 fields | **Data types:** CHAR(142), CUKY(1), CURR(1), DATS(29), DEC(1), FLTP(1), INT1(1), INT4(2), NUMC(26), QUAN(8), TIMS(11), UNIT(4)

## Key Fields
`BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `ARTPR` | ARTPR | T356A | CHAR | 2 | 0 | Priority Type |
| `PRIOK` | PRIOK | T356 | CHAR | 1 | 0 | Priority |
| `EQUNR` | EQUNR | EQUI | CHAR | 18 | 0 | Equipment Number |
| `BAUTL` | BAUTL | MARA | CHAR | 18 | 0 | Assembly |
| `ILOAN` | ILOAN | ILOA | CHAR | 12 | 0 | Location and account assignment for technical object |
| `ILOAI` | ILOAI | — | CHAR | 1 | 0 | ILOA Individual |
| `ANLZU` | ANLZU | T357M | CHAR | 1 | 0 | Syst.Condition |
| `IWERK` | IWERK | T399I | CHAR | 4 | 0 | Maintenance Planning Plant |
| `INGPR` | INGRP | T024I | CHAR | 3 | 0 | Planner Group for Customer Service and Plant Maintenance |
| `APGRP` | VAGRP | T024A | CHAR | 3 | 0 | Responsible planner group/department |
| `PM_OBJTY` | PM_OBJTY | — | CHAR | 2 | 0 | Object Type of CIM Resources for Work Center |
| `GEWRK` | LGWID | CRID | NUMC | 8 | 0 | Object ID of the Work Center |
| `KUNUM` | KUNUM | KNA1 | CHAR | 10 | 0 | Customer Number |
| `ANING` | ANING | — | CHAR | 12 | 0 | Name of Person Reponsible for System |
| `GAUZT` | GAUZT | — | FLTP | 16 | 16 | Planned downtime in hours |
| `GAUEH` | MAUEH | T006 | UNIT | 3 | 0 | Unit for Breakdown Duration |
| `ANLBD` | ANLBD | — | DATS | 8 | 0 | Date until which the system is available |
| `ANLVD` | ANLVD | — | DATS | 8 | 0 | Date from which the system is available |
| `ANLBZ` | ANLBZ | — | TIMS | 6 | 0 | Time until which the system is available |
| `ANLVZ` | ANLVZ | — | TIMS | 6 | 0 | Time from Which System is Available |
| `INSPK` | INSPK | — | CHAR | 12 | 0 | Name of Person Responsible for Technical Inspection |
| `DATAN` | DATAN | — | DATS | 8 | 0 | Date of Technical Inspection |
| `WARPL` | WARPL | MPLA | CHAR | 12 | 0 | Maintenance Plan |
| `ABNUM` | ABNUM | — | INT4 | 10 | 0 | Maintenance Plan Call Number |
| `WAPOS` | WAPOS | — | CHAR | 16 | 0 | Maintenance item |
| `LAUFN` | LAUFN | AUFK | CHAR | 12 | 0 | Order number |
| `OBKNR` | OBJKNR | SER00 | INT4 | 10 | 0 | Object list number |
| `REVNR` | REVNI | T352R | CHAR | 8 | 0 | Revision for Plant Maintenance and Customer Service |
| `ADDAT` | ADDAT | — | DATS | 8 | 0 | PM Order: Reference Date |
| `ADUHR` | ADUHR | — | TIMS | 6 | 0 | Time of Reference Date |
| `IPHAS` | PM_PHASE | — | CHAR | 1 | 0 | Maintenance Processing Phase |
| `ILART` | ILA | T353I | CHAR | 3 | 0 | Maintenance activity type |
| `QMNUM` | QMNUM | QMEL | CHAR | 12 | 0 | Notification No |
| `HISDA` | HISDA | — | DATS | 8 | 0 | PM request: History date |
| `AKKNZ` | AKKNZ | — | CHAR | 1 | 0 | Order Category Indicator Plant Maintenance |
| `PLKNZ` | AUF_PLKNZ | — | CHAR | 1 | 0 | Maintenance order planning indicator |
| `SERIALNR` | GERNR | — | CHAR | 18 | 0 | Serial Number |
| `SERMAT` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `DEVICEID` | DEVICEID | — | CHAR | 40 | 0 | Additional Device Data |
| `SCREENTY` | SCRTP | TQBT | CHAR | 4 | 0 | Scenario or Subscreen Category |
| `ADPSP` | ADDCOMPARE_CORE | — | CHAR | 40 | 0 | Reference Element PM/PS |
| `RSUPG` | RSUPG | — | CHAR | 1 | 0 | Upgrade Order Indicator |
| `/ISDFPS/OBJNR` | J_OBJNR | — | CHAR | 22 | 0 | Object number |
| `/ISDFPS/MEQUI` | /ISDFPS/MEQUI | — | CHAR | 18 | 0 | Master Equipment |
| `UII` | UII_CHAR72 | — | CHAR | 72 | 0 | Unique Item Identifier |
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
| `SOWRK` | AUFSOWRK | T001W | CHAR | 4 | 0 | Location plant |
| `ASTKZ` | AUFSTKZ | — | CHAR | 1 | 0 | Identifier for statistical order |
| `WAERS` | AUFWAERS | TCURC | CUKY | 5 | 0 | Order Currency |
| `ASTNR` | AUFASTNR | — | NUMC | 2 | 0 | Order status |
| `STDAT` | AUFSTDAT | — | DATS | 8 | 0 | Date of last status change |
| `ESTNR` | AUFESTNR | TKO03 | NUMC | 2 | 0 | Status reached so far |
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
| `SAKNR` | AUFSAKNR | SKB1 | CHAR | 10 | 0 | G/L account for basic settlement |
| `SETNM` | AUFSETNM | — | CHAR | 12 | 0 | Allocation set |
| `CYCLE` | ST_KOSTL | CSKS | CHAR | 10 | 0 | Cost center to which costs are actually posted |
| `SDATE` | SDATE | — | DATS | 8 | 0 | Start Date |
| `SEQNR` | AUFSEQNR | — | NUMC | 4 | 0 | Sequence number |
| `USER2` | AUFUSER2 | — | CHAR | 20 | 0 | Person responsible |
| `USER4` | AUFUSER4 | — | CURR | 11 | 2 | Estimated total costs of order |
| `OBJNR` | J_OBJNR | ONR00 | CHAR | 22 | 0 | Object number |
| `PRCTR` | PRCTR | CEPC | CHAR | 10 | 0 | Profit Center |
| `PSPEL` | PS_PSP_ELE | PRPS | NUMC | 8 | 0 | Work breakdown structure element (WBS element) |
| `AWSLS` | AWSLS | TKV01 | CHAR | 6 | 0 | Variance Key |
| `ABGSL` | ABGR_SCHL | TKKAA | CHAR | 6 | 0 | Results Analysis Key |
| `KDAUF` | KDAUF | VBUK | CHAR | 10 | 0 | Sales Order Number |
| `KDPOS` | KDPOS | — | NUMC | 6 | 0 | Item Number in Sales Order |
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
| `STORT` | PMLOC | T499S | CHAR | 10 | 0 | Location of maintenance object |
| `KOSTL` | KOSTL | — | CHAR | 10 | 0 | Cost Center |
| `TPLNR` | TPLNR | IFLOT | CHAR | 30 | 0 | Functional Location |
| `ABCKZ` | ABCKZ | T370C | CHAR | 1 | 0 | ABC indicator for technical object |
| `EQFNR` | EQFNR | — | CHAR | 30 | 0 | Sort field |
| `SWERK` | SWERK | T001W | CHAR | 4 | 0 | Maintenance plant |
| `MSGRP` | RAUMNR | — | CHAR | 8 | 0 | Room |
| `BEBER` | BEBER | T357 | CHAR | 3 | 0 | Plant section |
| `CR_OBJTY` | CR_OBJTY | — | CHAR | 2 | 0 | Object types of the CIM resource |
| `PPSID` | PPSID | CRID | NUMC | 8 | 0 | Object ID of PP work center |
| `PROID` | PS_PSP_PNR | PRPS | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `ANLNR` | ANLN1 | — | CHAR | 12 | 0 | Main Asset Number |
| `ANLUN` | ANLN2 | — | CHAR | 4 | 0 | Asset Subnumber |
| `DAUFN` | DAUFN | AUFK | CHAR | 12 | 0 | Standing order number |
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
| `AUFNT` | CO_TEILNET | — | CHAR | 12 | 0 | Number of superior network |
| `AUFPT` | CO_AUFPL | — | NUMC | 10 | 0 | Routing number of operations in the order |
| `APLZT` | CO_APLZL | — | NUMC | 8 | 0 | General counter for order |
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
| `MAUFNR` | MAUFNR | — | CHAR | 12 | 0 | Number of superior order |
| `LEAD_AUFNR` | CO_LAUFNR | AUFK | CHAR | 12 | 0 | Leading order in current processing |
| `OWNER` | ILOM_OWNER | — | CHAR | 1 | 0 | Object reference indicator |
| `VKORG` | VKORG | TVKO | CHAR | 4 | 0 | Sales Organization |
| `VTWEG` | VTWEG | TVKOV | CHAR | 2 | 0 | Distribution Channel |
| `SPART` | SPART | TVTA | CHAR | 2 | 0 | Division |
| `GLUZP` | CO_GLUZP | — | TIMS | 6 | 0 | Basic finish (time) |
| `GSUZP` | CO_GSUZP | — | TIMS | 6 | 0 | Basic start time |
| `GLUZS` | CO_GLUZS | — | TIMS | 6 | 0 | Scheduled finish time |
| `GSUZS` | CO_GSUZS | — | TIMS | 6 | 0 | Scheduled Start (Time) |
| `GEUZI` | CO_GEUZI | — | TIMS | 6 | 0 | Confirmed order finish (time) |
| `GSUZI` | CO_GSUZI | — | TIMS | 6 | 0 | Actual start time |
| `ADRNR_ILOA` | AD_ADDRNUM | ADRC | CHAR | 10 | 0 | Address number |
| `NO_DISP` | NO_DISP_PLUS | — | CHAR | 1 | 0 | Effective for Materials Planning |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABCKZ` | VIAUFKST | MANDT | T370C |  | |
| `ABCKZ` | VIAUFKST | ABCKZ | T370C |  | |
| `ABGSL` | VIAUFKST | MANDT | TKKAA |  | |
| `ABGSL` | VIAUFKST | ABGSL | TKKAA |  | |
| `ABKRS` | VIAUFKST | MANDT | TKO08 |  | |
| `ABKRS` | VIAUFKST | KOKRS | TKO08 |  | |
| `ABKRS` | VIAUFKST | ABKRS | TKO08 |  | |
| `ADRNR_ILOA` | VIAUFKST | MANDT | ADRC |  | |
| `ADRNR_ILOA` | VIAUFKST | ADRNR_ILOA | ADRC |  | |
| `ADRNR_ILOA` | * |  | ADRC |  | |
| `ADRNR_ILOA` | * |  | ADRC |  | |
| `ANLZU` | SYST | MANDT | T357M |  | |
| `ANLZU` | VIAUFKST | ANLZU | T357M |  | |
| `APGRP` | VIAUFKST | MANDT | T024A |  | |
| `APGRP` | VIAUFKST | IWERK | T024A |  | |
| `APGRP` | VIAUFKST | APGRP | T024A |  | |
| `ARTPR` | VIAUFKST | MANDT | T356A |  | |
| `ARTPR` | VIAUFKST | ARTPR | T356A |  | |
| `AUART` | VIAUFKST | MANDT | T003O |  | |
| `AUART` | VIAUFKST | AUART | T003O |  | |
| `AUFK_STATUS` | VIAUFKST | MANDT | ACTCMB_TAB |  | |
| `AUFK_STATUS` | VIAUFKST | AUFK_STATUS | ACTCMB_TAB |  | |
| `AUFNR` | VIAUFKST | AUFNR | AUFK |  | |
| `AUFNR` | VIAUFKST | MANDT | AUFK |  | |
| `AWSLS` | VIAUFKST | MANDT | TKV01 |  | |
| `AWSLS` | TKV01 | AWOBA | TKV01 |  | |
| `AWSLS` | VIAUFKST | AWSLS | TKV01 |  | |
| `BAUTL` | VIAUFKST | MANDT | MARA |  | |
| `BAUTL` | VIAUFKST | BAUTL | MARA |  | |
| `BEBER` | VIAUFKST | MANDT | T357 |  | |
| `BEBER` | VIAUFKST | SWERK | T357 |  | |
| `BEBER` | VIAUFKST | BEBER | T357 |  | |
| `BEMOT` | VIAUFKST | BEMOT | TBMOT |  | |
| `BEMOT` | VIAUFKST | MANDT | TBMOT |  | |
| `BUKRS` | VIAUFKST | MANDT | T001 |  | |
| `BUKRS` | VIAUFKST | BUKRS | T001 |  | |
| `CLAIM_CONTROL` | SYST | MANDT | WTYSCC_CLM_CONT |  | |
| `CLAIM_CONTROL` | VIAUFKST | CLAIM_CONTROL | WTYSCC_CLM_CONT |  | |
| `CYCLE` | VIAUFKST | MANDT | CSKS |  | |
| `CYCLE` | VIAUFKST | KOKRS | CSKS |  | |
| `CYCLE` | VIAUFKST | CYCLE | CSKS |  | |
| `CYCLE` | * |  | CSKS |  | |
| `DAUFN` | VIAUFKST | MANDT | AUFK |  | |
| `DAUFN` | VIAUFKST | DAUFN | AUFK |  | |
| `DISPO` | VIAUFKST | MANDT | T024D |  | |
| `DISPO` | AUFK | WERKS | T024D |  | |
| `DISPO` | VIAUFKST | DISPO | T024D |  | |
| `EQUNR` | VIAUFKST | EQUNR | EQUI |  | |
| `EQUNR` | VIAUFKST | MANDT | EQUI |  | |
| `ESTNR` | VIAUFKST | MANDT | TKO03 |  | |
| `ESTNR` | VIAUFKST | AUART | TKO03 |  | |
| `ESTNR` | VIAUFKST | ESTNR | TKO03 |  | |
| `ETYPE` | GJV_OBJDAT | BUKRS | T8JG |  | |
| `ETYPE` | VIAUFKST | VNAME | T8JG |  | |
| `ETYPE` | VIAUFKST | ETYPE | T8JG |  | |
| `ETYPE` | * |  | T8JG |  | |
| `ETYPE` | SYST | MANDT | T8JG |  | |
| `FERC_IND` | VIAUFKST | MANDT | FERC_C7 |  | |
| `FERC_IND` | VIAUFKST | FERC_IND | FERC_C7 |  | |
| `FEVOR` | VIAUFKST | MANDT | T024F |  | |
| `FEVOR` | AUFK | WERKS | T024F |  | |
| `FEVOR` | VIAUFKST | FEVOR | T024F |  | |
| `FHORI` | AUFK | WERKS | T436A |  | |
| `FHORI` | VIAUFKST | FHORI | T436A |  | |
| `FHORI` | VIAUFKST | MANDT | T436A |  | |
| `GAUEH` | VIAUFKST | GAUEH | T006 |  | |
| `GAUEH` | VIAUFKST | MANDT | T006 |  | |
| `GEWRK` | VIAUFKST | MANDT | CRID |  | |
| `GEWRK` | VIAUFKST | PM_OBJTY | CRID |  | |
| `GEWRK` | VIAUFKST | GEWRK | CRID |  | |
| `GMEIN` | VIAUFKST | MANDT | T006 |  | |
| `GMEIN` | VIAUFKST | GMEIN | T006 |  | |
| `GSBER` | VIAUFKST | MANDT | TGSB |  | |
| `GSBER` | VIAUFKST | GSBER | TGSB |  | |
| `ILART` | VIAUFKST | MANDT | T353I |  | |
| `ILART` | VIAUFKST | ILART | T353I |  | |
| `ILOAN` | VIAUFKST | MANDT | ILOA |  | |
| `ILOAN` | VIAUFKST | ILOAN | ILOA |  | |
| `INGPR` | VIAUFKST | INGPR | T024I |  | |
| `INGPR` | VIAUFKST | MANDT | T024I |  | |
| `INGPR` | VIAUFKST | IWERK | T024I |  | |
| `IWERK` | VIAUFKST | MANDT | T399I |  | |
| `IWERK` | VIAUFKST | IWERK | T399I |  | |
| `JV_JIBCL` | SYST | MANDT | T8J6A |  | |
| `JV_JIBCL` | GJV_OBJDAT | BUKRS | T8J6A |  | |
| `JV_JIBCL` | VIAUFKST | JV_JIBCL | T8J6A |  | |
| `JV_JIBSA` | SYST | MANDT | T8J6C |  | |
| `JV_JIBSA` | GJV_OBJDAT | BUKRS | T8J6C |  | |
| `JV_JIBSA` | VIAUFKST | JV_JIBCL | T8J6C |  | |
| `JV_JIBSA` | VIAUFKST | JV_JIBSA | T8J6C |  | |
| `KALSM` | VIAUFKST | KAPPL | T683 |  | |
| `KALSM` | VIAUFKST | KALSM | T683 |  | |
| `KALSM` | VIAUFKST | MANDT | T683 |  | |
| `KALSM` | VIAUFKST | KVEWE | T683 |  | |
| `KAPPL` | VIAUFKST | KAPPL | T681A |  | |
| `KDAUF` | VIAUFKST | MANDT | VBUK |  | |
| `KDAUF` | VIAUFKST | KDAUF | VBUK |  | |
| `KOKRS` | VIAUFKST | KOKRS | TKA01 |  | |
| `KOKRS` | VIAUFKST | MANDT | TKA01 |  | |
| `KOSTV` | VIAUFKST | MANDT | CSKS |  | |
| `KOSTV` | VIAUFKST | KOKRS | CSKS |  | |
| `KOSTV` | VIAUFKST | KOSTV | CSKS |  | |
| `KOSTV` | * |  | CSKS |  | |
| `KSTAR` | VIAUFKST | KSTAR | CSKB |  | |
| `KSTAR` | * |  | CSKB |  | |
| `KSTAR` | VIAUFKST | MANDT | CSKB |  | |
| `KSTAR` | VIAUFKST | KOKRS | CSKB |  | |
| `KUNUM` | VIAUFKST | MANDT | KNA1 |  | |
| `KUNUM` | VIAUFKST | KUNUM | KNA1 |  | |
| `KVEWE` | VIAUFKST | KVEWE | T681V |  | |
| `LAUFN` | VIAUFKST | MANDT | AUFK |  | |
| `LAUFN` | VIAUFKST | LAUFN | AUFK |  | |
| `LEAD_AUFNR` | VIAUFKST | MANDT | AUFK |  | |
| `LEAD_AUFNR` | VIAUFKST | LEAD_AUFNR | AUFK |  | |
| `MANDT` | VIAUFKST | MANDT | T000 |  | |
| `OBJNR` | VIAUFKST | MANDT | ONR00 |  | |
| `OBJNR` | VIAUFKST | OBJNR | ONR00 |  | |
| `OBKNR` | VIAUFKST | OBKNR | SER00 |  | |
| `OBKNR` | SYST | MANDT | SER00 |  | |
| `OIHANTYP` | SYST | MANDT | OIH5 |  | |
| `OIHANTYP` | VIAUFKST | OIHANTYP | OIH5 |  | |
| `PAENR` | VIAUFKST | MANDT | AENR |  | |
| `PAENR` | VIAUFKST | PAENR | AENR |  | |
| `PLGRP` | AUFK | WERKS | T024A |  | |
| `PLGRP` | VIAUFKST | PLGRP | T024A |  | |
| `PLGRP` | VIAUFKST | MANDT | T024A |  | |
| `PLNAW` | VIAUFKST | MANDT | TCA09 |  | |
| `PLNAW` | VIAUFKST | PLNAW | TCA09 |  | |
| `PLNBEZ` | VIAUFKST | MANDT | MARA |  | |
| `PLNBEZ` | VIAUFKST | PLNBEZ | MARA |  | |
| `PLNME` | VIAUFKST | MANDT | T006 |  | |
| `PLNME` | VIAUFKST | PLNME | T006 |  | |
| `PPSID` | VIAUFKST | MANDT | CRID |  | |
| `PPSID` | VIAUFKST | CR_OBJTY | CRID |  | |
| `PPSID` | VIAUFKST | PPSID | CRID |  | |
| `PRCTR` | * |  | CEPC |  | |
| `PRCTR` | VIAUFKST | KOKRS | CEPC |  | |
| `PRCTR` | VIAUFKST | MANDT | CEPC |  | |
| `PRCTR` | VIAUFKST | PRCTR | CEPC |  | |
| `PRIOK` | VIAUFKST | MANDT | T356 |  | |
| `PRIOK` | VIAUFKST | ARTPR | T356 |  | |
| `PRIOK` | VIAUFKST | PRIOK | T356 |  | |
| `PROFID` | VIAUFKST | PROFID | TCN41 |  | |
| `PROFID` | VIAUFKST | MANDT | TCN41 |  | |
| `PROFID` | VIAUFKST | PLNAW | TCN41 |  | |
| `PROID` | VIAUFKST | MANDT | PRPS |  | |
| `PROID` | VIAUFKST | PROID | PRPS |  | |
| `PRONR` | VIAUFKST | MANDT | PROJ |  | |
| `PRONR` | VIAUFKST | PRONR | PROJ |  | |
| `PSPEL` | VIAUFKST | MANDT | PRPS |  | |
| `PSPEL` | VIAUFKST | PSPEL | PRPS |  | |
| `PVERW` | VIAUFKST | MANDT | T411 |  | |
| `PVERW` | VIAUFKST | PVERW | T411 |  | |
| `QMNUM` | VIAUFKST | MANDT | QMEL |  | |
| `QMNUM` | VIAUFKST | QMNUM | QMEL |  | |
| `RECID` | VIAUFKST | RECID | T8JJ |  | |
| `RECID` | SYST | MANDT | T8JJ |  | |
| `RECID` | GJV_OBJDAT | BUKRS | T8JJ |  | |
| `REFNR` | VIAUFKST | MANDT | AUFK |  | |
| `REFNR` | VIAUFKST | REFNR | AUFK |  | |
| `REVNR` | VIAUFKST | MANDT | T352R |  | |
| `REVNR` | VIAUFKST | IWERK | T352R |  | |
| `REVNR` | VIAUFKST | REVNR | T352R |  | |
| `SAENR` | VIAUFKST | MANDT | AENR |  | |
| `SAENR` | VIAUFKST | SAENR | AENR |  | |
| `SAKNR` | VIAUFKST | MANDT | SKB1 |  | |
| `SAKNR` | VIAUFKST | BUKRS | SKB1 |  | |
| `SAKNR` | VIAUFKST | SAKNR | SKB1 |  | |
| `SBMEH` | VIAUFKST | MANDT | T006 |  | |
| `SBMEH` | VIAUFKST | SBMEH | T006 |  | |
| `SCREENTY` | VIAUFKST | SCREENTY | TQBT |  | |
| `SERMAT` | VIAUFKST | MANDT | MARA |  | |
| `SERMAT` | VIAUFKST | SERMAT | MARA |  | |
| `SOWRK` | VIAUFKST | MANDT | T001W |  | |
| `SOWRK` | VIAUFKST | SOWRK | T001W |  | |
| `SPART` | VIAUFKST | MANDT | TVTA |  | |
| `SPART` | VIAUFKST | VKORG | TVTA |  | |
| `SPART` | VIAUFKST | VTWEG | TVTA |  | |
| `SPART` | VIAUFKST | SPART | TVTA |  | |
| `STLAN` | VIAUFKST | MANDT | T416 |  | |
| `STLAN` | VIAUFKST | STLAN | T416 |  | |
| `STLBEZ` | VIAUFKST | STLBEZ | MARA |  | |
| `STLBEZ` | VIAUFKST | MANDT | MARA |  | |
| `STLST` | VIAUFKST | MANDT | T415S |  | |
| `STLST` | VIAUFKST | STLST | T415S |  | |
| `STORT` | VIAUFKST | SWERK | T499S |  | |
| `STORT` | VIAUFKST | STORT | T499S |  | |
| `STORT` | VIAUFKST | MANDT | T499S |  | |
| `SWERK` | VIAUFKST | MANDT | T001W |  | |
| `SWERK` | VIAUFKST | SWERK | T001W |  | |
| `TERKZ` | VIAUFKST | MANDT | T482 |  | |
| `TERKZ` | VIAUFKST | TERKZ | T482 |  | |
| `TPLNR` | VIAUFKST | MANDT | IFLOT |  | |
| `TPLNR` | VIAUFKST | TPLNR | IFLOT |  | |
| `UPDATE_CONTROL` | SYST | MANDT | WTYSCC_UPDT_CONT |  | |
| `UPDATE_CONTROL` | VIAUFKST | UPDATE_CONTROL | WTYSCC_UPDT_CONT |  | |
| `VERAA_USER` | * |  | USR02 |  | |
| `VERAA_USER` | VIAUFKST | VERAA_USER | USR02 |  | |
| `VKORG` | VIAUFKST | MANDT | TVKO |  | |
| `VKORG` | VIAUFKST | VKORG | TVKO |  | |
| `VNAME` | SYST | MANDT | T8JV |  | |
| `VNAME` | GJV_OBJDAT | BUKRS | T8JV |  | |
| `VNAME` | VIAUFKST | VNAME | T8JV |  | |
| `VOGRP` | VIAUFKST | MANDT | TKAVG |  | |
| `VOGRP` | VIAUFKST | OBJID | TKAVG |  | |
| `VOGRP` | VIAUFKST | VOGRP | TKAVG |  | |
| `VOGRP` | * |  | TKAVG |  | |
| `VTWEG` | VIAUFKST | VTWEG | TVKOV |  | |
| `VTWEG` | VIAUFKST | MANDT | TVKOV |  | |
| `VTWEG` | VIAUFKST | VKORG | TVKOV |  | |
| `WAERS` | VIAUFKST | MANDT | TCURC |  | |
| `WAERS` | VIAUFKST | WAERS | TCURC |  | |
| `WARPL` | VIAUFKST | MANDT | MPLA |  | |
| `WARPL` | VIAUFKST | WARPL | MPLA |  | |
| `WERKS` | VIAUFKST | MANDT | T001W |  | |
| `WERKS` | VIAUFKST | WERKS | T001W |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `addat`, `aedat`, `auart`, `aufnr`, `erdat`, `erfzeit`, `ernam`, `gewrk`, `ilart`, `ingpr`, `iphas`, `loekz`, `objnr`, `priok`, `qmnum`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `auart`, `erdat`, `ingpr`

## Join Paths
- `VIAUFKST.AUFNR` → `AUFK.AUFNR` — WO Tracking → Order
- `VIAUFKST.OBJNR` → `JEST.OBJNR` — WO Tracking → Status

## Programs Using This Table
- `z_bapi_get_cl_status.txt`
- `z_bapi_get_ft_status.txt`
- `z_bapi_get_mi_status.txt`
- `z_bapi_get_track_cl.txt`
- `z_bapi_get_track_mi.txt`
- `zdiscon.txt`
- `zisbi0013.txt`
- `ziscs0026.txt`
- `ziscs0026a.txt`
- `ziscs0039.txt`
- `ziscs0157.txt`
- `ziscs0176.txt`
- `ziscs0176_adj.txt`
- `ziscs0200.txt`
- `ziscs0209_f01.txt`
- `ziscs0287.txt`
- `ziscs0328.txt`
- `ziscsriaufk20.txt`
- `zisfi0030.txt`
- `zisfi0038.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_