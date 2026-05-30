# `CRHD`

**Description:** Work Center — work center definition
**Category:** Standard SAP Table
**References:** 18 SELECT statements across 16 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/crhd/) — validated 2026-05-30, schema v1.0
**Schema fields:** 125 fields | **Data types:** CHAR(88), DATS(6), DEC(4), NUMC(3), QUAN(8), UNIT(16)

## Key Fields
`LIFNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BEGDA` | BEGDATUM | — | DATS | 8 | 0 | Start Date |
| `ENDDA` | ENDDATUM | — | DATS | 8 | 0 | End Date |
| `AEDAT_GRND` | AEDTM | — | DATS | 8 | 0 | Changed on |
| `AENAM_GRND` | USRNAME | — | CHAR | 12 | 0 | User Name |
| `AEDAT_VORA` | AEDTM | — | DATS | 8 | 0 | Changed on |
| `AENAM_VORA` | USRNAME | — | CHAR | 12 | 0 | User Name |
| `AEDAT_TERM` | AEDTM | — | DATS | 8 | 0 | Changed on |
| `AENAM_TERM` | USRNAME | — | CHAR | 12 | 0 | User Name |
| `AEDAT_TECH` | AEDTM | — | DATS | 8 | 0 | Changed on |
| `AENAM_TECH` | USRNAME | — | CHAR | 12 | 0 | User Name |
| `ARBPL` | ARBPL | — | CHAR | 8 | 0 | Work center |
| `WERKS` | WERKS_D | T001W | CHAR | 4 | 0 | Plant |
| `VERWE` | AP_VERWE | TC30 | CHAR | 4 | 0 | Work Center Category |
| `LVORM` | AP_LOEVORM | — | CHAR | 1 | 0 | Deletion flag for work center |
| `PAR01` | AP_PAR01 | TC20 | CHAR | 6 | 0 | First work center parameter (for formulas) |
| `PAR02` | AP_PAR02 | TC20 | CHAR | 6 | 0 | Second work center parameter (for formulas) |
| `PAR03` | AP_PAR03 | TC20 | CHAR | 6 | 0 | Third work center parameter (for formulas) |
| `PAR04` | AP_PAR04 | TC20 | CHAR | 6 | 0 | Fourth work center parameter (for formulas) |
| `PAR05` | AP_PAR05 | TC20 | CHAR | 6 | 0 | Fifth work center parameter (for formulas) |
| `PAR06` | AP_PAR06 | TC20 | CHAR | 6 | 0 | Sixth work center parameter (for formulas) |
| `PARU1` | AP_PARUNIT | T006 | UNIT | 3 | 0 | Parameter unit |
| `PARU2` | AP_PARUNIT | T006 | UNIT | 3 | 0 | Parameter unit |
| `PARU3` | AP_PARUNIT | T006 | UNIT | 3 | 0 | Parameter unit |
| `PARU4` | AP_PARUNIT | T006 | UNIT | 3 | 0 | Parameter unit |
| `PARU5` | AP_PARUNIT | T006 | UNIT | 3 | 0 | Parameter unit |
| `PARU6` | AP_PARUNIT | T006 | UNIT | 3 | 0 | Parameter unit |
| `PARV1` | AP_PARVAL | — | QUAN | 9 | 3 | Parameter value |
| `PARV2` | AP_PARVAL | — | QUAN | 9 | 3 | Parameter value |
| `PARV3` | AP_PARVAL | — | QUAN | 9 | 3 | Parameter value |
| `PARV4` | AP_PARVAL | — | QUAN | 9 | 3 | Parameter value |
| `PARV5` | AP_PARVAL | — | QUAN | 9 | 3 | Parameter value |
| `PARV6` | AP_PARVAL | — | QUAN | 9 | 3 | Parameter value |
| `PLANV` | AP_PLANV | TC23 | CHAR | 3 | 0 | Key for task list usage |
| `STAND` | AP_STAND | T499S | CHAR | 10 | 0 | Work center location |
| `VERAN` | AP_VERAN | TC24 | CHAR | 3 | 0 | Person responsible for the work center |
| `VGWTS` | VORGSCHL | TC21 | CHAR | 4 | 0 | Standard value key |
| `VGM01` | AP_VGW_MES | — | CHAR | 1 | 0 | Rule for standard value maintenance |
| `VGM02` | AP_VGW_MES | — | CHAR | 1 | 0 | Rule for standard value maintenance |
| `VGM03` | AP_VGW_MES | — | CHAR | 1 | 0 | Rule for standard value maintenance |
| `VGM04` | AP_VGW_MES | — | CHAR | 1 | 0 | Rule for standard value maintenance |
| `VGM05` | AP_VGW_MES | — | CHAR | 1 | 0 | Rule for standard value maintenance |
| `VGM06` | AP_VGW_MES | — | CHAR | 1 | 0 | Rule for standard value maintenance |
| `XDEFA` | AP_DEFAULT | — | CHAR | 1 | 0 | Indicator: Work center for default values |
| `XKOST` | AP_XKOST | — | CHAR | 1 | 0 | Indicator: Work center is maintained for costing |
| `XSPRR` | AP_XSPRR | — | CHAR | 1 | 0 | Indicator: Work center is locked |
| `XTERM` | AP_XTERM | — | CHAR | 1 | 0 | Indicator: Work center is maintained for scheduling |
| `ZGR01` | IDZEITGRAD | TC31 | CHAR | 3 | 0 | Key for performance efficiency rate |
| `ZGR02` | IDZEITGRAD | TC31 | CHAR | 3 | 0 | Key for performance efficiency rate |
| `ZGR03` | IDZEITGRAD | TC31 | CHAR | 3 | 0 | Key for performance efficiency rate |
| `ZGR04` | IDZEITGRAD | TC31 | CHAR | 3 | 0 | Key for performance efficiency rate |
| `ZGR05` | IDZEITGRAD | TC31 | CHAR | 3 | 0 | Key for performance efficiency rate |
| `ZGR06` | IDZEITGRAD | TC31 | CHAR | 3 | 0 | Key for performance efficiency rate |
| `KTSCH` | KTSCH | T435 | CHAR | 7 | 0 | Standard text key |
| `LOANZ` | LOHNANZ | — | DEC | 3 | 0 | Number of Time Tickets |
| `LOART` | LOHNART | — | CHAR | 4 | 0 | Wage Type |
| `LOGRP` | LOHNGRP | T421 | CHAR | 3 | 0 | Wage group |
| `QUALF` | QUALF | T423 | CHAR | 2 | 0 | Suitability |
| `RASCH` | RUEARSCHLU | T428 | CHAR | 2 | 0 | Setup Type Key |
| `STEUS` | STEUS | T430 | CHAR | 4 | 0 | Control key |
| `VGE01` | VGWRTEH | T006 | UNIT | 3 | 0 | Unit of measure for the standard value |
| `VGE02` | VGWRTEH | T006 | UNIT | 3 | 0 | Unit of measure for the standard value |
| `VGE03` | VGWRTEH | T006 | UNIT | 3 | 0 | Unit of measure for the standard value |
| `VGE04` | VGWRTEH | T006 | UNIT | 3 | 0 | Unit of measure for the standard value |
| `VGE05` | VGWRTEH | T006 | UNIT | 3 | 0 | Unit of measure for the standard value |
| `VGE06` | VGWRTEH | T006 | UNIT | 3 | 0 | Unit of measure for the standard value |
| `KTSCH_REF` | KTSCH_REF | — | CHAR | 1 | 0 | Indicator: Standard text key is referenced |
| `LOART_REF` | LOART_REF | — | CHAR | 1 | 0 | Indicator: Wage type is referenced |
| `LOANZ_REF` | LOANZ_REF | — | CHAR | 1 | 0 | Indicator: Number of time tickets is referenced |
| `LOGRP_REF` | LOGRP_REF | — | CHAR | 1 | 0 | Indicator: Wage group is referenced |
| `QUALF_REF` | QUALF_REF | — | CHAR | 1 | 0 | Indicator: Suitability is referenced |
| `RASCH_REF` | RASCH_REF | — | CHAR | 1 | 0 | Indicator: Setup type key is referenced |
| `STEUS_REF` | STEUS_REF | — | CHAR | 1 | 0 | Indicator: Control key is referenced |
| `FORT1` | AP_FORM_T1 | TC25 | CHAR | 6 | 0 | Formula for setup time |
| `FORT2` | AP_FORM_T2 | TC25 | CHAR | 6 | 0 | Formula for the duration of processing time |
| `FORT3` | AP_FORM_T3 | TC25 | CHAR | 6 | 0 | Formula for teardown time |
| `KAPID` | KAPID | KAKO | NUMC | 8 | 0 | Capacity ID |
| `ORTGR` | ORTSGRUPPE | — | CHAR | 4 | 0 | Location group |
| `ZEIWN` | DZEIWN | T006 | UNIT | 3 | 0 | Unit for the standard queue time |
| `ZWNOR` | DZWNOR | — | QUAN | 9 | 3 | Standard queue time |
| `ZEIWM` | DZEIWM | T006 | UNIT | 3 | 0 | Unit for the minumum queue time |
| `ZWMIN` | DZWMIN | — | QUAN | 9 | 3 | Minimum queue time |
| `FORMR` | FLGFORMART | — | CHAR | 1 | 0 | Indicator: same formulas as in capacity |
| `MATYP` | MATYP | TMATY | CHAR | 10 | 0 | Machine type |
| `CPLGR` | CPLGR | T024C | CHAR | 3 | 0 | CAPP planner group |
| `SORTB` | SORTB | TSRTB | CHAR | 9 | 0 | Sort string |
| `MTRVP` | MTRVP | — | DEC | 3 | 1 | Additional time percentage for setup |
| `MTMVP` | MTMVP | — | DEC | 3 | 1 | Additional time percentage for machines |
| `MTPVP` | MTPVP | — | DEC | 3 | 1 | Aditional time percentage for labor |
| `RSANZ` | CR_RS_ANZ | — | NUMC | 3 | 0 | Number of confirmation slips |
| `PDEST` | CR_PDEST | TSP03 | CHAR | 4 | 0 | Printer for shop papers |
| `HROID` | HROBJID | PLOGI | NUMC | 8 | 0 | Object ID |
| `FORTN` | AP_FORM_TN | TC25 | CHAR | 6 | 0 | Formula for the duration of other types of int. processing |
| `ZGR01_REF` | AP_KZREF | — | CHAR | 1 | 0 | Field is referenced |
| `ZGR02_REF` | AP_KZREF | — | CHAR | 1 | 0 | Field is referenced |
| `ZGR03_REF` | AP_KZREF | — | CHAR | 1 | 0 | Field is referenced |
| `ZGR04_REF` | AP_KZREF | — | CHAR | 1 | 0 | Field is referenced |
| `ZGR05_REF` | AP_KZREF | — | CHAR | 1 | 0 | Field is referenced |
| `ZGR06_REF` | AP_KZREF | — | CHAR | 1 | 0 | Field is referenced |
| `STEUS_C` | STEUS | T430 | CHAR | 4 | 0 | Control key |
| `STEUS_I` | STEUS | T430 | CHAR | 4 | 0 | Control key |
| `STEUS_N` | STEUS | T430 | CHAR | 4 | 0 | Control key |
| `STEUS_Q` | STEUS | T430 | CHAR | 4 | 0 | Control key |
| `RUZUS` | RUZUS | TCERS | CHAR | 4 | 0 | Key: rounding and additional values |
| `RSANZ_REF` | RSANZ_REF | — | CHAR | 1 | 0 | Indicator: Number of confirmation slips is referenced |
| `HR` | AP_KZHR | — | CHAR | 1 | 0 | Work center only resides in HR |
| `PRVBE` | PRVBE | PVBE | CHAR | 10 | 0 | Production Supply Area |
| `SUBSYS` | QEIFSUBSYS | QISUB | CHAR | 6 | 0 | Subsystem Identifier for QM Subsystem Interface |
| `BDEGR` | BDEGR | — | CHAR | 3 | 0 | Grouping for Connection to Subsystem |
| `RGEKZ` | RGEKZAP | — | CHAR | 1 | 0 | Indicator: Backflushing |
| `HRTYP` | OTYPE | T778O | CHAR | 2 | 0 | Object Type |
| `SLWID` | SLWID | TCN00 | CHAR | 7 | 0 | Key word ID for user-defined fields |
| `LIFNR` | LIFNR | LFA1 | CHAR | 10 | 0 | Account Number of Vendor or Creditor |
| `SLWID_REF` | AP_KZREF | — | CHAR | 1 | 0 | Field is referenced |
| `LIFNR_REF` | AP_KZREF | — | CHAR | 1 | 0 | Field is referenced |
| `VGARB` | VGWRTAR | T006 | UNIT | 3 | 0 | Unit of measure of work |
| `VGDIM` | VGDIMAR | T006D | CHAR | 6 | 0 | Dimension of work |
| `HRPLVAR` | PLVAR | T778P | CHAR | 2 | 0 | Plan Version |
| `VGDAU` | DAUNORE | — | UNIT | 3 | 0 | Normal duration/unit |
| `STOBJ` | J_OBJNR | — | CHAR | 22 | 0 | Object number |
| `RESGR` | MATRIX_ID | TCYMI | CHAR | 8 | 0 | Matrix identification |
| `LGORT_RES` | LGORT_RES | T001L | CHAR | 4 | 0 | Storage location storage resource |
| `MIXMAT` | MIXMAT | — | CHAR | 1 | 0 | Indicator: mixing of material allowed |
| `ISTBED_KZ` | CY_ISTBEDKZ | — | CHAR | 1 | 0 | Calculation of actual capacity requirements |
| `SRTYPE` | COCF_SR_SRTYPE | COCF_CU_SRTYPE | CHAR | 10 | 0 | Shift Report Type |
| `SNTYPE` | COCF_SN_SNTYPE | TQ80 | CHAR | 2 | 0 | Shift Note Type |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `CPLGR` | CRHD | MANDT | T024C |  | |
| `CPLGR` | CRHD | CPLGR | T024C |  | |
| `FORT1` | CRHD | MANDT | TC25 |  | |
| `FORT1` | CRHD | FORT1 | TC25 |  | |
| `FORT2` | CRHD | MANDT | TC25 |  | |
| `FORT2` | CRHD | FORT2 | TC25 |  | |
| `FORT3` | CRHD | MANDT | TC25 |  | |
| `FORT3` | CRHD | FORT3 | TC25 |  | |
| `FORTN` | CRHD | MANDT | TC25 |  | |
| `FORTN` | CRHD | FORTN | TC25 |  | |
| `HROID` | CRHD | HRTYP | PLOGI |  | |
| `HROID` | CRHD | HROID | PLOGI |  | |
| `HROID` | CRHD | MANDT | PLOGI |  | |
| `HROID` | CRHD | HRPLVAR | PLOGI |  | |
| `HRPLVAR` | CRHD | MANDT | T778P |  | |
| `HRPLVAR` | CRHD | HRPLVAR | T778P |  | |
| `HRTYP` | CRHD | MANDT | T778O |  | |
| `HRTYP` | CRHD | HRTYP | T778O |  | |
| `KAPID` | CRHD | KAPID | KAKO |  | |
| `KAPID` | CRHD | MANDT | KAKO |  | |
| `KTSCH` | CRHD | MANDT | T435 |  | |
| `KTSCH` | CRHD | KTSCH | T435 |  | |
| `LGORT_RES` | CRHD | MANDT | T001L |  | |
| `LGORT_RES` | CRHD | WERKS | T001L |  | |
| `LGORT_RES` | CRHD | LGORT_RES | T001L |  | |
| `LIFNR` | CRHD | MANDT | LFA1 |  | |
| `LIFNR` | CRHD | LIFNR | LFA1 |  | |
| `LOGRP` | CRHD | WERKS | T421 |  | |
| `LOGRP` | CRHD | LOGRP | T421 |  | |
| `LOGRP` | CRHD | MANDT | T421 |  | |
| `MANDT` | CRHD | MANDT | T000 |  | |
| `MATYP` | CRHD | MANDT | TMATY |  | |
| `MATYP` | CRHD | MATYP | TMATY |  | |
| `OBJID` | CRHD | MANDT | CRID |  | |
| `OBJID` | CRHD | OBJTY | CRID |  | |
| `OBJID` | CRHD | OBJID | CRID |  | |
| `PAR01` | CRHD | MANDT | TC20 |  | |
| `PAR01` | CRHD | PAR01 | TC20 |  | |
| `PAR02` | CRHD | MANDT | TC20 |  | |
| `PAR02` | CRHD | PAR02 | TC20 |  | |
| `PAR03` | CRHD | PAR03 | TC20 |  | |
| `PAR03` | CRHD | MANDT | TC20 |  | |
| `PAR04` | CRHD | MANDT | TC20 |  | |
| `PAR04` | CRHD | PAR04 | TC20 |  | |
| `PAR05` | CRHD | MANDT | TC20 |  | |
| `PAR05` | CRHD | PAR05 | TC20 |  | |
| `PAR06` | CRHD | PAR06 | TC20 |  | |
| `PAR06` | CRHD | MANDT | TC20 |  | |
| `PARU1` | CRHD | MANDT | T006 |  | |
| `PARU1` | CRHD | PARU1 | T006 |  | |
| `PARU2` | CRHD | PARU2 | T006 |  | |
| `PARU2` | CRHD | MANDT | T006 |  | |
| `PARU3` | CRHD | MANDT | T006 |  | |
| `PARU3` | CRHD | PARU3 | T006 |  | |
| `PARU4` | CRHD | MANDT | T006 |  | |
| `PARU4` | CRHD | PARU4 | T006 |  | |
| `PARU5` | CRHD | MANDT | T006 |  | |
| `PARU5` | CRHD | PARU5 | T006 |  | |
| `PARU6` | CRHD | MANDT | T006 |  | |
| `PARU6` | CRHD | PARU6 | T006 |  | |
| `PDEST` | CRHD | PDEST | TSP03 |  | |
| `PLANV` | CRHD | MANDT | TC23 |  | |
| `PLANV` | CRHD | PLANV | TC23 |  | |
| `PRVBE` | CRHD | MANDT | PVBE |  | |
| `PRVBE` | CRHD | WERKS | PVBE |  | |
| `PRVBE` | CRHD | PRVBE | PVBE |  | |
| `QUALF` | CRHD | MANDT | T423 |  | |
| `QUALF` | CRHD | WERKS | T423 |  | |
| `QUALF` | CRHD | QUALF | T423 |  | |
| `RASCH` | CRHD | MANDT | T428 |  | |
| `RASCH` | CRHD | WERKS | T428 |  | |
| `RASCH` | CRHD | RASCH | T428 |  | |
| `RESGR` | CRHD | MANDT | TCYMI |  | |
| `RESGR` | CRHD | WERKS | TCYMI |  | |
| `RESGR` | CRHD | RESGR | TCYMI |  | |
| `RUZUS` | CRHD | MANDT | TCERS |  | |
| `RUZUS` | CRHD | RUZUS | TCERS |  | |
| `SLWID` | CRHD | MANDT | TCN00 |  | |
| `SLWID` | CRHD | SLWID | TCN00 |  | |
| `SNTYPE` | CRHD | MANDT | TQ80 |  | |
| `SNTYPE` | CRHD | SNTYPE | TQ80 |  | |
| `SORTB` | CRHD | MANDT | TSRTB |  | |
| `SORTB` | CRHD | SORTB | TSRTB |  | |
| `SRTYPE` | CRHD | MANDT | COCF_CU_SRTYPE |  | |
| `SRTYPE` | CRHD | SRTYPE | COCF_CU_SRTYPE |  | |
| `STAND` | CRHD | STAND | T499S |  | |
| `STAND` | CRHD | MANDT | T499S |  | |
| `STAND` | CRHD | WERKS | T499S |  | |
| `STEUS` | CRHD | MANDT | T430 |  | |
| `STEUS` | &#039;*&#039; |  | T430 |  | |
| `STEUS` | CRHD | STEUS | T430 |  | |
| `STEUS_C` | CRHD | MANDT | T430 |  | |
| `STEUS_C` | &#039;*&#039; |  | T430 |  | |
| `STEUS_C` | CRHD | STEUS_C | T430 |  | |
| `STEUS_I` | CRHD | STEUS_I | T430 |  | |
| `STEUS_I` | CRHD | MANDT | T430 |  | |
| `STEUS_I` | &#039;*&#039; |  | T430 |  | |
| `STEUS_N` | CRHD | MANDT | T430 |  | |
| `STEUS_N` | &#039;*&#039; |  | T430 |  | |
| `STEUS_N` | CRHD | STEUS_N | T430 |  | |
| `STEUS_Q` | &#039;*&#039; |  | T430 |  | |
| `STEUS_Q` | CRHD | STEUS_Q | T430 |  | |
| `STEUS_Q` | CRHD | MANDT | T430 |  | |
| `SUBSYS` | CRHD | MANDT | QISUB |  | |
| `SUBSYS` | CRHD | SUBSYS | QISUB |  | |
| `VERAN` | CRHD | MANDT | TC24 |  | |
| `VERAN` | CRHD | WERKS | TC24 |  | |
| `VERAN` | CRHD | VERAN | TC24 |  | |
| `VERWE` | CRHD | MANDT | TC30 |  | |
| `VERWE` | CRHD | VERWE | TC30 |  | |
| `VGARB` | CRHD | MANDT | T006 |  | |
| `VGARB` | CRHD | VGARB | T006 |  | |
| `VGDIM` | CRHD | MANDT | T006D |  | |
| `VGDIM` | CRHD | VGDIM | T006D |  | |
| `VGE01` | CRHD | MANDT | T006 |  | |
| `VGE01` | CRHD | VGE01 | T006 |  | |
| `VGE02` | CRHD | MANDT | T006 |  | |
| `VGE02` | CRHD | VGE02 | T006 |  | |
| `VGE03` | CRHD | VGE03 | T006 |  | |
| `VGE03` | CRHD | MANDT | T006 |  | |
| `VGE04` | CRHD | MANDT | T006 |  | |
| `VGE04` | CRHD | VGE04 | T006 |  | |
| `VGE05` | CRHD | MANDT | T006 |  | |
| `VGE05` | CRHD | VGE05 | T006 |  | |
| `VGE06` | CRHD | MANDT | T006 |  | |
| `VGE06` | CRHD | VGE06 | T006 |  | |
| `VGWTS` | CRHD | MANDT | TC21 |  | |
| `VGWTS` | CRHD | VGWTS | TC21 |  | |
| `WERKS` | CRHD | MANDT | T001W |  | |
| `WERKS` | CRHD | WERKS | T001W |  | |
| `ZEIWM` | CRHD | MANDT | T006 |  | |
| `ZEIWM` | CRHD | ZEIWM | T006 |  | |
| `ZEIWN` | CRHD | MANDT | T006 |  | |
| `ZEIWN` | CRHD | ZEIWN | T006 |  | |
| `ZGR01` | CRHD | MANDT | TC31 |  | |
| `ZGR01` | CRHD | ZGR01 | TC31 |  | |
| `ZGR02` | CRHD | ZGR02 | TC31 |  | |
| `ZGR02` | CRHD | MANDT | TC31 |  | |
| `ZGR03` | CRHD | MANDT | TC31 |  | |
| `ZGR03` | CRHD | ZGR03 | TC31 |  | |
| `ZGR04` | CRHD | MANDT | TC31 |  | |
| `ZGR04` | CRHD | ZGR04 | TC31 |  | |
| `ZGR05` | CRHD | MANDT | TC31 |  | |
| `ZGR05` | CRHD | ZGR05 | TC31 |  | |
| `ZGR06` | CRHD | MANDT | TC31 |  | |
| `ZGR06` | CRHD | ZGR06 | TC31 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `endda`, `kapid`, `lvorm`, `objid`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `endda`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0104.txt`
- `ziscs0002.txt`
- `ziscs0003.txt`
- `ziscs0007.txt`
- `ziscs0007_gprs.txt`
- `ziscs0016.txt`
- `ziscs0026.txt`
- `ziscs0026a.txt`
- `ziscs0039.txt`
- `ziscs0046.txt`
- `ziscs0200.txt`
- `ziscs0287.txt`
- `ziscs0465.txt`
- `zisdm0144.txt`
- `zisdm0145.txt`
- `zisdmmiolxf66.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_