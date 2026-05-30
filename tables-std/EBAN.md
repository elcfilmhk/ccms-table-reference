# `EBAN`

**Description:** Purchase Requisition — purchase requisition
**Category:** Standard SAP Table
**References:** 16 SELECT statements across 9 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eban/) — validated 2026-05-30, schema v1.0
**Schema fields:** 164 fields | **Data types:** CHAR(118), CUKY(1), CURR(2), DATS(7), DEC(7), INT4(1), LANG(1), NUMC(18), QUAN(6), TIMS(1), UNIT(2)

## Key Fields
`MATNR` | `LIFNR` | `KUNNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BSART` | BBSRT | T161 | CHAR | 4 | 0 | Purchase Requisition Document Type |
| `BSTYP` | BSTYP | — | CHAR | 1 | 0 | Purchasing Document Category |
| `BSAKZ` | BSAKZ | — | CHAR | 1 | 0 | Control indicator for purchasing document type |
| `LOEKZ` | ELOEK | — | CHAR | 1 | 0 | Deletion Indicator in Purchasing Document |
| `STATU` | BANST | — | CHAR | 1 | 0 | Processing status of purchase requisition |
| `ESTKZ` | ESTKZ | — | CHAR | 1 | 0 | Creation Indicator (Purchase Requisition/Schedule Lines) |
| `FRGKZ` | FRGKZ | T161S | CHAR | 1 | 0 | Release Indicator |
| `FRGZU` | FRGZU | — | CHAR | 8 | 0 | Release status |
| `FRGST` | FRGST | — | CHAR | 2 | 0 | Release Strategy in Purchase Requisition |
| `EKGRP` | EKGRP | T024 | CHAR | 3 | 0 | Purchasing Group |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `ERDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AFNAM` | AFNAM | — | CHAR | 12 | 0 | Name of Requisitioner/Requester |
| `TXZ01` | TXZ01 | — | CHAR | 40 | 0 | Short Text |
| `MATNR` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `EMATN` | EMATN | MARA | CHAR | 18 | 0 | Material Number Corresponding to Manufacturer Part Number |
| `WERKS` | EWERK | T001W | CHAR | 4 | 0 | Plant |
| `LGORT` | LGORT_D | T001L | CHAR | 4 | 0 | Storage Location |
| `BEDNR` | BEDNR | — | CHAR | 10 | 0 | Requirement Tracking Number |
| `MATKL` | MATKL | T023 | CHAR | 9 | 0 | Material Group |
| `RESWK` | RESWK | — | CHAR | 4 | 0 | Supplying (Issuing) Plant in Stock Transport Order |
| `MENGE` | BAMNG | — | QUAN | 13 | 3 | Purchase Requisition Quantity |
| `MEINS` | BAMEI | T006 | UNIT | 3 | 0 | Purchase Requisition Unit of Measure |
| `BUMNG` | BUMNG | — | QUAN | 13 | 3 | Shortage (stock undercoverage) quantity |
| `BADAT` | BADAT | — | DATS | 8 | 0 | Requisition (Request) Date |
| `LPEIN` | LPEIN | TPRG | CHAR | 1 | 0 | Category of Delivery Date |
| `LFDAT` | EINDT | — | DATS | 8 | 0 | Item Delivery Date |
| `FRGDT` | FRGDT | — | DATS | 8 | 0 | Purchase Requisition Release Date |
| `WEBAZ` | WEBAZ | — | DEC | 3 | 0 | Goods Receipt Processing Time in Days |
| `PREIS` | BAPRE | — | CURR | 11 | 2 | Price in Purchase Requisition |
| `PEINH` | EPEIN | — | DEC | 5 | 0 | Price Unit |
| `PSTYP` | PSTYP | T163 | CHAR | 1 | 0 | Item Category in Purchasing Document |
| `KNTTP` | KNTTP | T163K | CHAR | 1 | 0 | Account Assignment Category |
| `KZVBR` | KZVBR | — | CHAR | 1 | 0 | Consumption Posting |
| `KFLAG` | KFLAG | — | CHAR | 1 | 0 | Acct.asst.changeable |
| `VRTKZ` | VRTKZ | — | CHAR | 1 | 0 | Distribution indicator for multiple account assignment |
| `TWRKZ` | TWRKZ | — | CHAR | 1 | 0 | Partial Invoice Indicator |
| `WEPOS` | WEPOS | — | CHAR | 1 | 0 | Goods Receipt Indicator |
| `WEUNB` | WEUNB | — | CHAR | 1 | 0 | Goods Receipt, Non-Valuated |
| `REPOS` | REPOS | — | CHAR | 1 | 0 | Invoice Receipt Indicator |
| `LIFNR` | WLIEF | LFA1 | CHAR | 10 | 0 | Desired Vendor |
| `FLIEF` | FLIEF | LFA1 | CHAR | 10 | 0 | Fixed Vendor |
| `EKORG` | EKORG | T024E | CHAR | 4 | 0 | Purchasing Organization |
| `VRTYP` | BSTYP | — | CHAR | 1 | 0 | Purchasing Document Category |
| `KONNR` | KONNR | EKKO | CHAR | 10 | 0 | Number of Principal Purchase Agreement |
| `KTPNR` | KTPNR | EKPO | NUMC | 5 | 0 | Item Number of Principal Purchase Agreement |
| `INFNR` | INFNR | EINA | CHAR | 10 | 0 | Number of Purchasing Info Record |
| `ZUGBA` | DZUGBA | — | CHAR | 1 | 0 | Assigned Source of Supply |
| `QUNUM` | QUNUM | — | CHAR | 10 | 0 | Number of Quota Arrangement |
| `QUPOS` | QUPOS | — | NUMC | 3 | 0 | Quota Arrangement Item |
| `DISPO` | DISPO | T024D | CHAR | 3 | 0 | MRP Controller (Materials Planner) |
| `SERNR` | SERNR | — | CHAR | 8 | 0 | BOM explosion number |
| `BVDAT` | BVDAT | — | DATS | 8 | 0 | Date of last resubmission |
| `BATOL` | BATOL | — | DEC | 3 | 0 | Resubmission Interval of Purchase Requisition |
| `BVDRK` | BVDRK | — | DEC | 7 | 0 | Number of resubmissions |
| `EBELN` | BSTNR | EKKO | CHAR | 10 | 0 | Purchase Order Number |
| `EBELP` | BSTPO | EKPO | NUMC | 5 | 0 | Purchase Order Item Number |
| `BEDAT` | BEDAT | — | DATS | 8 | 0 | Purchase Order Date |
| `BSMNG` | BSMNG | — | QUAN | 13 | 3 | Quantity Ordered Against this Purchase Requisition |
| `LBLNI` | LBLNI | ESSR | CHAR | 10 | 0 | Entry Sheet Number |
| `BWTAR` | BWTAR_D | T149D | CHAR | 10 | 0 | Valuation Type |
| `XOBLR` | XOBLR | — | CHAR | 1 | 0 | Item affects commitments |
| `EBAKZ` | EBAKZ | — | CHAR | 1 | 0 | Purchase Requisition Closed |
| `RSNUM` | RSNUM | — | NUMC | 10 | 0 | Number of Reservation/Dependent Requirement |
| `SOBKZ` | SOBKZ | T148 | CHAR | 1 | 0 | Special Stock Indicator |
| `ARSNR` | ARSNR | — | NUMC | 10 | 0 | Settlement reservation number |
| `ARSPS` | ARSPS | — | NUMC | 4 | 0 | Item number of the settlement reservation |
| `FIXKZ` | BAFIX | — | CHAR | 1 | 0 | Purchase Requisition is Fixed |
| `BMEIN` | BSTME | T006 | UNIT | 3 | 0 | Purchase Order Unit of Measure |
| `REVLV` | REVLV | — | CHAR | 2 | 0 | Revision Level |
| `VORAB` | VORAB | — | CHAR | 1 | 0 | Advance procurement: project stock |
| `PACKNO` | PACKNO | ESLH | NUMC | 10 | 0 | Package number |
| `KANBA` | KBNKZ | — | CHAR | 1 | 0 | Kanban Indicator |
| `BPUEB` | BPUEB | — | CHAR | 1 | 0 | Adopt Requisition Price in Purchase Order |
| `CUOBJ` | CUOBJ | — | NUMC | 18 | 0 | Configuration (internal object number) |
| `FRGGR` | FRGGR | T16FG | CHAR | 2 | 0 | Release group |
| `FRGRL` | FRGRL | — | CHAR | 1 | 0 | Release Not Yet Completely Effected |
| `AKTNR` | WAKTION | WAKH | CHAR | 10 | 0 | Promotion |
| `CHARG` | CHARG_D | — | CHAR | 10 | 0 | Batch Number |
| `UMSOK` | UMSOK | — | CHAR | 1 | 0 | Special Stock Indicator for Physical Stock Transfer |
| `VERID` | VERID | — | CHAR | 4 | 0 | Production Version |
| `FIPOS` | FIPOS | — | CHAR | 14 | 0 | Commitment Item |
| `FISTL` | FISTL | — | CHAR | 16 | 0 | Funds Center |
| `GEBER` | BP_GEBER | — | CHAR | 10 | 0 | Fund |
| `KZKFG` | KZCUH | — | CHAR | 1 | 0 | Origin of Configuration |
| `SATNR` | SATNR | — | CHAR | 18 | 0 | Cross-Plant Configurable Material |
| `MNG02` | MNG06 | — | QUAN | 13 | 3 | Committed Quantity |
| `DAT01` | DAT05 | — | DATS | 8 | 0 | Committed Date |
| `ATTYP` | ATTYP | — | CHAR | 2 | 0 | Material Category |
| `ADRNR` | ADRNR_MM | ADRC | CHAR | 10 | 0 | Manual address number in purchasing document item |
| `ADRN2` | ADRN2 | ADRC | CHAR | 10 | 0 | Number of delivery address |
| `KUNNR` | EKUNNR | KNA1 | CHAR | 10 | 0 | Customer |
| `EMLIF` | EMLIF | LFA1 | CHAR | 10 | 0 | Vendor to be supplied/who is to receive delivery |
| `LBLKZ` | LBLKZ | — | CHAR | 1 | 0 | Subcontracting vendor |
| `KZBWS` | KZBWS | — | CHAR | 1 | 0 | Valuation of Special Stock |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `IDNLF` | IDNLF | — | CHAR | 35 | 0 | Material Number Used by Vendor |
| `GSFRG` | GSFRG | — | CHAR | 1 | 0 | Overall release of purchase requisitions |
| `MPROF` | MPROF | — | CHAR | 4 | 0 | Manufacturer Part Profile |
| `KZFME` | KZWSO | — | CHAR | 1 | 0 | Units of measure usage |
| `SPRAS` | SPRAS | T002 | LANG | 1 | 0 | Language Key |
| `TECHS` | TECHS | — | CHAR | 12 | 0 | Parameter Variant/Standard Variant |
| `MFRPN` | MFRPN | — | CHAR | 40 | 0 | Manufacturer Part Number |
| `MFRNR` | MFRNR | LFA1 | CHAR | 10 | 0 | Number of a Manufacturer |
| `EMNFR` | EMNFR | — | CHAR | 10 | 0 | External manufacturer code name or number |
| `FORDN` | SFORDN | — | CHAR | 10 | 0 | Framework Order |
| `FORDP` | FORDP | — | NUMC | 5 | 0 | Item of framework order |
| `PLIFZ` | PLIFZ | — | DEC | 3 | 0 | Planned Delivery Time in Days |
| `BERID` | BERID | — | CHAR | 10 | 0 | MRP Area |
| `UZEIT` | LZEIT | — | TIMS | 6 | 0 | Delivery Date Time-Spot |
| `FKBER` | FKBER | — | CHAR | 16 | 0 | Functional Area |
| `GRANT_NBR` | GM_GRANT_NBR | — | CHAR | 20 | 0 | Grant |
| `MEMORY` | MEMBF | — | CHAR | 1 | 0 | Purchase Requisition not yet Complete |
| `BANPR` | BANPR | — | CHAR | 2 | 0 | Requisition Processing State |
| `RLWRT` | RLWRT | — | CURR | 15 | 2 | Total value at time of release |
| `BLCKD` | BLCKD | — | CHAR | 1 | 0 | Purchase Requisition Blocked |
| `REVNO` | REVNO | — | CHAR | 8 | 0 | Version number in Purchasing |
| `BLCKT` | BLCKT | — | CHAR | 60 | 0 | Reason for Item Block |
| `BESWK` | BESWK | T001W | CHAR | 4 | 0 | Procuring Plant |
| `EPROFILE` | MEPROFILE | — | CHAR | 2 | 0 | External Procurement Profile |
| `EPREFDOC` | EPREFDOC | — | CHAR | 10 | 0 | External Procurement Reference Document |
| `EPREFITM` | EPREFITM | — | NUMC | 5 | 0 | External Procurement Reference Item |
| `GMMNG` | GMMNG | — | QUAN | 13 | 3 | PO Quantity of Purchase Requisition in POs on Hold |
| `WRTKZ` | WRTKZ | — | CHAR | 1 | 0 | Value-Based Commitment Reduction for Service Purchase Reqs |
| `RESLO` | RESLO | — | CHAR | 4 | 0 | Issuing Storage Location for Stock Transport Order |
| `KBLNR` | KBLNR | — | CHAR | 10 | 0 | Document Number for Earmarked Funds |
| `KBLPOS` | KBLPOS | — | NUMC | 3 | 0 | Earmarked Funds: Document Item |
| `PRIO_URG` | PRIO_URG | PURG | NUMC | 2 | 0 | Requirement Urgency |
| `PRIO_REQ` | PRIO_REQ | PREQ | NUMC | 3 | 0 | Requirement Priority |
| `MEMORYTYPE` | MEMORYTYPE | — | CHAR | 1 | 0 | Category of Incompleteness |
| `ANZSN` | ANZSN | — | INT4 | 10 | 0 | Number of serial numbers |
| `MHDRZ` | MHDRZ | — | DEC | 4 | 0 | Minimum Remaining Shelf Life |
| `IPRKZ` | DATTP | — | CHAR | 1 | 0 | Period Indicator for Shelf Life Expiration Date |
| `NODISP` | NODISP | — | CHAR | 1 | 0 | Ind: Reserv. not applicable to MRP;Purc. req. not created |
| `SRM_CONTRACT_ID` | SRM_CONTRACT_ID | — | CHAR | 10 | 0 | Central Contract |
| `SRM_CONTRACT_ITM` | SRM_CONTRACT_ITEM | — | NUMC | 10 | 0 | Central Contract Item Number |
| `BUDGET_PD` | FM_BUDGET_PERIOD | — | CHAR | 10 | 0 | FM: Budget Period |
| `ADVCODE` | /ISDFPS/ADVCODE | /ISDFPS/ADVCODE2 | CHAR | 2 | 0 | Advice Code |
| `STACODE` | /ISDFPS/STACODE | /ISDFPS/CSTACODE | CHAR | 2 | 0 | Status Code |
| `BANFN_CS` | /ISDFPS/BANFN_CS | — | CHAR | 10 | 0 | Cross-System PReq Number |
| `BNFPO_CS` | /ISDFPS/BNFPO_CS | — | NUMC | 5 | 0 | Cross-System PReq Item |
| `ITEM_CS` | /ISDFPS/ITEM_CS | — | CHAR | 1 | 0 | Cross-System Item Category |
| `BSMNG_SND` | /ISDFPS/BSMNG_SND | — | QUAN | 13 | 3 | PO Quantity Sender |
| `NO_MARD_DATA` | /ISDFPS/NO_MARD_DATA | — | CHAR | 1 | 0 | No Storage Location Data Exists for Material |
| `SERRU` | SERRU | — | CHAR | 1 | 0 | Type of subcontracting |
| `DISUB_SOBKZ` | DISUB_SOBKZ_LB | — | CHAR | 1 | 0 | Special stock indicator Subcontracting |
| `DISUB_PSPNR` | PS_PSP_PNR | — | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `DISUB_KUNNR` | KUNNR | — | CHAR | 10 | 0 | Customer Number |
| `DISUB_VBELN` | VBELN | — | CHAR | 10 | 0 | Sales and Distribution Document Number |
| `DISUB_POSNR` | POSNR | — | NUMC | 6 | 0 | Item number of the SD document |
| `DISUB_OWNER` | OWNER_D | — | CHAR | 10 | 0 | Owner of stock |
| `IUID_RELEVANT` | IUID_RELEVANT | — | CHAR | 1 | 0 | IUID-Relevant |
| `OITAXFROM` | OIH_TAXFRO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;from&#039; location |
| `OIHANTYP` | OIH_HANTYP | OIH5 | CHAR | 2 | 0 | Excise Duty Handling Type |
| `OITAXTO` | OIH_TAXTO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;to&#039; location |
| `OITAXGRP` | OIH_TAXGRP | OIH2 | CHAR | 2 | 0 | Excise Duty Group |
| `OIOILCON` | OIH_OILCON | — | DEC | 5 | 2 | Oil content in a material as a percentage |
| `OIINEX` | OIH_INEX | OIH16 | CHAR | 2 | 0 | Code for internal or external excise duty rate determination |
| `OIPRICIE` | OIH_PRICIE | — | CHAR | 1 | 0 | ED pricing: external (indicator) |
| `OIO_SPROC` | OIO_SPROC | — | CHAR | 4 | 0 | Supply Process |
| `OIO_STATUS` | OIO_SC_STATUS | — | CHAR | 1 | 0 | Supply chain status |
| `OIO_REF_BANFN` | OIO_REF_BANFN | — | CHAR | 10 | 0 | Reference requisition number |
| `OIO_REF_BNFPO` | OIO_REF_BNFPO | — | NUMC | 5 | 0 | Reference requisition item |
| `OIO_HOLD` | OIO_HOLD | — | CHAR | 1 | 0 | Indicator: Hold Delivery Onshore |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ADRN2` | EBAN | ADRN2 | ADRC |  | |
| `ADRN2` | * |  | ADRC |  | |
| `ADRN2` | * |  | ADRC |  | |
| `ADRN2` | EBAN | MANDT | ADRC |  | |
| `ADRNR` | * |  | ADRC |  | |
| `ADRNR` | * |  | ADRC |  | |
| `ADRNR` | EBAN | MANDT | ADRC |  | |
| `ADRNR` | EBAN | ADRNR | ADRC |  | |
| `ADVCODE` | EBAN | MANDT | /ISDFPS/ADVCODE2 |  | |
| `ADVCODE` | EBAN | BSART | /ISDFPS/ADVCODE2 |  | |
| `ADVCODE` | EBAN | ADVCODE | /ISDFPS/ADVCODE2 |  | |
| `AKTNR` | EBAN | MANDT | WAKH |  | |
| `AKTNR` | EBAN | AKTNR | WAKH |  | |
| `BESWK` | EBAN | MANDT | T001W |  | |
| `BESWK` | EBAN | BESWK | T001W |  | |
| `BMEIN` | EBAN | MANDT | T006 |  | |
| `BMEIN` | EBAN | BMEIN | T006 |  | |
| `BSART` | EBAN | MANDT | T161 |  | |
| `BSART` | EBAN | BSTYP | T161 |  | |
| `BSART` | EBAN | BSART | T161 |  | |
| `BWTAR` | EBAN | MANDT | T149D |  | |
| `BWTAR` | EBAN | BWTAR | T149D |  | |
| `DISPO` | EBAN | WERKS | T024D |  | |
| `DISPO` | EBAN | DISPO | T024D |  | |
| `DISPO` | EBAN | MANDT | T024D |  | |
| `EBELN` | EBAN | EBELN | EKKO |  | |
| `EBELN` | EBAN | MANDT | EKKO |  | |
| `EBELP` | EBAN | MANDT | EKPO |  | |
| `EBELP` | EBAN | EBELN | EKPO |  | |
| `EBELP` | EBAN | EBELP | EKPO |  | |
| `EKGRP` | EBAN | MANDT | T024 |  | |
| `EKGRP` | EBAN | EKGRP | T024 |  | |
| `EKORG` | EBAN | MANDT | T024E |  | |
| `EKORG` | EBAN | EKORG | T024E |  | |
| `EMATN` | EBAN | MANDT | MARA |  | |
| `EMATN` | EBAN | EMATN | MARA |  | |
| `EMLIF` | EBAN | EMLIF | LFA1 |  | |
| `EMLIF` | EBAN | MANDT | LFA1 |  | |
| `FLIEF` | EBAN | MANDT | LFA1 |  | |
| `FLIEF` | EBAN | FLIEF | LFA1 |  | |
| `FRGGR` | EBAN | MANDT | T16FG |  | |
| `FRGGR` | EBAN | FRGGR | T16FG |  | |
| `FRGKZ` | EBAN | MANDT | T161S |  | |
| `FRGKZ` | EBAN | FRGKZ | T161S |  | |
| `INFNR` | EBAN | MANDT | EINA |  | |
| `INFNR` | EBAN | INFNR | EINA |  | |
| `KNTTP` | EBAN | KNTTP | T163K |  | |
| `KNTTP` | EBAN | MANDT | T163K |  | |
| `KONNR` | EBAN | MANDT | EKKO |  | |
| `KONNR` | EBAN | KONNR | EKKO |  | |
| `KTPNR` | EBAN | MANDT | EKPO |  | |
| `KTPNR` | EBAN | KONNR | EKPO |  | |
| `KTPNR` | EBAN | KTPNR | EKPO |  | |
| `KUNNR` | EBAN | MANDT | KNA1 |  | |
| `KUNNR` | EBAN | KUNNR | KNA1 |  | |
| `LBLNI` | EBAN | MANDT | ESSR |  | |
| `LBLNI` | EBAN | LBLNI | ESSR |  | |
| `LGORT` | EBAN | WERKS | T001L |  | |
| `LGORT` | EBAN | LGORT | T001L |  | |
| `LGORT` | EBAN | MANDT | T001L |  | |
| `LIFNR` | EBAN | MANDT | LFA1 |  | |
| `LIFNR` | EBAN | LIFNR | LFA1 |  | |
| `LPEIN` | EBAN | MANDT | TPRG |  | |
| `LPEIN` | SYST | LANGU | TPRG |  | |
| `LPEIN` | EBAN | LPEIN | TPRG |  | |
| `MANDT` | EBAN | MANDT | T000 |  | |
| `MATKL` | EBAN | MANDT | T023 |  | |
| `MATKL` | EBAN | MATKL | T023 |  | |
| `MATNR` | EBAN | MANDT | MARA |  | |
| `MATNR` | EBAN | MATNR | MARA |  | |
| `MEINS` | EBAN | MANDT | T006 |  | |
| `MEINS` | EBAN | MEINS | T006 |  | |
| `MFRNR` | EBAN | MFRNR | LFA1 |  | |
| `MFRNR` | EBAN | MANDT | LFA1 |  | |
| `OIHANTYP` | EBAN | MANDT | OIH5 |  | |
| `OIHANTYP` | EBAN | OIHANTYP | OIH5 |  | |
| `OIINEX` | EBAN | MANDT | OIH16 |  | |
| `OIINEX` | EBAN | OIINEX | OIH16 |  | |
| `OITAXFROM` | EBAN | OITAXFROM | OIH4 |  | |
| `OITAXFROM` | EBAN | MANDT | OIH4 |  | |
| `OITAXGRP` | EBAN | MANDT | OIH2 |  | |
| `OITAXGRP` | EBAN | OITAXGRP | OIH2 |  | |
| `OITAXTO` | EBAN | MANDT | OIH4 |  | |
| `OITAXTO` | EBAN | OITAXTO | OIH4 |  | |
| `PACKNO` | EBAN | MANDT | ESLH |  | |
| `PACKNO` | EBAN | PACKNO | ESLH |  | |
| `PRIO_REQ` | EBAN | PRIO_REQ | PREQ |  | |
| `PRIO_REQ` | EBAN | MANDT | PREQ |  | |
| `PRIO_URG` | EBAN | MANDT | PURG |  | |
| `PRIO_URG` | EBAN | PRIO_URG | PURG |  | |
| `PSTYP` | EBAN | MANDT | T163 |  | |
| `PSTYP` | EBAN | PSTYP | T163 |  | |
| `SOBKZ` | EBAN | SOBKZ | T148 |  | |
| `SOBKZ` | EBAN | MANDT | T148 |  | |
| `SPRAS` | EBAN | SPRAS | T002 |  | |
| `STACODE` | EBAN | MANDT | /ISDFPS/CSTACODE |  | |
| `STACODE` | EBAN | STACODE | /ISDFPS/CSTACODE |  | |
| `WAERS` | EBAN | MANDT | TCURC |  | |
| `WAERS` | EBAN | WAERS | TCURC |  | |
| `WERKS` | EBAN | WERKS | T001W |  | |
| `WERKS` | EBAN | MANDT | T001W |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ADRN2`, `ADRNR`, `ADVCODE`, `AFNAM`, `AKTNR`, `ARSNR`, `ARSPS`, `ATTYP`, `BADAT`, `BANFN`, `BANFN_CS`, `BANPR`, `BATOL`, `BEDAT`, `BEDNR`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zissd00040.txt`
- `zissd00072.txt`
- `zissd00079.txt`
- `zissd00081.txt`
- `zissd00086.txt`
- `zissd00098.txt`
- `zissd00108.txt`
- `zmmprsi01.txt`
- `zmmprsi13.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_