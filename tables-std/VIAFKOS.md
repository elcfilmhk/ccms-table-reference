# `VIAFKOS`

**Description:** Service Order — service order header
**Category:** Standard SAP Table
**References:** 153 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/viafkos/) — validated 2026-05-30, schema v1.0
**Schema fields:** 196 fields | **Data types:** CHAR(116), CUKY(1), DATS(33), FLTP(1), INT4(2), NUMC(24), QUAN(8), TIMS(7), UNIT(4)

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
| `KOSTL_ILOA` | KOSTL | CSKS | CHAR | 10 | 0 | Cost Center |
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
| `ADRNR` | AD_ADDRNUM | ADRC | CHAR | 10 | 0 | Address number |
| `KDAUF` | KDAUF | VBUK | CHAR | 10 | 0 | Sales Order Number |
| `KDPOS` | KDPOS | — | NUMC | 6 | 0 | Item Number in Sales Order |
| `GLUZP` | CO_GLUZP | — | TIMS | 6 | 0 | Basic finish (time) |
| `GSUZP` | CO_GSUZP | — | TIMS | 6 | 0 | Basic start time |
| `GLUZS` | CO_GLUZS | — | TIMS | 6 | 0 | Scheduled finish time |
| `GSUZS` | CO_GSUZS | — | TIMS | 6 | 0 | Scheduled Start (Time) |
| `MAUFNR` | MAUFNR | — | CHAR | 12 | 0 | Number of superior order |
| `LEAD_AUFNR` | CO_LAUFNR | AUFK | CHAR | 12 | 0 | Leading order in current processing |
| `OWNER` | ILOM_OWNER | — | CHAR | 1 | 0 | Object reference indicator |
| `SERMAT` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `SERIALNR` | GERNR | — | CHAR | 18 | 0 | Serial Number |
| `DEVICEID` | DEVICEID | — | CHAR | 40 | 0 | Additional Device Data |
| `UII` | UII_CHAR72 | — | CHAR | 72 | 0 | Unique Item Identifier |
| `/CUM/CMNUM` | /CUM/CMNUM | — | CHAR | 12 | 0 | CU: Construction Measure Number |
| `/CUM/DESNUM` | /CUM/DESNUM | — | CHAR | 12 | 0 | CU: Design Number |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABCKZ` | VIAFKOS | MANDT | T370C |  | |
| `ABCKZ` | VIAFKOS | ABCKZ | T370C |  | |
| `ABGSL` | VIAFKOS | MANDT | TKKAA |  | |
| `ABGSL` | VIAFKOS | ABGSL | TKKAA |  | |
| `ABKRS` | VIAFKOS | ABKRS | TKO08 |  | |
| `ABKRS` | VIAFKOS | MANDT | TKO08 |  | |
| `ABKRS` | VIAFKOS | KOKRS | TKO08 |  | |
| `ADRNR` | VIAFKOS | MANDT | ADRC |  | |
| `ADRNR` | VIAFKOS | ADRNR | ADRC |  | |
| `ADRNR` | * |  | ADRC |  | |
| `ADRNR` | * |  | ADRC |  | |
| `ANLNR` | VIAFKOS | MANDT | ANLH |  | |
| `ANLNR` | VIAFKOS | BUKRS_ILOA | ANLH |  | |
| `ANLNR` | VIAFKOS | ANLNR | ANLH |  | |
| `ANLUN` | VIAFKOS | ANLUN | ANLA |  | |
| `ANLUN` | VIAFKOS | MANDT | ANLA |  | |
| `ANLUN` | VIAFKOS | BUKRS_ILOA | ANLA |  | |
| `ANLUN` | VIAFKOS | ANLNR | ANLA |  | |
| `ANLZU` | SYST | MANDT | T357M |  | |
| `ANLZU` | VIAFKOS | ANLZU | T357M |  | |
| `APGRP` | VIAFKOS | MANDT | T024A |  | |
| `APGRP` | VIAFKOS | IWERK | T024A |  | |
| `APGRP` | VIAFKOS | APGRP | T024A |  | |
| `ARTPR` | VIAFKOS | MANDT | T356A |  | |
| `ARTPR` | VIAFKOS | ARTPR | T356A |  | |
| `AUART` | VIAFKOS | MANDT | T003O |  | |
| `AUART` | VIAFKOS | AUART | T003O |  | |
| `AUFNR` | VIAFKOS | AUFNR | AUFK |  | |
| `AUFNR` | VIAFKOS | MANDT | AUFK |  | |
| `AUFNR_ILOA` | VIAFKOS | MANDT | AUFK |  | |
| `AUFNR_ILOA` | VIAFKOS | AUFNR_ILOA | AUFK |  | |
| `AWSLS` | VIAFKOS | MANDT | TKV01 |  | |
| `AWSLS` | TKV01 | AWOBA | TKV01 |  | |
| `AWSLS` | VIAFKOS | AWSLS | TKV01 |  | |
| `BAUTL` | VIAFKOS | BAUTL | MARA |  | |
| `BAUTL` | VIAFKOS | MANDT | MARA |  | |
| `BEBER` | VIAFKOS | MANDT | T357 |  | |
| `BEBER` | VIAFKOS | SWERK | T357 |  | |
| `BEBER` | VIAFKOS | BEBER | T357 |  | |
| `BUKRS` | VIAFKOS | MANDT | T001 |  | |
| `BUKRS` | VIAFKOS | BUKRS | T001 |  | |
| `BUKRS_ILOA` | VIAFKOS | MANDT | T001 |  | |
| `BUKRS_ILOA` | VIAFKOS | BUKRS_ILOA | T001 |  | |
| `CYCLE` | VIAFKOS | MANDT | CSKS |  | |
| `CYCLE` | VIAFKOS | KOKRS | CSKS |  | |
| `CYCLE` | VIAFKOS | CYCLE | CSKS |  | |
| `CYCLE` | * |  | CSKS |  | |
| `DAUFN` | VIAFKOS | MANDT | AUFK |  | |
| `DAUFN` | VIAFKOS | DAUFN | AUFK |  | |
| `DISPO` | VIAFKOS | MANDT | T024D |  | |
| `DISPO` | AUFK | WERKS | T024D |  | |
| `DISPO` | VIAFKOS | DISPO | T024D |  | |
| `EQUNR` | VIAFKOS | MANDT | EQUI |  | |
| `EQUNR` | VIAFKOS | EQUNR | EQUI |  | |
| `ESTNR` | VIAFKOS | MANDT | TKO03 |  | |
| `ESTNR` | VIAFKOS | AUART | TKO03 |  | |
| `ESTNR` | VIAFKOS | ESTNR | TKO03 |  | |
| `ETYPE` | SYST | MANDT | T8JG |  | |
| `ETYPE` | GJV_OBJDAT | BUKRS | T8JG |  | |
| `ETYPE` | VIAFKOS | VNAME | T8JG |  | |
| `ETYPE` | VIAFKOS | ETYPE | T8JG |  | |
| `ETYPE` | * |  | T8JG |  | |
| `FEVOR` | VIAFKOS | MANDT | T024F |  | |
| `FEVOR` | AUFK | WERKS | T024F |  | |
| `FEVOR` | VIAFKOS | FEVOR | T024F |  | |
| `FHORI` | AUFK | WERKS | T436A |  | |
| `FHORI` | VIAFKOS | FHORI | T436A |  | |
| `FHORI` | VIAFKOS | MANDT | T436A |  | |
| `GAUEH` | VIAFKOS | GAUEH | T006 |  | |
| `GAUEH` | VIAFKOS | MANDT | T006 |  | |
| `GEWRK` | VIAFKOS | MANDT | CRID |  | |
| `GEWRK` | VIAFKOS | PM_OBJTY | CRID |  | |
| `GEWRK` | VIAFKOS | GEWRK | CRID |  | |
| `GMEIN` | VIAFKOS | MANDT | T006 |  | |
| `GMEIN` | VIAFKOS | GMEIN | T006 |  | |
| `GSBER` | VIAFKOS | MANDT | TGSB |  | |
| `GSBER` | VIAFKOS | GSBER | TGSB |  | |
| `GSBER_ILOA` | VIAFKOS | GSBER_ILOA | TGSB |  | |
| `GSBER_ILOA` | VIAFKOS | MANDT | TGSB |  | |
| `ILART` | VIAFKOS | ILART | T353I |  | |
| `ILART` | VIAFKOS | MANDT | T353I |  | |
| `ILOAN` | VIAFKOS | MANDT | ILOA |  | |
| `ILOAN` | VIAFKOS | ILOAN | ILOA |  | |
| `INGPR` | VIAFKOS | INGPR | T024I |  | |
| `INGPR` | VIAFKOS | MANDT | T024I |  | |
| `INGPR` | VIAFKOS | IWERK | T024I |  | |
| `IWERK` | VIAFKOS | MANDT | T399I |  | |
| `IWERK` | VIAFKOS | IWERK | T399I |  | |
| `KALSM` | VIAFKOS | MANDT | T683 |  | |
| `KALSM` | VIAFKOS | KVEWE | T683 |  | |
| `KALSM` | VIAFKOS | KAPPL | T683 |  | |
| `KALSM` | VIAFKOS | KALSM | T683 |  | |
| `KAPPL` | VIAFKOS | KAPPL | T681A |  | |
| `KDAUF` | VIAFKOS | MANDT | VBUK |  | |
| `KDAUF` | VIAFKOS | KDAUF | VBUK |  | |
| `KOKRS` | VIAFKOS | MANDT | TKA01 |  | |
| `KOKRS` | VIAFKOS | KOKRS | TKA01 |  | |
| `KOKRS_ILOA` | VIAFKOS | MANDT | TKA01 |  | |
| `KOKRS_ILOA` | VIAFKOS | KOKRS_ILOA | TKA01 |  | |
| `KOSTL` | VIAFKOS | MANDT | CSKS |  | |
| `KOSTL` | VIAFKOS | KOKRS_ILOA | CSKS |  | |
| `KOSTL` | VIAFKOS | KOSTL | CSKS |  | |
| `KOSTL` | SYST | DATUM | CSKS |  | |
| `KOSTL_ILOA` | VIAFKOS | KOKRS_ILOA | CSKS |  | |
| `KOSTL_ILOA` | VIAFKOS | KOSTL_ILOA | CSKS |  | |
| `KOSTL_ILOA` | SYST | DATUM | CSKS |  | |
| `KOSTL_ILOA` | VIAFKOS | MANDT | CSKS |  | |
| `KOSTV` | * |  | CSKS |  | |
| `KOSTV` | VIAFKOS | MANDT | CSKS |  | |
| `KOSTV` | VIAFKOS | KOKRS | CSKS |  | |
| `KOSTV` | VIAFKOS | KOSTV | CSKS |  | |
| `KSTAR` | * |  | CSKB |  | |
| `KSTAR` | VIAFKOS | MANDT | CSKB |  | |
| `KSTAR` | VIAFKOS | KOKRS | CSKB |  | |
| `KSTAR` | VIAFKOS | KSTAR | CSKB |  | |
| `KUNUM` | VIAFKOS | MANDT | KNA1 |  | |
| `KUNUM` | VIAFKOS | KUNUM | KNA1 |  | |
| `KVEWE` | VIAFKOS | KVEWE | T681V |  | |
| `LAUFN` | VIAFKOS | LAUFN | AUFK |  | |
| `LAUFN` | VIAFKOS | MANDT | AUFK |  | |
| `LEAD_AUFNR` | VIAFKOS | MANDT | AUFK |  | |
| `LEAD_AUFNR` | VIAFKOS | LEAD_AUFNR | AUFK |  | |
| `MANDT` | VIAFKOS | MANDT | T000 |  | |
| `OBJNR` | VIAFKOS | MANDT | ONR00 |  | |
| `OBJNR` | VIAFKOS | OBJNR | ONR00 |  | |
| `OBKNR` | SYST | MANDT | SER00 |  | |
| `OBKNR` | VIAFKOS | OBKNR | SER00 |  | |
| `PAENR` | VIAFKOS | MANDT | AENR |  | |
| `PAENR` | VIAFKOS | PAENR | AENR |  | |
| `PLGRP` | VIAFKOS | MANDT | T024A |  | |
| `PLGRP` | AUFK | WERKS | T024A |  | |
| `PLGRP` | VIAFKOS | PLGRP | T024A |  | |
| `PLNAW` | VIAFKOS | MANDT | TCA09 |  | |
| `PLNAW` | VIAFKOS | PLNAW | TCA09 |  | |
| `PLNBEZ` | VIAFKOS | MANDT | MARA |  | |
| `PLNBEZ` | VIAFKOS | PLNBEZ | MARA |  | |
| `PLNME` | VIAFKOS | MANDT | T006 |  | |
| `PLNME` | VIAFKOS | PLNME | T006 |  | |
| `PPSID` | VIAFKOS | MANDT | CRID |  | |
| `PPSID` | VIAFKOS | CR_OBJTY | CRID |  | |
| `PPSID` | VIAFKOS | PPSID | CRID |  | |
| `PRCTR` | * |  | CEPC |  | |
| `PRCTR` | VIAFKOS | KOKRS | CEPC |  | |
| `PRCTR` | VIAFKOS | MANDT | CEPC |  | |
| `PRCTR` | VIAFKOS | PRCTR | CEPC |  | |
| `PRIOK` | VIAFKOS | MANDT | T356 |  | |
| `PRIOK` | VIAFKOS | ARTPR | T356 |  | |
| `PRIOK` | VIAFKOS | PRIOK | T356 |  | |
| `PROFID` | VIAFKOS | MANDT | TCN41 |  | |
| `PROFID` | VIAFKOS | PLNAW | TCN41 |  | |
| `PROFID` | VIAFKOS | PROFID | TCN41 |  | |
| `PROID` | VIAFKOS | MANDT | PRPS |  | |
| `PROID` | VIAFKOS | PROID | PRPS |  | |
| `PRONR` | VIAFKOS | MANDT | PROJ |  | |
| `PRONR` | VIAFKOS | PRONR | PROJ |  | |
| `PSPEL` | VIAFKOS | PSPEL | PRPS |  | |
| `PSPEL` | VIAFKOS | MANDT | PRPS |  | |
| `PVERW` | VIAFKOS | PVERW | T411 |  | |
| `PVERW` | VIAFKOS | MANDT | T411 |  | |
| `QMNUM` | VIAFKOS | MANDT | QMEL |  | |
| `QMNUM` | VIAFKOS | QMNUM | QMEL |  | |
| `RECID` | SYST | MANDT | T8JJ |  | |
| `RECID` | GJV_OBJDAT | BUKRS | T8JJ |  | |
| `RECID` | VIAFKOS | RECID | T8JJ |  | |
| `REVNR` | VIAFKOS | MANDT | T352R |  | |
| `REVNR` | VIAFKOS | IWERK | T352R |  | |
| `REVNR` | VIAFKOS | REVNR | T352R |  | |
| `SAENR` | VIAFKOS | MANDT | AENR |  | |
| `SAENR` | VIAFKOS | SAENR | AENR |  | |
| `SAKNR` | VIAFKOS | BUKRS | SKB1 |  | |
| `SAKNR` | VIAFKOS | SAKNR | SKB1 |  | |
| `SAKNR` | VIAFKOS | MANDT | SKB1 |  | |
| `SBMEH` | VIAFKOS | MANDT | T006 |  | |
| `SBMEH` | VIAFKOS | SBMEH | T006 |  | |
| `SERMAT` | VIAFKOS | MANDT | MARA |  | |
| `SERMAT` | VIAFKOS | SERMAT | MARA |  | |
| `SOWRK` | VIAFKOS | MANDT | T001W |  | |
| `SOWRK` | VIAFKOS | SOWRK | T001W |  | |
| `SPART` | VIAFKOS | VTWEG | TVTA |  | |
| `SPART` | VIAFKOS | SPART | TVTA |  | |
| `SPART` | VIAFKOS | MANDT | TVTA |  | |
| `SPART` | VIAFKOS | VKORG | TVTA |  | |
| `STLAN` | VIAFKOS | MANDT | T416 |  | |
| `STLAN` | VIAFKOS | STLAN | T416 |  | |
| `STLBEZ` | VIAFKOS | STLBEZ | MARA |  | |
| `STLBEZ` | VIAFKOS | MANDT | MARA |  | |
| `STLST` | VIAFKOS | MANDT | T415S |  | |
| `STLST` | VIAFKOS | STLST | T415S |  | |
| `STORT` | VIAFKOS | SOWRK | T499S |  | |
| `STORT` | VIAFKOS | STORT | T499S |  | |
| `STORT` | VIAFKOS | MANDT | T499S |  | |
| `STORT_ILOA` | VIAFKOS | MANDT | T499S |  | |
| `STORT_ILOA` | VIAFKOS | SWERK | T499S |  | |
| `STORT_ILOA` | VIAFKOS | STORT_ILOA | T499S |  | |
| `SWERK` | VIAFKOS | SWERK | T001W |  | |
| `SWERK` | VIAFKOS | MANDT | T001W |  | |
| `TERKZ` | VIAFKOS | MANDT | T482 |  | |
| `TERKZ` | VIAFKOS | TERKZ | T482 |  | |
| `TPLNR` | VIAFKOS | MANDT | IFLOT |  | |
| `TPLNR` | VIAFKOS | TPLNR | IFLOT |  | |
| `VKORG` | VIAFKOS | VKORG | TVKO |  | |
| `VKORG` | VIAFKOS | MANDT | TVKO |  | |
| `VNAME` | VIAFKOS | VNAME | T8JV |  | |
| `VNAME` | SYST | MANDT | T8JV |  | |
| `VNAME` | GJV_OBJDAT | BUKRS | T8JV |  | |
| `VOGRP` | VIAFKOS | MANDT | TKAVG |  | |
| `VOGRP` | VIAFKOS | OBJID | TKAVG |  | |
| `VOGRP` | VIAFKOS | VOGRP | TKAVG |  | |
| `VOGRP` | * |  | TKAVG |  | |
| `VTWEG` | VIAFKOS | MANDT | TVKOV |  | |
| `VTWEG` | VIAFKOS | VKORG | TVKOV |  | |
| `VTWEG` | VIAFKOS | VTWEG | TVKOV |  | |
| `WAERS` | VIAFKOS | MANDT | TCURC |  | |
| `WAERS` | VIAFKOS | WAERS | TCURC |  | |
| `WARPL` | VIAFKOS | MANDT | MPLA |  | |
| `WARPL` | VIAFKOS | WARPL | MPLA |  | |
| `WERKS` | VIAFKOS | MANDT | T001W |  | |
| `WERKS` | VIAFKOS | WERKS | T001W |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AUART`, `AUFNR`, `IPHAS`, `KTEXT`, `adrnr`, `aedat`, `auart`, `aufnr`, `aufpl`, `erdat`, `gewrk`, `ilart`, `ingpr`, `iwerk`, `kunum`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `IPHAS`, `aufnr`, `ilart`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_dunning_create_so.txt`
- `ziscs0031.txt`
- `ziscs0149.txt`
- `ziscs0161.txt`
- `ziscs0182.txt`
- `ziscs0254.txt`
- `ziscs0364.txt`
- `ziscsriaufk20.txt`
- `zisdm0067.txt`
- `zisdm0142.txt`
- `zisdm0152.txt`
- `zisdm0169.txt`
- `zisdm0172.txt`
- `zisdm0215.txt`
- `zisdm0315.txt`
- `zisdm0420.txt`
- `zisfi0005_dun.txt`
- `zisfi0009.txt`
- `zisfi0082.txt`
- `zisuorder.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_