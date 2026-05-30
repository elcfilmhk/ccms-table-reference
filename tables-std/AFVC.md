# `AFVC`

**Description:** Operation — order operation/activity
**Category:** Standard SAP Table
**References:** 2 SELECT statements across 2 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/afvc/) — validated 2026-05-30, schema v1.0
**Schema fields:** 181 fields | **Data types:** CHAR(133), CUKY(2), CURR(3), DEC(10), INT1(3), INT4(1), LANG(1), NUMC(27), RAW(1)

## Key Fields
`LIFNR` | `BUKRS` | `PERNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `PLNFL` | PLNFOLGE | — | CHAR | 6 | 0 | Sequence |
| `PLNKN` | PLNKN | — | NUMC | 8 | 0 | Number of the task list node |
| `PLNAL` | PLNAL | — | CHAR | 2 | 0 | Group Counter |
| `PLNTY` | PLNTY | TCA01 | CHAR | 1 | 0 | Task List Type |
| `VINTV` | VINTV | — | DEC | 3 | 0 | Increment between referenced operations |
| `PLNNR` | PLNNR | — | CHAR | 8 | 0 | Key for Task List Group |
| `ZAEHL` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `VORNR` | VORNR | — | CHAR | 4 | 0 | Operation/Activity Number |
| `STEUS` | STEUS | T430 | CHAR | 4 | 0 | Control key |
| `ARBID` | CR_OBJID | CRID | NUMC | 8 | 0 | Object ID of the resource |
| `PDEST` | CR_PDEST | TSP03 | CHAR | 4 | 0 | Printer for shop papers |
| `WERKS` | WERKS_D | T001W | CHAR | 4 | 0 | Plant |
| `KTSCH` | KTSCH | T435 | CHAR | 7 | 0 | Standard text key |
| `LTXA1` | LTXA1 | — | CHAR | 40 | 0 | Operation short text |
| `LTXA2` | LTXA2 | — | CHAR | 40 | 0 | Second line of the description |
| `TXTSP` | SPRAS | T002 | LANG | 1 | 0 | Language Key |
| `VPLTY` | VPLNTY | TCA01 | CHAR | 1 | 0 | Type of the referenced task list |
| `VPLNR` | VPLNNR | — | CHAR | 8 | 0 | Group of the referenced task list |
| `VPLAL` | VPLNAL | — | CHAR | 2 | 0 | Group counter of the referenced task list |
| `VPLFL` | VPLBFL | — | CHAR | 6 | 0 | Referenced sequence in routing |
| `VGWTS` | VORGSCHL | TC21 | CHAR | 4 | 0 | Standard value key |
| `LAR01` | LSTAR | CSLA | CHAR | 6 | 0 | Activity Type |
| `LAR02` | LSTAR | CSLA | CHAR | 6 | 0 | Activity Type |
| `LAR03` | LSTAR | CSLA | CHAR | 6 | 0 | Activity Type |
| `LAR04` | LSTAR | CSLA | CHAR | 6 | 0 | Activity Type |
| `LAR05` | LSTAR | CSLA | CHAR | 6 | 0 | Activity Type |
| `LAR06` | LSTAR | CSLA | CHAR | 6 | 0 | Activity Type |
| `ZERMA` | DZERMA | T429 | CHAR | 5 | 0 | Type of standard value calculation |
| `ZGDAT` | DZGDAT | — | CHAR | 4 | 0 | Date when the standard value was calculated |
| `ZCODE` | DZCODE | — | CHAR | 6 | 0 | Reference number for standard value code |
| `ZULNR` | DZULNR | — | CHAR | 5 | 0 | Basis for standard value calculation |
| `LOANZ` | LOHNANZ | — | DEC | 3 | 0 | Number of Time Tickets |
| `LOART` | LOHNART | — | CHAR | 4 | 0 | Wage Type |
| `RSANZ` | CR_RS_ANZ | — | NUMC | 3 | 0 | Number of confirmation slips |
| `QUALF` | QUALF | T423 | CHAR | 2 | 0 | Suitability |
| `ANZMA` | ANZMS | — | DEC | 5 | 2 | Number of employees |
| `RFGRP` | RUEFAGRP | T426 | CHAR | 10 | 0 | Setup group category |
| `RFSCH` | RUEFASCHLU | T425 | CHAR | 10 | 0 | Setup group key |
| `RASCH` | RUEARSCHLU | T428 | CHAR | 2 | 0 | Setup Type Key |
| `AUFAK` | AUSCHUFAK | — | DEC | 5 | 3 | Scrap factor |
| `LOGRP` | LOHNGRP | T421 | CHAR | 3 | 0 | Wage group |
| `UEMUS` | UEMUSKZ | — | CHAR | 1 | 0 | Required overlapping |
| `UEKAN` | UEKANKZ | — | CHAR | 1 | 0 | Optional overlapping |
| `FLIES` | FLIESSKZ | — | CHAR | 1 | 0 | Indicator: continuous flow production |
| `SPMUS` | SPLITTUNG | — | CHAR | 1 | 0 | Required splitting |
| `SPLIM` | SPLITTANZ | — | DEC | 3 | 0 | Maximum number of splits |
| `ABLIPKZ` | ABLIPKZ | — | CHAR | 1 | 0 | Indicator: simultaneous teardown and wait |
| `RSTRA` | RSTRA | T499Q | CHAR | 2 | 0 | Reduction strategy per operation/activity |
| `SUMNR` | SUMKNTNR | — | NUMC | 8 | 0 | Node number of the superior operation |
| `SORTL` | SORTI | — | CHAR | 10 | 0 | Sort Term for Non-Stock Info Records |
| `LIFNR` | LIFNR | LFA1 | CHAR | 10 | 0 | Account Number of Vendor or Creditor |
| `PREIS` | PREIS | — | CURR | 11 | 2 | Price |
| `PEINH` | PEINH | — | DEC | 5 | 0 | Price Unit |
| `SAKTO` | KSTAR | CSKA | CHAR | 10 | 0 | Cost Element |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `INFNR` | INFNR | EINA | CHAR | 10 | 0 | Number of Purchasing Info Record |
| `ESOKZ` | ESOKZ | — | CHAR | 1 | 0 | Purchasing info record category |
| `EKORG` | EKORG | T024E | CHAR | 4 | 0 | Purchasing Organization |
| `EKGRP` | VG_EKGRP | T024 | CHAR | 3 | 0 | Purchasing group for external processing |
| `KZLGF` | KZLGF | — | CHAR | 1 | 0 | Indicator: fixed lot external processing |
| `KZWRTF` | KZWRTF | — | CHAR | 1 | 0 | Indicator: Fixed price for external processing |
| `MATKL` | MATKL | T023 | CHAR | 9 | 0 | Material Group |
| `DDEHN` | DAUDEHN | — | CHAR | 1 | 0 | Indicator: flexible duration |
| `ANZZL` | ANZKAP | — | INT1 | 3 | 0 | Number of capacities required |
| `PRZNT` | APROZENT | — | INT1 | 3 | 0 | Work percentage |
| `MLSTN` | MILESTONE | T433 | CHAR | 5 | 0 | Usage |
| `PPRIO` | PRIORITAET | — | CHAR | 2 | 0 | Priority |
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `ANFKO` | ANFKO | CSKS | CHAR | 10 | 0 | Requesting cost center |
| `ANFKOKRS` | ANFKOKRS | TKA01 | CHAR | 4 | 0 | Controlling area of the requesting cost center |
| `INDET` | INDET | — | CHAR | 1 | 0 | Key for calculation |
| `LARNT` | LSTAR | CSLA | CHAR | 6 | 0 | Activity Type |
| `PRKST` | PRKST | — | CURR | 11 | 2 | Costs in the activity |
| `APLFL` | PLNFOLGE | — | CHAR | 6 | 0 | Sequence |
| `RUECK` | CO_RUECK | — | NUMC | 10 | 0 | Completion confirmation number for the operation |
| `RMZHL` | CO_RMZHL | — | NUMC | 8 | 0 | Confirmation counter |
| `PROJN` | PS_PSP_ELE | PRPS | NUMC | 8 | 0 | Work breakdown structure element (WBS element) |
| `OBJNR` | J_OBJNR | ONR00 | CHAR | 22 | 0 | Object number |
| `SPANZ` | SPLITTERM | — | DEC | 3 | 0 | Actual number of splits |
| `BEDID` | BEDID | — | NUMC | 12 | 0 | ID of the capacity requirements record |
| `BEDZL` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `BANFN` | CO_BANFN | — | CHAR | 10 | 0 | Purchase requisition number |
| `BNFPO` | CO_BNFPO | EBAN | NUMC | 5 | 0 | Item number of the purchase requisition in the order |
| `LEK01` | CO_LEIKZ | — | CHAR | 1 | 0 | Indicator: No remaining activity expected |
| `LEK02` | CO_LEIKZ | — | CHAR | 1 | 0 | Indicator: No remaining activity expected |
| `LEK03` | CO_LEIKZ | — | CHAR | 1 | 0 | Indicator: No remaining activity expected |
| `LEK04` | CO_LEIKZ | — | CHAR | 1 | 0 | Indicator: No remaining activity expected |
| `LEK05` | CO_LEIKZ | — | CHAR | 1 | 0 | Indicator: No remaining activity expected |
| `LEK06` | CO_LEIKZ | — | CHAR | 1 | 0 | Indicator: No remaining activity expected |
| `SELKZ` | CO_SELKZ | TCK08 | CHAR | 1 | 0 | Selection indicator for costing line items |
| `KALID` | WFCID | TFACD | CHAR | 2 | 0 | Factory Calendar |
| `FRSP` | FRSP | — | CHAR | 1 | 0 | Earliest possible activity / Latest possible activity |
| `STDKN` | STDKN | — | NUMC | 8 | 0 | Node of operation within reference operation set |
| `ANLZU` | ANLZU | T357M | CHAR | 1 | 0 | Syst.Condition |
| `ISTRU` | ISTRU | MARA | CHAR | 18 | 0 | Assembly |
| `ISTTY` | STLTY | — | CHAR | 1 | 0 | BOM category |
| `ISTNR` | STNUM | — | CHAR | 8 | 0 | Bill of material |
| `ISTKN` | STLKN | — | NUMC | 8 | 0 | BOM item node number |
| `ISTPO` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `IUPOZ` | UPOSZ | — | CHAR | 4 | 0 | Subitem Number |
| `EBORT` | EBORT | — | CHAR | 20 | 0 | Installation Point for Subitem |
| `VERTL` | CR_VERTN | TC29 | CHAR | 8 | 0 | Distr.cap.reqmts (plant maint.,process order, network) |
| `LEKNW` | LEKNW | — | CHAR | 1 | 0 | Indicator: No Remaining Work Expected |
| `NPRIO` | NW_PRIO | TCN07 | CHAR | 1 | 0 | Priority |
| `PVZKN` | CO_APLZL | — | NUMC | 8 | 0 | General counter for order |
| `PHFLG` | PHFLG | — | CHAR | 1 | 0 | Indicator: Phase |
| `PHSEQ` | PHSEQ | TC52 | CHAR | 2 | 0 | Control Recipe Destination |
| `KNOBJ` | KNOBJ | — | NUMC | 18 | 0 | Number of Object with Assigned Dependencies |
| `ERFSICHT` | QERFSICHT | — | CHAR | 2 | 0 | Recording View |
| `QPPKTABS` | QPPKTABS | — | CHAR | 1 | 0 | Flow Variants for Inspection Point Completion |
| `OTYPE` | OTYPE | T778O | CHAR | 2 | 0 | Object Type |
| `OBJEKTID` | OBJEKTID | — | NUMC | 8 | 0 | Object ID |
| `QLKAPAR` | QL_KAPART | TC26 | CHAR | 3 | 0 | Capacity category |
| `RSTUF` | RSTUF | — | NUMC | 1 | 0 | Reduction level which reduces operation lead time |
| `NPTXTKY` | TXTKY | — | CHAR | 12 | 0 | Internal text number (12-character) |
| `SUBSYS` | QEIFSUBSYS | — | CHAR | 6 | 0 | Subsystem Identifier for QM Subsystem Interface |
| `PSPNR` | PS_SPS_ELE | — | NUMC | 8 | 0 | Standard WBS element |
| `PACKNO` | PACKNO | — | NUMC | 10 | 0 | Package number |
| `TXJCD` | TXJCD | TTXJ | CHAR | 15 | 0 | Tax Jurisdiction |
| `SCOPE` | SCOPE_CV | — | CHAR | 2 | 0 | Object Class |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `PRCTR` | PRCTR | CEPC | CHAR | 10 | 0 | Profit Center |
| `NO_DISP` | NO_DISP_PLUS | — | CHAR | 1 | 0 | Effective for Materials Planning |
| `QKZPRZEIT` | QKZPRZEIT | — | CHAR | 1 | 0 | Interval = Time (Time-Related) |
| `QKZZTMG1` | QKZZTMG1 | — | CHAR | 1 | 0 | Quantity Confirmation for Each Partial Lot |
| `QKZPRMENG` | QKZPRMENG | — | CHAR | 1 | 0 | Creation Cycle = Quantity  (Quantity-Reference) |
| `QKZPRFREI` | QKZPRFREI | — | CHAR | 1 | 0 | Interval Without Reference to Time or Quantity |
| `KZFEAT` | QKZFEAT | — | CHAR | 1 | 0 | Indicator Is Not Used Currently |
| `QKZTLSBEST` | QKZTLSBEST | — | CHAR | 1 | 0 | Operation with Stock-Related Partial Lot Assignment |
| `AENNR` | AENNR | AENR | CHAR | 12 | 0 | Change Number |
| `CUOBJ_ARB` | CUOBJ | — | NUMC | 18 | 0 | Configuration (internal object number) |
| `EVGEW` | EV_WEIGHTD | — | DEC | 8 | 0 | Aggregation weight for POC (PS progress) |
| `ARBII` | CR_OBJID_I | CRID | NUMC | 8 | 0 | Actual operating resources object identification |
| `WERKI` | WERKS_I | T001W | CHAR | 4 | 0 | Actual plant |
| `CY_SEQNRV` | CY_SEQNRV | — | NUMC | 14 | 0 | Sequence number operation |
| `KAPT_PUFFR` | KAPT_PUFFR | — | INT4 | 10 | 0 | Operation floats after finite scheduling (in seconds) |
| `EBELN` | EBELN | EKKO | CHAR | 10 | 0 | Purchasing Document Number |
| `EBELP` | EBELP | EKPO | NUMC | 5 | 0 | Item Number of Purchasing Document |
| `WEMPF` | WEMPF | — | CHAR | 12 | 0 | Goods Recipient/Ship-To Party |
| `ABLAD` | ABLAD | — | CHAR | 25 | 0 | Unloading Point |
| `CLASF` | CLASF | — | CHAR | 1 | 0 | Ind.: Take Activity Into Account for Project Summarization |
| `FRUNV` | FRUNV | — | CHAR | 1 | 0 | Indicator: External procurement data incomplete |
| `ZSCHL` | AUFZSCHL | — | CHAR | 6 | 0 | Overhead key |
| `KALSM` | AUFKALSM | — | CHAR | 6 | 0 | Costing Sheet |
| `SCHED_END` | SCEND_ACT | — | CHAR | 1 | 0 | Ind.: Purchase requisition at activity finish date |
| `NETZKONT` | NETZKONT | — | CHAR | 1 | 0 | Indicator for the account assignment of a network(hdr/act.) |
| `OWAER` | OWAERS | TCURC | CUKY | 5 | 0 | Object currency for network activity |
| `AFNAM` | AFNAM | — | CHAR | 12 | 0 | Name of Requisitioner/Requester |
| `BEDNR` | BEDNR | — | CHAR | 10 | 0 | Requirement Tracking Number |
| `KZFIX` | CN_KZFIX | — | CHAR | 1 | 0 | Indicator: Purchasing info record data are fixed |
| `PERNR` | CO_PERNR | — | NUMC | 8 | 0 | Personnel number |
| `FRDLB` | CO_FRDLB | — | CHAR | 1 | 0 | Indicator: Externally processed op. with subcontracting |
| `QPART` | QPART | TQ30 | CHAR | 8 | 0 | Inspection Type |
| `LOEKZ` | AUFLOEKZ | — | CHAR | 1 | 0 | Deletion flag |
| `WKURS` | WKURS | — | DEC | 9 | 5 | Exchange Rate |
| `PROD_ACT` | PROD_ACT | — | CHAR | 1 | 0 | Indicator: Activity is a production activity |
| `FPLNR` | FPLNR | — | CHAR | 10 | 0 | Billing plan number / invoicing plan number |
| `OBJTYPE` | OCM_OBJ_TYPE | — | CHAR | 1 | 0 | Change indicator |
| `CH_PROC` | OCM_CH_PROC | — | CHAR | 1 | 0 | Process that has lead to the change of an object |
| `KLVAR` | CK_KLVAR | — | CHAR | 4 | 0 | Costing Variant |
| `KALNR` | CK_KALNR | — | NUMC | 12 | 0 | Cost Estimate Number for Cost Est. w/o Qty Structure |
| `FORDN` | SFORDN | — | CHAR | 10 | 0 | Framework Order |
| `FORDP` | FORDP | — | NUMC | 5 | 0 | Item of framework order |
| `MAT_PRKST` | MAT_PRKST | — | CURR | 11 | 2 | Material planning in networks: primary costs |
| `PRZ01` | CO_PRZNR | — | CHAR | 12 | 0 | Business Process |
| `RFPNT` | CN_RFPNT | TCNRFP | CHAR | 20 | 0 | Reference point for BOM transfer |
| `FUNC_AREA` | FKBER | TFKB | CHAR | 16 | 0 | Functional Area |
| `TECHS` | TECHS | — | CHAR | 12 | 0 | Parameter Variant/Standard Variant |
| `ADPSP` | ADDCOMPARE_CORE | — | CHAR | 40 | 0 | Reference Element PM/PS |
| `RFIPPNT` | CN_RPIP | TCNRPIP | CHAR | 20 | 0 | Reference Point for Relationship Between iPPE and PS |
| `MES_OPERID` | CO_MES_INT_OPERID | — | CHAR | 48 | 0 | Key of an Operation from an ME System |
| `MES_STEPID` | CO_MES_INT_STEPID | — | CHAR | 6 | 0 | Key of a Step in a Routing (SAP ME) |
| `/CUM/CUGUID` | SYSUUID_X | /CUM/AFCU | RAW | 16 | 0 | UUID in X form (binary) |
| `/ISDFPS/OBJNR` | J_OBJNR | — | CHAR | 22 | 0 | Object number |
| `AFVC_STATUS` | ACTCMB_DELE | ACTCMB_TAB | INT1 | 3 | 0 | Status Combination |
| `MILL_OC_AUFNR_MO` | MILL_OC_AUFNR_MO | — | CHAR | 12 | 0 | Number of Combined Order |
| `OIO_HOLD` | OIO_HOLD | — | CHAR | 1 | 0 | Indicator: Hold Delivery Onshore |
| `WTY_IND` | WTYSC_WTY_INDICATOR | — | CHAR | 1 | 0 | Warranty indicator |
| `TPLNR` | TPLNR | — | CHAR | 30 | 0 | Functional Location |
| `EQUNR` | EQUNR | — | CHAR | 18 | 0 | Equipment Number |
| `CPD_UPDAT` | /CPD/PFP_TSTMP | — | DEC | 15 | 0 | Time Stamp |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `/CUM/CUGUID` | SYST | MANDT | /CUM/AFCU |  | |
| `/CUM/CUGUID` | AFVC | /CUM/CUGUID | /CUM/AFCU |  | |
| `AENNR` | AFVKI | MANDT | AENR |  | |
| `AENNR` | AFVC | AENNR | AENR |  | |
| `AFVC_STATUS` | SYST | MANDT | ACTCMB_TAB |  | |
| `AFVC_STATUS` | AFVC | AFVC_STATUS | ACTCMB_TAB |  | |
| `ANFKO` | CSKS | DATBI | CSKS |  | |
| `ANFKO` | AFVKI | MANDT | CSKS |  | |
| `ANFKO` | AFVC | ANFKOKRS | CSKS |  | |
| `ANFKO` | AFVC | ANFKO | CSKS |  | |
| `ANFKOKRS` | AFVKI | MANDT | TKA01 |  | |
| `ANFKOKRS` | AFVC | ANFKOKRS | TKA01 |  | |
| `ANLZU` | CAUFVD | MANDT | T357M |  | |
| `ANLZU` | AFVC | ANLZU | T357M |  | |
| `ARBID` | CRID | OBJTY | CRID |  | |
| `ARBID` | AFVC | ARBID | CRID |  | |
| `ARBID` | AFVKI | MANDT | CRID |  | |
| `ARBII` | AFVKI | MANDT | CRID |  | |
| `ARBII` | CRID | OBJTY | CRID |  | |
| `ARBII` | AFVC | ARBII | CRID |  | |
| `BNFPO` | AFVKI | MANDT | EBAN |  | |
| `BNFPO` | AFVC | BANFN | EBAN |  | |
| `BNFPO` | AFVC | BNFPO | EBAN |  | |
| `BUKRS` | AFVKI | MANDT | T001 |  | |
| `BUKRS` | AFVC | BUKRS | T001 |  | |
| `EBELN` | AFVGD | MANDT | EKKO |  | |
| `EBELN` | AFVC | EBELN | EKKO |  | |
| `EBELP` | AFVC | EBELN | EKPO |  | |
| `EBELP` | AFVC | EBELP | EKPO |  | |
| `EBELP` | AFVGD | MANDT | EKPO |  | |
| `EKGRP` | AFVC | EKGRP | T024 |  | |
| `EKGRP` | AFVKI | MANDT | T024 |  | |
| `EKORG` | AFVKI | MANDT | T024E |  | |
| `EKORG` | AFVC | EKORG | T024E |  | |
| `FUNC_AREA` | SYST | MANDT | TFKB |  | |
| `FUNC_AREA` | AFVC | FUNC_AREA | TFKB |  | |
| `GSBER` | AFVKI | MANDT | TGSB |  | |
| `GSBER` | AFVC | GSBER | TGSB |  | |
| `INFNR` | AFVKI | MANDT | EINA |  | |
| `INFNR` | AFVC | INFNR | EINA |  | |
| `ISTRU` | AFVC | ISTRU | MARA |  | |
| `ISTRU` | AFVGK | MANDT | MARA |  | |
| `KALID` | AFVC | KALID | TFACD |  | |
| `KTSCH` | AFVKI | MANDT | T435 |  | |
| `KTSCH` | AFVC | KTSCH | T435 |  | |
| `LAR01` | AFVKI | MANDT | CSLA |  | |
| `LAR01` | AFVC | ANFKOKRS | CSLA |  | |
| `LAR01` | AFVC | LAR01 | CSLA |  | |
| `LAR01` | CSLA | DATBI | CSLA |  | |
| `LAR02` | AFVKI | MANDT | CSLA |  | |
| `LAR02` | AFVC | ANFKOKRS | CSLA |  | |
| `LAR02` | AFVC | LAR02 | CSLA |  | |
| `LAR02` | CSLA | DATBI | CSLA |  | |
| `LAR03` | AFVC | ANFKOKRS | CSLA |  | |
| `LAR03` | AFVC | LAR03 | CSLA |  | |
| `LAR03` | CSLA | DATBI | CSLA |  | |
| `LAR03` | AFVKI | MANDT | CSLA |  | |
| `LAR04` | CSLA | DATBI | CSLA |  | |
| `LAR04` | AFVKI | MANDT | CSLA |  | |
| `LAR04` | AFVC | ANFKOKRS | CSLA |  | |
| `LAR04` | AFVC | LAR04 | CSLA |  | |
| `LAR05` | AFVKI | MANDT | CSLA |  | |
| `LAR05` | AFVC | ANFKOKRS | CSLA |  | |
| `LAR05` | AFVC | LAR05 | CSLA |  | |
| `LAR05` | CSLA | DATBI | CSLA |  | |
| `LAR06` | AFVKI | MANDT | CSLA |  | |
| `LAR06` | AFVC | ANFKOKRS | CSLA |  | |
| `LAR06` | AFVC | LAR06 | CSLA |  | |
| `LAR06` | CSLA | DATBI | CSLA |  | |
| `LARNT` | AFVC | ANFKOKRS | CSLA |  | |
| `LARNT` | AFVC | LARNT | CSLA |  | |
| `LARNT` | CSLA | DATBI | CSLA |  | |
| `LARNT` | AFVGK | MANDT | CSLA |  | |
| `LIFNR` | AFVKI | MANDT | LFA1 |  | |
| `LIFNR` | AFVC | LIFNR | LFA1 |  | |
| `LOGRP` | AFVC | WERKS | T421 |  | |
| `LOGRP` | AFVC | LOGRP | T421 |  | |
| `LOGRP` | AFVKI | MANDT | T421 |  | |
| `MANDT` | AFVC | MANDT | T000 |  | |
| `MATKL` | AFVKI | MANDT | T023 |  | |
| `MATKL` | AFVC | MATKL | T023 |  | |
| `MLSTN` | AFVKI | MANDT | T433 |  | |
| `MLSTN` | AFVC | MLSTN | T433 |  | |
| `NPRIO` | SYST | MANDT | TCN07 |  | |
| `NPRIO` | AFVC | NPRIO | TCN07 |  | |
| `OBJNR` | AFVKI | MANDT | ONR00 |  | |
| `OBJNR` | AFVC | OBJNR | ONR00 |  | |
| `OTYPE` | AFVKI | MANDT | T778O |  | |
| `OTYPE` | AFVC | OTYPE | T778O |  | |
| `OWAER` | SYST | MANDT | TCURC |  | |
| `OWAER` | AFVC | OWAER | TCURC |  | |
| `PDEST` | AFVC | PDEST | TSP03 |  | |
| `PHSEQ` | AFVC | WERKS | TC52 |  | |
| `PHSEQ` | AFVC | PHSEQ | TC52 |  | |
| `PHSEQ` | MANDT | AFVC | TC52 |  | |
| `PLNTY` | AFVKI | MANDT | TCA01 |  | |
| `PLNTY` | AFVC | PLNTY | TCA01 |  | |
| `PRCTR` | AFVKI | MANDT | CEPC |  | |
| `PRCTR` | AFVC | PRCTR | CEPC |  | |
| `PRCTR` | * |  | CEPC |  | |
| `PRCTR` | * |  | CEPC |  | |
| `PROJN` | AFVKI | MANDT | PRPS |  | |
| `PROJN` | AFVC | PROJN | PRPS |  | |
| `QLKAPAR` | AFVKI | MANDT | TC26 |  | |
| `QLKAPAR` | AFVC | QLKAPAR | TC26 |  | |
| `QPART` | AFVC | MANDT | TQ30 |  | |
| `QPART` | AFVC | QPART | TQ30 |  | |
| `QUALF` | AFVKI | MANDT | T423 |  | |
| `QUALF` | AFVC | WERKS | T423 |  | |
| `QUALF` | AFVC | QUALF | T423 |  | |
| `RASCH` | AFVKI | MANDT | T428 |  | |
| `RASCH` | AFVC | WERKS | T428 |  | |
| `RASCH` | AFVC | RASCH | T428 |  | |
| `RFGRP` | AFVC | WERKS | T426 |  | |
| `RFGRP` | AFVC | RFGRP | T426 |  | |
| `RFGRP` | AFVKI | MANDT | T426 |  | |
| `RFIPPNT` | SYST | MANDT | TCNRPIP |  | |
| `RFIPPNT` | AFVC | RFIPPNT | TCNRPIP |  | |
| `RFPNT` | AFVC | RFPNT | TCNRFP |  | |
| `RFPNT` | AFVC | MANDT | TCNRFP |  | |
| `RFSCH` | AFVKI | MANDT | T425 |  | |
| `RFSCH` | AFVC | WERKS | T425 |  | |
| `RFSCH` | AFVC | RFGRP | T425 |  | |
| `RFSCH` | AFVC | RFSCH | T425 |  | |
| `RSTRA` | AFVC | WERKS | T499Q |  | |
| `RSTRA` | AFVC | RSTRA | T499Q |  | |
| `RSTRA` | AFVKI | MANDT | T499Q |  | |
| `SAKTO` | AFVKI | MANDT | CSKA |  | |
| `SAKTO` | CSKA | KTOPL | CSKA |  | |
| `SAKTO` | AFVC | SAKTO | CSKA |  | |
| `SELKZ` | AFVKI | MANDT | TCK08 |  | |
| `SELKZ` | AFVC | SELKZ | TCK08 |  | |
| `STEUS` | AFVKI | MANDT | T430 |  | |
| `STEUS` | CAUFVD | PLNAW | T430 |  | |
| `STEUS` | AFVC | STEUS | T430 |  | |
| `TXJCD` | AFVKI | MANDT | TTXJ |  | |
| `TXJCD` | CAUFVD | KALSM | TTXJ |  | |
| `TXJCD` | AFVC | TXJCD | TTXJ |  | |
| `TXTSP` | AFVC | TXTSP | T002 |  | |
| `VERTL` | AFVGK | MANDT | TC29 |  | |
| `VERTL` | AFVC | VERTL | TC29 |  | |
| `VGWTS` | AFVKI | MANDT | TC21 |  | |
| `VGWTS` | AFVC | VGWTS | TC21 |  | |
| `VPLTY` | AFVC | VPLTY | TCA01 |  | |
| `VPLTY` | AFVKI | MANDT | TCA01 |  | |
| `WAERS` | AFVKI | MANDT | TCURC |  | |
| `WAERS` | AFVC | WAERS | TCURC |  | |
| `WERKI` | AFVKI | MANDT | T001W |  | |
| `WERKI` | AFVC | WERKI | T001W |  | |
| `WERKS` | AFVC | WERKS | T001W |  | |
| `WERKS` | AFVKI | MANDT | T001W |  | |
| `ZERMA` | AFVC | WERKS | T429 |  | |
| `ZERMA` | AFVC | ZERMA | T429 |  | |
| `ZERMA` | AFVKI | MANDT | T429 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zbapi_iia_dates_getlist.txt`
- `ziscsriaufk20.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_