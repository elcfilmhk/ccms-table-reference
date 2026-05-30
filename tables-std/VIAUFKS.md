# `VIAUFKS`

**Description:** Order (IS-U) — IS-U order master
**Category:** Standard SAP Table
**References:** 71 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/viaufks/) — validated 2026-05-30, schema v1.0
**Schema fields:** 203 fields | **Data types:** CHAR(120), CUKY(1), CURR(1), DATS(33), FLTP(1), INT4(2), NUMC(24), QUAN(8), TIMS(9), UNIT(4)

## Key Fields
`BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `PRIOK` | PRIOK | T356 | CHAR | 1 | 0 | Priority |
| `EQUNR` | EQUNR | EQUI | CHAR | 18 | 0 | Equipment Number |
| `BAUTL` | BAUTL | MARA | CHAR | 18 | 0 | Assembly |
| `ANLZU` | ANLZU | T357M | CHAR | 1 | 0 | Syst.Condition |
| `IWERK` | IWERK | T399I | CHAR | 4 | 0 | Maintenance Planning Plant |
| `INGPR` | INGRP | T024I | CHAR | 3 | 0 | Planner Group for Customer Service and Plant Maintenance |
| `APGRP` | VAGRP | T024A | CHAR | 3 | 0 | Responsible planner group/department |
| `GEWRK` | LGWID | CRID | NUMC | 8 | 0 | Object ID of the Work Center |
| `KUNUM` | KUNUM | KNA1 | CHAR | 10 | 0 | Customer Number |
| `ANING` | ANING | — | CHAR | 12 | 0 | Name of Person Reponsible for System |
| `GAUEH` | MAUEH | T006 | UNIT | 3 | 0 | Unit for Breakdown Duration |
| `GAUZT` | GAUZT | — | FLTP | 16 | 16 | Planned downtime in hours |
| `ANLBD` | ANLBD | — | DATS | 8 | 0 | Date until which the system is available |
| `ANLVD` | ANLVD | — | DATS | 8 | 0 | Date from which the system is available |
| `ANLBZ` | ANLBZ | — | TIMS | 6 | 0 | Time until which the system is available |
| `ANLVZ` | ANLVZ | — | TIMS | 6 | 0 | Time from Which System is Available |
| `WARPL` | WARPL | MPLA | CHAR | 12 | 0 | Maintenance Plan |
| `WAPOS` | WAPOS | — | CHAR | 16 | 0 | Maintenance item |
| `REVNR` | REVNI | T352R | CHAR | 8 | 0 | Revision for Plant Maintenance and Customer Service |
| `ARTPR` | ARTPR | T356A | CHAR | 2 | 0 | Priority Type |
| `ILOAN` | ILOAN | ILOA | CHAR | 12 | 0 | Location and account assignment for technical object |
| `ILOAI` | ILOAI | — | CHAR | 1 | 0 | ILOA Individual |
| `PM_OBJTY` | PM_OBJTY | — | CHAR | 2 | 0 | Object Type of CIM Resources for Work Center |
| `INSPK` | INSPK | — | CHAR | 12 | 0 | Name of Person Responsible for Technical Inspection |
| `DATAN` | DATAN | — | DATS | 8 | 0 | Date of Technical Inspection |
| `ABNUM` | ABNUM | — | INT4 | 10 | 0 | Maintenance Plan Call Number |
| `LAUFN` | LAUFN | AUFK | CHAR | 12 | 0 | Order number |
| `OBKNR` | OBJKNR | SER00 | INT4 | 10 | 0 | Object list number |
| `AUART` | AUFART | T003O | CHAR | 4 | 0 | Order Type |
| `AUTYP` | AUFTYP | — | NUMC | 2 | 0 | Order category |
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
| `KOSTL` | KOSTL | CSKS | CHAR | 10 | 0 | Cost Center |
| `SAKNR` | AUFSAKNR | SKB1 | CHAR | 10 | 0 | G/L account for basic settlement |
| `SETNM` | AUFSETNM | — | CHAR | 12 | 0 | Allocation set |
| `CYCLE` | ST_KOSTL | CSKS | CHAR | 10 | 0 | Cost center to which costs are actually posted |
| `SDATE` | SDATE | — | DATS | 8 | 0 | Start Date |
| `SEQNR` | AUFSEQNR | — | NUMC | 4 | 0 | Sequence number |
| `OBJNR` | J_OBJNR | ONR00 | CHAR | 22 | 0 | Object number |
| `PRCTR` | PRCTR | CEPC | CHAR | 10 | 0 | Profit Center |
| `VNAME` | JV_NAME | T8JV | CHAR | 6 | 0 | Joint Venture |
| `RECID` | JV_RECIND | T8JJ | CHAR | 2 | 0 | Recovery Indicator |
| `ETYPE` | JV_ETYPE | T8JG | CHAR | 3 | 0 | Equity type |
| `PSPEL` | PS_PSP_ELE | PRPS | NUMC | 8 | 0 | Work breakdown structure element (WBS element) |
| `AWSLS` | AWSLS | TKV01 | CHAR | 6 | 0 | Variance Key |
| `ABGSL` | ABGR_SCHL | TKKAA | CHAR | 6 | 0 | Results Analysis Key |
| `TPLNR` | TPLNR | IFLOT | CHAR | 30 | 0 | Functional Location |
| `ABCKZ` | ABCKZ | T370C | CHAR | 1 | 0 | ABC indicator for technical object |
| `EQFNR` | EQFNR | — | CHAR | 30 | 0 | Sort field |
| `SWERK` | SWERK | T001W | CHAR | 4 | 0 | Maintenance plant |
| `STORT_ILOA` | PMLOC | T499S | CHAR | 10 | 0 | Location of maintenance object |
| `MSGRP` | RAUMNR | — | CHAR | 8 | 0 | Room |
| `BEBER` | BEBER | T357 | CHAR | 3 | 0 | Plant section |
| `CR_OBJTY` | CR_OBJTY | — | CHAR | 2 | 0 | Object types of the CIM resource |
| `PPSID` | PPSID | CRID | NUMC | 8 | 0 | Object ID of PP work center |
| `GSBER_ILOA` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `KOKRS_ILOA` | KOKRS | TKA01 | CHAR | 4 | 0 | Controlling Area |
| `PROID` | PS_PSP_PNR | PRPS | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `BUKRS_ILOA` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `ANLNR` | ANLN1 | ANLH | CHAR | 12 | 0 | Main Asset Number |
| `ANLUN` | ANLN2 | ANLA | CHAR | 4 | 0 | Asset Subnumber |
| `DAUFN` | DAUFN | AUFK | CHAR | 12 | 0 | Standing order number |
| `AUFNR_ILOA` | ILOM_ORDST | AUFK | CHAR | 12 | 0 | Settlement order |
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
| `ADDAT` | ADDAT | — | DATS | 8 | 0 | PM Order: Reference Date |
| `ADUHR` | ADUHR | — | TIMS | 6 | 0 | Time of Reference Date |
| `IPHAS` | PM_PHASE | — | CHAR | 1 | 0 | Maintenance Processing Phase |
| `ILART` | ILA | T353I | CHAR | 3 | 0 | Maintenance activity type |
| `QMNUM` | QMNUM | QMEL | CHAR | 12 | 0 | Notification No |
| `FLG_AOB` | FLG_AOB | — | CHAR | 1 | 0 | Indicator: relationships |
| `FLG_ARBEI` | FLG_ARBEI | — | CHAR | 1 | 0 | Indicator: Default value work is relevant |
| `GLTPP` | CO_GLTPP | — | DATS | 8 | 0 | Finish date (forecast) |
| `GSTPP` | CO_GSTPP | — | DATS | 8 | 0 | Forecast start date |
| `GLTPS` | CO_GLTPS | — | DATS | 8 | 0 | Scheduled forecast finish |
| `GSTPS` | CO_GSTPS | — | DATS | 8 | 0 | Scheduled forecast start |
| `FTRPS` | CO_FTRPS | — | DATS | 8 | 0 | Scheduled release date (forecast) |
| `RDKZP` | REDKZP | — | CHAR | 1 | 0 | Reduction indicator for scheduling (forecast) |
| `TRKZP` | TERMKZP | — | CHAR | 1 | 0 | Scheduling type (forecast) |
| `VKORG` | VKORG | TVKO | CHAR | 4 | 0 | Sales Organization |
| `VTWEG` | VTWEG | TVKOV | CHAR | 2 | 0 | Distribution Channel |
| `SPART` | SPART | TVTA | CHAR | 2 | 0 | Division |
| `ADRNR_ILOA` | AD_ADDRNUM | ADRC | CHAR | 10 | 0 | Address number |
| `KDAUF` | KDAUF | VBUK | CHAR | 10 | 0 | Sales Order Number |
| `KDPOS` | KDPOS | — | NUMC | 6 | 0 | Item Number in Sales Order |
| `GLUZP` | CO_GLUZP | — | TIMS | 6 | 0 | Basic finish (time) |
| `GSUZP` | CO_GSUZP | — | TIMS | 6 | 0 | Basic start time |
| `GLUZS` | CO_GLUZS | — | TIMS | 6 | 0 | Scheduled finish time |
| `GSUZS` | CO_GSUZS | — | TIMS | 6 | 0 | Scheduled Start (Time) |
| `MAUFNR` | MAUFNR | — | CHAR | 12 | 0 | Number of superior order |
| `LEAD_AUFNR` | CO_LAUFNR | AUFK | CHAR | 12 | 0 | Leading order in current processing |
| `GEUZI` | CO_GEUZI | — | TIMS | 6 | 0 | Confirmed order finish (time) |
| `GSUZI` | CO_GSUZI | — | TIMS | 6 | 0 | Actual start time |
| `OWNER` | ILOM_OWNER | — | CHAR | 1 | 0 | Object reference indicator |
| `PLKNZ` | AUF_PLKNZ | — | CHAR | 1 | 0 | Maintenance order planning indicator |
| `USER4` | AUFUSER4 | — | CURR | 11 | 2 | Estimated total costs of order |
| `RSORD` | RSORD | — | CHAR | 1 | 0 | Refurbishment order indicator (PM) |
| `BEMOT` | BEMOT | TBMOT | CHAR | 2 | 0 | Accounting Indicator |
| `SERMAT` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `SERIALNR` | GERNR | — | CHAR | 18 | 0 | Serial Number |
| `DEVICEID` | DEVICEID | — | CHAR | 40 | 0 | Additional Device Data |
| `ADRNRA` | AD_ADDRNUM | — | CHAR | 10 | 0 | Address number |
| `UII` | UII_CHAR72 | — | CHAR | 72 | 0 | Unique Item Identifier |
| `NETZKONT` | NETZKONT | — | CHAR | 1 | 0 | Indicator for the account assignment of a network(hdr/act.) |
| `/CUM/CMNUM` | /CUM/CMNUM | — | CHAR | 12 | 0 | CU: Construction Measure Number |
| `/CUM/DESNUM` | /CUM/DESNUM | — | CHAR | 12 | 0 | CU: Design Number |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABCKZ` | VIAUFKS | MANDT | T370C |  | |
| `ABCKZ` | VIAUFKS | ABCKZ | T370C |  | |
| `ABGSL` | VIAUFKS | MANDT | TKKAA |  | |
| `ABGSL` | VIAUFKS | ABGSL | TKKAA |  | |
| `ABKRS` | VIAUFKS | MANDT | TKO08 |  | |
| `ABKRS` | VIAUFKS | KOKRS | TKO08 |  | |
| `ABKRS` | VIAUFKS | ABKRS | TKO08 |  | |
| `ADRNR_ILOA` | VIAUFKS | MANDT | ADRC |  | |
| `ADRNR_ILOA` | VIAUFKS | ADRNR_ILOA | ADRC |  | |
| `ADRNR_ILOA` | * |  | ADRC |  | |
| `ADRNR_ILOA` | * |  | ADRC |  | |
| `ANLNR` | VIAUFKS | MANDT | ANLH |  | |
| `ANLNR` | VIAUFKS | BUKRS_ILOA | ANLH |  | |
| `ANLNR` | VIAUFKS | ANLNR | ANLH |  | |
| `ANLUN` | VIAUFKS | ANLUN | ANLA |  | |
| `ANLUN` | VIAUFKS | MANDT | ANLA |  | |
| `ANLUN` | VIAUFKS | BUKRS_ILOA | ANLA |  | |
| `ANLUN` | VIAUFKS | ANLNR | ANLA |  | |
| `ANLZU` | VIAUFKS | ANLZU | T357M |  | |
| `ANLZU` | SYST | MANDT | T357M |  | |
| `APGRP` | VIAUFKS | APGRP | T024A |  | |
| `APGRP` | VIAUFKS | MANDT | T024A |  | |
| `APGRP` | VIAUFKS | IWERK | T024A |  | |
| `ARTPR` | VIAUFKS | MANDT | T356A |  | |
| `ARTPR` | VIAUFKS | ARTPR | T356A |  | |
| `AUART` | VIAUFKS | AUART | T003O |  | |
| `AUART` | VIAUFKS | MANDT | T003O |  | |
| `AUFNR` | VIAUFKS | AUFNR | AUFK |  | |
| `AUFNR` | VIAUFKS | MANDT | AUFK |  | |
| `AUFNR_ILOA` | VIAUFKS | MANDT | AUFK |  | |
| `AUFNR_ILOA` | VIAUFKS | AUFNR_ILOA | AUFK |  | |
| `AWSLS` | TKV01 | AWOBA | TKV01 |  | |
| `AWSLS` | VIAUFKS | AWSLS | TKV01 |  | |
| `AWSLS` | VIAUFKS | MANDT | TKV01 |  | |
| `BAUTL` | VIAUFKS | MANDT | MARA |  | |
| `BAUTL` | VIAUFKS | BAUTL | MARA |  | |
| `BEBER` | VIAUFKS | MANDT | T357 |  | |
| `BEBER` | VIAUFKS | SWERK | T357 |  | |
| `BEBER` | VIAUFKS | BEBER | T357 |  | |
| `BEMOT` | VIAUFKS | MANDT | TBMOT |  | |
| `BEMOT` | VIAUFKS | BEMOT | TBMOT |  | |
| `BUKRS` | VIAUFKS | BUKRS | T001 |  | |
| `BUKRS` | VIAUFKS | MANDT | T001 |  | |
| `BUKRS_ILOA` | VIAUFKS | MANDT | T001 |  | |
| `BUKRS_ILOA` | VIAUFKS | BUKRS_ILOA | T001 |  | |
| `CYCLE` | VIAUFKS | MANDT | CSKS |  | |
| `CYCLE` | VIAUFKS | KOKRS | CSKS |  | |
| `CYCLE` | VIAUFKS | CYCLE | CSKS |  | |
| `CYCLE` | * |  | CSKS |  | |
| `DAUFN` | VIAUFKS | MANDT | AUFK |  | |
| `DAUFN` | VIAUFKS | DAUFN | AUFK |  | |
| `DISPO` | AUFK | WERKS | T024D |  | |
| `DISPO` | VIAUFKS | DISPO | T024D |  | |
| `DISPO` | VIAUFKS | MANDT | T024D |  | |
| `EQUNR` | VIAUFKS | MANDT | EQUI |  | |
| `EQUNR` | VIAUFKS | EQUNR | EQUI |  | |
| `ESTNR` | VIAUFKS | ESTNR | TKO03 |  | |
| `ESTNR` | VIAUFKS | MANDT | TKO03 |  | |
| `ESTNR` | VIAUFKS | AUART | TKO03 |  | |
| `ETYPE` | * |  | T8JG |  | |
| `ETYPE` | SYST | MANDT | T8JG |  | |
| `ETYPE` | GJV_OBJDAT | BUKRS | T8JG |  | |
| `ETYPE` | VIAUFKS | VNAME | T8JG |  | |
| `ETYPE` | VIAUFKS | ETYPE | T8JG |  | |
| `FEVOR` | VIAUFKS | MANDT | T024F |  | |
| `FEVOR` | AUFK | WERKS | T024F |  | |
| `FEVOR` | VIAUFKS | FEVOR | T024F |  | |
| `FHORI` | VIAUFKS | MANDT | T436A |  | |
| `FHORI` | AUFK | WERKS | T436A |  | |
| `FHORI` | VIAUFKS | FHORI | T436A |  | |
| `GAUEH` | VIAUFKS | MANDT | T006 |  | |
| `GAUEH` | VIAUFKS | GAUEH | T006 |  | |
| `GEWRK` | VIAUFKS | MANDT | CRID |  | |
| `GEWRK` | VIAUFKS | PM_OBJTY | CRID |  | |
| `GEWRK` | VIAUFKS | GEWRK | CRID |  | |
| `GMEIN` | VIAUFKS | MANDT | T006 |  | |
| `GMEIN` | VIAUFKS | GMEIN | T006 |  | |
| `GSBER` | VIAUFKS | MANDT | TGSB |  | |
| `GSBER` | VIAUFKS | GSBER | TGSB |  | |
| `GSBER_ILOA` | VIAUFKS | MANDT | TGSB |  | |
| `GSBER_ILOA` | VIAUFKS | GSBER_ILOA | TGSB |  | |
| `ILART` | VIAUFKS | MANDT | T353I |  | |
| `ILART` | VIAUFKS | ILART | T353I |  | |
| `ILOAN` | VIAUFKS | MANDT | ILOA |  | |
| `ILOAN` | VIAUFKS | ILOAN | ILOA |  | |
| `INGPR` | VIAUFKS | IWERK | T024I |  | |
| `INGPR` | VIAUFKS | INGPR | T024I |  | |
| `INGPR` | VIAUFKS | MANDT | T024I |  | |
| `IWERK` | VIAUFKS | MANDT | T399I |  | |
| `IWERK` | VIAUFKS | IWERK | T399I |  | |
| `KALSM` | VIAUFKS | KAPPL | T683 |  | |
| `KALSM` | VIAUFKS | KALSM | T683 |  | |
| `KALSM` | VIAUFKS | MANDT | T683 |  | |
| `KALSM` | VIAUFKS | KVEWE | T683 |  | |
| `KAPPL` | VIAUFKS | KAPPL | T681A |  | |
| `KDAUF` | VIAUFKS | MANDT | VBUK |  | |
| `KDAUF` | VIAUFKS | KDAUF | VBUK |  | |
| `KOKRS` | VIAUFKS | KOKRS | TKA01 |  | |
| `KOKRS` | VIAUFKS | MANDT | TKA01 |  | |
| `KOKRS_ILOA` | VIAUFKS | MANDT | TKA01 |  | |
| `KOKRS_ILOA` | VIAUFKS | KOKRS_ILOA | TKA01 |  | |
| `KOSTL` | VIAUFKS | MANDT | CSKS |  | |
| `KOSTL` | VIAUFKS | KOKRS_ILOA | CSKS |  | |
| `KOSTL` | VIAUFKS | KOSTL | CSKS |  | |
| `KOSTL` | SYST | DATUM | CSKS |  | |
| `KOSTV` | VIAUFKS | KOKRS | CSKS |  | |
| `KOSTV` | VIAUFKS | KOSTV | CSKS |  | |
| `KOSTV` | * |  | CSKS |  | |
| `KOSTV` | VIAUFKS | MANDT | CSKS |  | |
| `KSTAR` | * |  | CSKB |  | |
| `KSTAR` | VIAUFKS | MANDT | CSKB |  | |
| `KSTAR` | VIAUFKS | KOKRS | CSKB |  | |
| `KSTAR` | VIAUFKS | KSTAR | CSKB |  | |
| `KUNUM` | VIAUFKS | MANDT | KNA1 |  | |
| `KUNUM` | VIAUFKS | KUNUM | KNA1 |  | |
| `KVEWE` | VIAUFKS | KVEWE | T681V |  | |
| `LAUFN` | VIAUFKS | LAUFN | AUFK |  | |
| `LAUFN` | VIAUFKS | MANDT | AUFK |  | |
| `LEAD_AUFNR` | VIAUFKS | MANDT | AUFK |  | |
| `LEAD_AUFNR` | VIAUFKS | LEAD_AUFNR | AUFK |  | |
| `MANDT` | VIAUFKS | MANDT | T000 |  | |
| `OBJNR` | VIAUFKS | OBJNR | ONR00 |  | |
| `OBJNR` | VIAUFKS | MANDT | ONR00 |  | |
| `OBKNR` | VIAUFKS | OBKNR | SER00 |  | |
| `OBKNR` | SYST | MANDT | SER00 |  | |
| `PAENR` | VIAUFKS | MANDT | AENR |  | |
| `PAENR` | VIAUFKS | PAENR | AENR |  | |
| `PLGRP` | VIAUFKS | MANDT | T024A |  | |
| `PLGRP` | AUFK | WERKS | T024A |  | |
| `PLGRP` | VIAUFKS | PLGRP | T024A |  | |
| `PLNAW` | VIAUFKS | PLNAW | TCA09 |  | |
| `PLNAW` | VIAUFKS | MANDT | TCA09 |  | |
| `PLNBEZ` | VIAUFKS | MANDT | MARA |  | |
| `PLNBEZ` | VIAUFKS | PLNBEZ | MARA |  | |
| `PLNME` | VIAUFKS | PLNME | T006 |  | |
| `PLNME` | VIAUFKS | MANDT | T006 |  | |
| `PPSID` | VIAUFKS | MANDT | CRID |  | |
| `PPSID` | VIAUFKS | CR_OBJTY | CRID |  | |
| `PPSID` | VIAUFKS | PPSID | CRID |  | |
| `PRCTR` | * |  | CEPC |  | |
| `PRCTR` | VIAUFKS | KOKRS | CEPC |  | |
| `PRCTR` | VIAUFKS | MANDT | CEPC |  | |
| `PRCTR` | VIAUFKS | PRCTR | CEPC |  | |
| `PRIOK` | VIAUFKS | MANDT | T356 |  | |
| `PRIOK` | VIAUFKS | ARTPR | T356 |  | |
| `PRIOK` | VIAUFKS | PRIOK | T356 |  | |
| `PROFID` | VIAUFKS | MANDT | TCN41 |  | |
| `PROFID` | VIAUFKS | PLNAW | TCN41 |  | |
| `PROFID` | VIAUFKS | PROFID | TCN41 |  | |
| `PROID` | VIAUFKS | MANDT | PRPS |  | |
| `PROID` | VIAUFKS | PROID | PRPS |  | |
| `PRONR` | VIAUFKS | MANDT | PROJ |  | |
| `PRONR` | VIAUFKS | PRONR | PROJ |  | |
| `PSPEL` | VIAUFKS | MANDT | PRPS |  | |
| `PSPEL` | VIAUFKS | PSPEL | PRPS |  | |
| `PVERW` | VIAUFKS | MANDT | T411 |  | |
| `PVERW` | VIAUFKS | PVERW | T411 |  | |
| `QMNUM` | VIAUFKS | MANDT | QMEL |  | |
| `QMNUM` | VIAUFKS | QMNUM | QMEL |  | |
| `RECID` | SYST | MANDT | T8JJ |  | |
| `RECID` | GJV_OBJDAT | BUKRS | T8JJ |  | |
| `RECID` | VIAUFKS | RECID | T8JJ |  | |
| `REVNR` | VIAUFKS | MANDT | T352R |  | |
| `REVNR` | VIAUFKS | IWERK | T352R |  | |
| `REVNR` | VIAUFKS | REVNR | T352R |  | |
| `SAENR` | VIAUFKS | MANDT | AENR |  | |
| `SAENR` | VIAUFKS | SAENR | AENR |  | |
| `SAKNR` | VIAUFKS | MANDT | SKB1 |  | |
| `SAKNR` | VIAUFKS | BUKRS | SKB1 |  | |
| `SAKNR` | VIAUFKS | SAKNR | SKB1 |  | |
| `SBMEH` | VIAUFKS | MANDT | T006 |  | |
| `SBMEH` | VIAUFKS | SBMEH | T006 |  | |
| `SERMAT` | VIAUFKS | SERMAT | MARA |  | |
| `SERMAT` | VIAUFKS | MANDT | MARA |  | |
| `SOWRK` | VIAUFKS | MANDT | T001W |  | |
| `SOWRK` | VIAUFKS | SOWRK | T001W |  | |
| `SPART` | VIAUFKS | MANDT | TVTA |  | |
| `SPART` | VIAUFKS | VKORG | TVTA |  | |
| `SPART` | VIAUFKS | VTWEG | TVTA |  | |
| `SPART` | VIAUFKS | SPART | TVTA |  | |
| `STLAN` | VIAUFKS | STLAN | T416 |  | |
| `STLAN` | VIAUFKS | MANDT | T416 |  | |
| `STLBEZ` | VIAUFKS | MANDT | MARA |  | |
| `STLBEZ` | VIAUFKS | STLBEZ | MARA |  | |
| `STLST` | VIAUFKS | MANDT | T415S |  | |
| `STLST` | VIAUFKS | STLST | T415S |  | |
| `STORT` | VIAUFKS | MANDT | T499S |  | |
| `STORT` | VIAUFKS | SOWRK | T499S |  | |
| `STORT` | VIAUFKS | STORT | T499S |  | |
| `STORT_ILOA` | VIAUFKS | STORT_ILOA | T499S |  | |
| `STORT_ILOA` | VIAUFKS | MANDT | T499S |  | |
| `STORT_ILOA` | VIAUFKS | SWERK | T499S |  | |
| `SWERK` | VIAUFKS | MANDT | T001W |  | |
| `SWERK` | VIAUFKS | SWERK | T001W |  | |
| `TERKZ` | VIAUFKS | MANDT | T482 |  | |
| `TERKZ` | VIAUFKS | TERKZ | T482 |  | |
| `TPLNR` | VIAUFKS | TPLNR | IFLOT |  | |
| `TPLNR` | VIAUFKS | MANDT | IFLOT |  | |
| `VKORG` | VIAUFKS | MANDT | TVKO |  | |
| `VKORG` | VIAUFKS | VKORG | TVKO |  | |
| `VNAME` | GJV_OBJDAT | BUKRS | T8JV |  | |
| `VNAME` | VIAUFKS | VNAME | T8JV |  | |
| `VNAME` | SYST | MANDT | T8JV |  | |
| `VOGRP` | VIAUFKS | VOGRP | TKAVG |  | |
| `VOGRP` | * |  | TKAVG |  | |
| `VOGRP` | VIAUFKS | MANDT | TKAVG |  | |
| `VOGRP` | VIAUFKS | OBJID | TKAVG |  | |
| `VTWEG` | VIAUFKS | VKORG | TVKOV |  | |
| `VTWEG` | VIAUFKS | VTWEG | TVKOV |  | |
| `VTWEG` | VIAUFKS | MANDT | TVKOV |  | |
| `WAERS` | VIAUFKS | MANDT | TCURC |  | |
| `WAERS` | VIAUFKS | WAERS | TCURC |  | |
| `WARPL` | VIAUFKS | MANDT | MPLA |  | |
| `WARPL` | VIAUFKS | WARPL | MPLA |  | |
| `WERKS` | VIAUFKS | MANDT | T001W |  | |
| `WERKS` | VIAUFKS | WERKS | T001W |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AUART`, `AUFNR`, `ERDAT`, `GSTRP`, `IDAT2`, `ILART`, `ILOAN`, `IPHAS`, `TPLNR`, `auart`, `aufnr`, `idat2`, `ilart`, `iloan`, `iphas`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `AUART`, `AUFNR`, `aufnr`, `idat2`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_premise_validation_f.txt`
- `z_bapi_validate_premise.txt`
- `zdiscon.txt`
- `zisbi0173.txt`
- `zisbi0198.txt`
- `zisbw0043.txt`
- `ziscrm0318forms.txt`
- `ziscs0038.txt`
- `ziscs0153.txt`
- `ziscs0273.txt`
- `ziscs0283.txt`
- `ziscs0283a.txt`
- `ziscs0341.txt`
- `zisdm0409.txt`
- `zisdm_so_approval_f01.txt`
- `zisdmreaufk20f10.txt`
- `zisfi0124.txt`
- `zrdm_dr_rep.txt`
- `zrdm_mr_rep.txt`
- `zrpm_mwfm_so_create.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_