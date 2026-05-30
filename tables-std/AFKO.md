# `AFKO`

**Description:** Order Header (CO) — cost order header
**Category:** Standard SAP Table
**References:** 12 SELECT statements across 11 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/afko/) — validated 2026-05-30, schema v1.0
**Schema fields:** 163 fields | **Data types:** CHAR(67), DATS(25), DEC(7), INT4(1), NUMC(32), QUAN(14), TIMS(12), UNIT(5)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
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
| `OIHANTYP` | OIH_HANTYP | — | CHAR | 2 | 0 | Excise Duty Handling Type |
| `MILL_RATIO` | MILL_RATIO | — | INT4 | 10 | 0 | Factor for Quantity-Based Settlement |
| `BMEINS` | MEINS | — | UNIT | 3 | 0 | Base Unit of Measure |
| `BMENGE` | BASMN | — | QUAN | 13 | 3 | Base quantity |
| `MILL_OC_ZUSKZ` | MILL_OC_ZUSKZ | — | CHAR | 1 | 0 | Combination Indicator |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `AENNR` | AFKO | MANDT | AENR |  | |
| `AENNR` | AFKO | AENNR | AENR |  | |
| `AUFNR` | AFKO | MANDT | AUFK |  | |
| `AUFNR` | AFKO | AUFNR | AUFK |  | |
| `CFB_LZEIH` | SYST | MANDT | T006 |  | |
| `CFB_LZEIH` | AFKO | CFB_LZEIH | T006 |  | |
| `CHSCH` | &#039;PP&#039; |  | T683 |  | |
| `CHSCH` | AFKO | CHSCH | T683 |  | |
| `CHSCH` | AFKO | MANDT | T683 |  | |
| `CHSCH` | &#039;H&#039; |  | T683 |  | |
| `CSPLIT` | AFKO | MANDT | MAKV |  | |
| `CSPLIT` | AFKO | STLBEZ | MAKV |  | |
| `CSPLIT` | AUFK | WERKS | MAKV |  | |
| `CSPLIT` | AFKO | CSPLIT | MAKV |  | |
| `DISPO` | AFKO | MANDT | T024D |  | |
| `DISPO` | AUFK | WERKS | T024D |  | |
| `DISPO` | AFKO | DISPO | T024D |  | |
| `FEVOR` | AFKO | MANDT | T024F |  | |
| `FEVOR` | AUFK | WERKS | T024F |  | |
| `FEVOR` | AFKO | FEVOR | T024F |  | |
| `FHORI` | AFKO | FHORI | T436A |  | |
| `FHORI` | AFKO | MANDT | T436A |  | |
| `FHORI` | AUFK | WERKS | T436A |  | |
| `GMEIN` | AFKO | GMEIN | T006 |  | |
| `GMEIN` | AFKO | MANDT | T006 |  | |
| `LEAD_AUFNR` | AFKO | MANDT | AUFK |  | |
| `LEAD_AUFNR` | AFKO | LEAD_AUFNR | AUFK |  | |
| `MANDT` | AFKO | MANDT | T000 |  | |
| `NTZUE` | AFKO | NTZUE | AUFK |  | |
| `NTZUE` | AFKO | MANDT | AUFK |  | |
| `PAENR` | AFKO | MANDT | AENR |  | |
| `PAENR` | AFKO | PAENR | AENR |  | |
| `PLGRP` | AUFK | WERKS | T024A |  | |
| `PLGRP` | AFKO | PLGRP | T024A |  | |
| `PLGRP` | AFKO | MANDT | T024A |  | |
| `PLNAW` | AFKO | MANDT | TCA09 |  | |
| `PLNAW` | AFKO | PLNAW | TCA09 |  | |
| `PLNBEZ` | AFKO | MANDT | MARA |  | |
| `PLNBEZ` | AFKO | PLNBEZ | MARA |  | |
| `PLNME` | AFKO | MANDT | T006 |  | |
| `PLNME` | AFKO | PLNME | T006 |  | |
| `PROFID` | AFKO | PLNAW | TCN41 |  | |
| `PROFID` | AFKO | PROFID | TCN41 |  | |
| `PROFID` | AFKO | MANDT | TCN41 |  | |
| `PRONR` | AFKO | PRONR | PROJ |  | |
| `PRONR` | AFKO | MANDT | PROJ |  | |
| `PVERW` | AFKO | MANDT | T411 |  | |
| `PVERW` | AFKO | PVERW | T411 |  | |
| `RSHID` | AFKO | MANDT | CRID |  | |
| `RSHID` | AFKO | RSHTY | CRID |  | |
| `RSHID` | AFKO | RSHID | CRID |  | |
| `RSNID` | AFKO | RSNTY | CRID |  | |
| `RSNID` | AFKO | RSNID | CRID |  | |
| `RSNID` | AFKO | MANDT | CRID |  | |
| `SAENR` | AFKO | MANDT | AENR |  | |
| `SAENR` | AFKO | SAENR | AENR |  | |
| `SBMEH` | AFKO | MANDT | T006 |  | |
| `SBMEH` | AFKO | SBMEH | T006 |  | |
| `SFCPF` | AFKO | MANDT | TCO43 |  | |
| `SFCPF` | AUFK | WERKS | TCO43 |  | |
| `SFCPF` | AFKO | SFCPF | TCO43 |  | |
| `STLAN` | AFKO | MANDT | T416 |  | |
| `STLAN` | AFKO | STLAN | T416 |  | |
| `STLBEZ` | AFKO | MANDT | MARA |  | |
| `STLBEZ` | AFKO | STLBEZ | MARA |  | |
| `STLST` | AFKO | MANDT | T415S |  | |
| `STLST` | AFKO | STLST | T415S |  | |
| `TERKZ` | AFKO | MANDT | T482 |  | |
| `TERKZ` | AFKO | TERKZ | T482 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_ft_status.txt`
- `z_bapi_iia_dates_getlist.txt`
- `z_bapi_iia_dates_getlist_d.txt`
- `z_bapi_iia_get_detail.txt`
- `z_bapi_isusmorder_exch.txt`
- `ziscrm0318forms.txt`
- `ziscs0009.txt`
- `ziscs0154.txt`
- `ziscs0355.txt`
- `ziscseec_comm_frmwrk_trigger.txt`
- `zisdm0022f01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_