# `EKKO`

**Description:** Purchasing Document Header — PO header
**Category:** Standard SAP Table
**References:** 32 SELECT statements across 16 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/ekko/) — validated 2026-05-30, schema v1.0
**Schema fields:** 150 fields | **Data types:** CHAR(115), CUKY(2), CURR(6), DATS(12), DEC(8), LANG(1), NUMC(6)

## Key Fields
`BUKRS` | `LIFNR` | `KUNNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `BSTYP` | EBSTYP | — | CHAR | 1 | 0 | Purchasing Document Category |
| `BSART` | ESART | T161 | CHAR | 4 | 0 | Purchasing Document Type |
| `BSAKZ` | BSAKZ | — | CHAR | 1 | 0 | Control indicator for purchasing document type |
| `LOEKZ` | ELOEK | — | CHAR | 1 | 0 | Deletion Indicator in Purchasing Document |
| `STATU` | ESTAK | — | CHAR | 1 | 0 | Status of Purchasing Document |
| `AEDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `PINCR` | PINCR | — | NUMC | 5 | 0 | Item Number Interval |
| `LPONR` | LPONR | EKPO | NUMC | 5 | 0 | Last Item Number |
| `LIFNR` | ELIFN | LFA1 | CHAR | 10 | 0 | Vendor Account Number |
| `SPRAS` | SPRAS | T002 | LANG | 1 | 0 | Language Key |
| `ZTERM` | DZTERM | — | CHAR | 4 | 0 | Terms of Payment Key |
| `ZBD1T` | DZBDET | — | DEC | 3 | 0 | Cash (Prompt Payment) Discount Days |
| `ZBD2T` | DZBDET | — | DEC | 3 | 0 | Cash (Prompt Payment) Discount Days |
| `ZBD3T` | DZBDET | — | DEC | 3 | 0 | Cash (Prompt Payment) Discount Days |
| `ZBD1P` | DZBD1P | — | DEC | 5 | 3 | Cash Discount Percentage 1 |
| `ZBD2P` | DZBD2P | — | DEC | 5 | 3 | Cash Discount Percentage 2 |
| `EKORG` | EKORG | T024E | CHAR | 4 | 0 | Purchasing Organization |
| `EKGRP` | BKGRP | T024 | CHAR | 3 | 0 | Purchasing Group |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `WKURS` | WKURS | — | DEC | 9 | 5 | Exchange Rate |
| `KUFIX` | KUFIX | — | CHAR | 1 | 0 | Indicator: Fixing of Exchange Rate |
| `BEDAT` | EBDAT | — | DATS | 8 | 0 | Purchasing Document Date |
| `KDATB` | KDATB | — | DATS | 8 | 0 | Start of Validity Period |
| `KDATE` | KDATE | — | DATS | 8 | 0 | End of Validity Period |
| `BWBDT` | BWBDT | — | DATS | 8 | 0 | Closing Date for Applications |
| `ANGDT` | ANGAB | — | DATS | 8 | 0 | Deadline for Submission of Bid/Quotation |
| `BNDDT` | EBNDT | — | DATS | 8 | 0 | Binding Period for Quotation |
| `GWLDT` | MM_GWLDT | — | DATS | 8 | 0 | Warranty Date |
| `AUSNR` | AUSCH | EKKO | CHAR | 10 | 0 | Bid invitation number |
| `ANGNR` | ANGNR | — | CHAR | 10 | 0 | Quotation Number |
| `IHRAN` | IHRAN | — | DATS | 8 | 0 | Quotation Submission Date |
| `IHREZ` | IHREZ | — | CHAR | 12 | 0 | Your Reference |
| `VERKF` | EVERK | — | CHAR | 30 | 0 | Responsible Salesperson at Vendor&#039;s Office |
| `TELF1` | TELF0 | — | CHAR | 16 | 0 | Vendor&#039;s Telephone Number |
| `LLIEF` | LLIEF | LFA1 | CHAR | 10 | 0 | Supplying Vendor |
| `KUNNR` | KUNNR | KNA1 | CHAR | 10 | 0 | Customer Number |
| `KONNR` | KONNR | EKKO | CHAR | 10 | 0 | Number of Principal Purchase Agreement |
| `ABGRU` | ABDUM | — | CHAR | 2 | 0 | Field Not Used |
| `AUTLF` | KMPLF | — | CHAR | 1 | 0 | Complete Delivery Stipulated for Each Purchase Order |
| `WEAKT` | WEAKT | — | CHAR | 1 | 0 | Indicator: Goods Receipt Message |
| `RESWK` | RESWK | T001W | CHAR | 4 | 0 | Supplying (Issuing) Plant in Stock Transport Order |
| `LBLIF` | LBLIF | LFA1 | CHAR | 10 | 0 | Field not used |
| `INCO1` | INCO1 | TINC | CHAR | 3 | 0 | Incoterms (Part 1) |
| `INCO2` | INCO2 | — | CHAR | 28 | 0 | Incoterms (Part 2) |
| `KTWRT` | KTWRT | — | CURR | 15 | 2 | Target Value for Header Area per Distribution |
| `SUBMI` | SUBMI | — | CHAR | 10 | 0 | Collective Number |
| `KNUMV` | KNUMV | — | CHAR | 10 | 0 | Number of the document condition |
| `KALSM` | KALSM_D | T683 | CHAR | 6 | 0 | Procedure (Pricing, Output Control, Acct. Det., Costing,...) |
| `STAFO` | STAFO | — | CHAR | 6 | 0 | Update group for statistics update |
| `LIFRE` | LIFRE | LFA1 | CHAR | 10 | 0 | Different Invoicing Party |
| `EXNUM` | EXNUM | EIKP | CHAR | 10 | 0 | Number of foreign trade data in MM and SD documents |
| `UNSEZ` | UNSEZ | — | CHAR | 12 | 0 | Our Reference |
| `LOGSY` | LOGSYSTEM | — | CHAR | 10 | 0 | Logical System |
| `UPINC` | UPINC | — | NUMC | 5 | 0 | Item Number Interval for Subitems |
| `STAKO` | STAKO | — | CHAR | 1 | 0 | Document with time-dependent conditions |
| `FRGGR` | FRGGR | T16FG | CHAR | 2 | 0 | Release group |
| `FRGSX` | FRGSX | T16FS | CHAR | 2 | 0 | Release Strategy |
| `FRGKE` | FRGKE | T16FB | CHAR | 1 | 0 | Release Indicator: Purchasing Document |
| `FRGZU` | FRGZU | — | CHAR | 8 | 0 | Release status |
| `FRGRL` | FRGRL | — | CHAR | 1 | 0 | Release Not Yet Completely Effected |
| `LANDS` | LAND1_STML | T005 | CHAR | 3 | 0 | Country for Tax Return |
| `LPHIS` | LPHIS | — | CHAR | 1 | 0 | Indicator for scheduling agreement release documentation |
| `ADRNR` | AD_ADDRNUM | — | CHAR | 10 | 0 | Address number |
| `STCEG_L` | STCEG_L | — | CHAR | 3 | 0 | Country of Sales Tax ID Number |
| `STCEG` | STCEG | — | CHAR | 20 | 0 | VAT Registration Number |
| `ABSGR` | ABSGR | T165R | NUMC | 2 | 0 | Reason for Cancellation |
| `ADDNR` | ADDI_BELNR | — | CHAR | 10 | 0 | Document number for additional |
| `KORNR` | KORNR | — | CHAR | 1 | 0 | Correction of miscellaneous provisions |
| `MEMORY` | MEMER | — | CHAR | 1 | 0 | Purchase order not yet complete |
| `PROCSTAT` | MEPROCSTATE | — | CHAR | 2 | 0 | Purchasing document processing state |
| `RLWRT` | RLWRT | — | CURR | 15 | 2 | Total value at time of release |
| `REVNO` | REVNO | — | CHAR | 8 | 0 | Version number in Purchasing |
| `SCMPROC` | SCMPROC | — | CHAR | 1 | 0 | SCM Process That Created the Purchase Order |
| `REASON_CODE` | /SAPPSPRO/_GR_REASON_CODE | — | CHAR | 4 | 0 | Goods Receipt Reason Code |
| `MEMORYTYPE` | MEMORYTYPE | — | CHAR | 1 | 0 | Category of Incompleteness |
| `RETTP` | RETTP | — | CHAR | 1 | 0 | Retention Indicator |
| `RETPC` | RETPZ | — | DEC | 5 | 2 | Retention in Percent |
| `DPTYP` | ME_DPTYP | — | CHAR | 4 | 0 | Down Payment Indicator |
| `DPPCT` | ME_DPPCNT | — | DEC | 5 | 2 | Down Payment Percentage |
| `DPAMT` | ME_DPAMNT | — | CURR | 11 | 2 | Down Payment Amount in Document Currency |
| `DPDAT` | ME_DPDDAT | — | DATS | 8 | 0 | Due Date for Down Payment |
| `MSR_ID` | MSR_PROCESS_ID | — | CHAR | 10 | 0 | Process Identification Number |
| `HIERARCHY_EXISTS` | HIERARCHY_EXISTS | — | CHAR | 1 | 0 | Part of a Contract Hierarchy |
| `THRESHOLD_EXISTS` | EX_RATE_THRESHOLD | — | CHAR | 1 | 0 | Threshold Value for Exchange Rates Exists |
| `LEGAL_CONTRACT` | LEGAL_CONTRACT_ID | — | CHAR | 40 | 0 | Legal Contract Number |
| `DESCRIPTION` | CONTRACT_DESCRIPTION | — | CHAR | 40 | 0 | Contract Name |
| `RELEASE_DATE` | RELEASE_DATE | — | DATS | 8 | 0 | Release Date of Contract |
| `VSART` | VERSART | — | CHAR | 2 | 0 | Shipping type |
| `HANDOVERLOC` | HANDOVER_LOC | — | CHAR | 10 | 0 | Location for a physical handover of goods |
| `FORCE_ID` | /ISDFPS/FORCE_ID | — | CHAR | 32 | 0 | Internal Key for Force Element |
| `FORCE_CNT` | /ISDFPS/FORCE_CNT | — | NUMC | 6 | 0 | Internal (Version) Counter |
| `RELOC_ID` | /ISDFPS/RELOC_ID | /ISDFPS/REL | CHAR | 10 | 0 | Relocation ID |
| `RELOC_SEQ_ID` | /ISDFPS/RELOC_SEQ_ID | /ISDFPS/RELSEQ | CHAR | 4 | 0 | Relocation Step ID |
| `SOURCE_LOGSYS` | LOGSYS | — | CHAR | 10 | 0 | Logical system |
| `OIEXGNUM` | OIA_EXGNUM | — | CHAR | 10 | 0 | Exchange agreement number |
| `OIEXGTYP` | OIA_EXGTYP | — | CHAR | 4 | 0 | Exchange type |
| `OIAEVGTYPE` | OIA_EVTYPE | — | CHAR | 1 | 0 | Evergreen type |
| `OIPIPEVAL` | OID_PIPEV | — | CHAR | 1 | 0 | Validation indicator for pipeline fields (X=ON, blank=OFF) |
| `OIC_LIFNR` | LIFNR | LFA1 | CHAR | 10 | 0 | Account Number of Vendor or Creditor |
| `OIC_DCITYC` | OIC_DCITYC | T005G | CHAR | 4 | 0 | Destination city code |
| `OIC_DCOUNC` | OIC_DCOUNC | T005E | CHAR | 3 | 0 | Destination county code |
| `OIC_DREGIO` | OIC_DREGIO | T005S | CHAR | 3 | 0 | Destination region |
| `OIC_DLAND1` | OIC_DLAND1 | T005 | CHAR | 3 | 0 | Destination country |
| `OIC_OCITYC` | OIC_OCITYC | T005G | CHAR | 4 | 0 | Origin city code |
| `OIC_OCOUNC` | OIC_OCOUNC | T005E | CHAR | 3 | 0 | Origin county code |
| `OIC_OREGIO` | OIC_OREGIO | T005S | CHAR | 3 | 0 | Origin region |
| `OIC_OLAND1` | OIC_OLAND1 | T005 | CHAR | 3 | 0 | Origin country |
| `OIC_PORGIN` | OIC_PORGIN | — | CHAR | 15 | 0 | Tax origin |
| `OIC_PDESTN` | OIC_PDESTN | — | CHAR | 15 | 0 | Tax destination |
| `OIC_PTRIP` | OIC_PTRIP | — | CHAR | 16 | 0 | Pipeline trip number (external) |
| `OIC_PBATCH` | OIC_PBATCH | — | CHAR | 16 | 0 | OIC_PBATCH |
| `OIC_MOT` | OIC_MOT | TVTR | CHAR | 2 | 0 | IS-OIL MAP external details mode of transport |
| `OIC_AORGIN` | OIC_AORGIN | — | CHAR | 15 | 0 | Alternate origin |
| `OIC_ADESTN` | OIC_ADESTN | — | CHAR | 15 | 0 | Alternate destination |
| `OIC_TRUCKN` | OIC_TRUCKN | — | CHAR | 10 | 0 | Truck number |
| `OIA_BASELO` | OIA_BASELO | — | CHAR | 15 | 0 | Base location |
| `OID_EXTBOL` | OID_EXTBOL | — | CHAR | 16 | 0 | External bill of lading |
| `OID_MISCDL` | OID_MISCDL | — | CHAR | 16 | 0 | Miscellaneous delivery number |
| `VZSKZ` | VZSKZ | — | CHAR | 2 | 0 | Interest calculation indicator |
| `POHF_TYPE` | WRF_POHF_TYPE | — | CHAR | 1 | 0 | Document for Seasonal Purchase Order Processing |
| `EQ_EINDT` | WRF_POHF_EQ_EINDT | — | DATS | 8 | 0 | Delivery Date Header: All Items Have Same Delivery Date |
| `EQ_WERKS` | WRF_POHF_EQ_EWERK | — | CHAR | 4 | 0 | Plant Header: All Items Have Same Receiving Plant |
| `FIXPO` | WRF_POHF_FIXPO | — | CHAR | 1 | 0 | Firm Deal Indicator |
| `EKGRP_ALLOW` | WRF_POHF_EKGRP_ALLOW | — | CHAR | 1 | 0 | Take Account of Purch. Group |
| `WERKS_ALLOW` | WRF_POHF_WERKS_ALLOW | — | CHAR | 1 | 0 | Take Account of Plants |
| `CONTRACT_ALLOW` | WRF_POHF_CONTRACT_ALLOW | — | CHAR | 1 | 0 | Take Account of Contracts |
| `PSTYP_ALLOW` | WRF_POHF_PSTYP_ALLOW | — | CHAR | 1 | 0 | Take Account of Item Categories |
| `FIXPO_ALLOW` | WRF_POHF_FIXPO_ALLOW | — | CHAR | 1 | 0 | Take Account of Fixed-Date Purchases Indicator |
| `KEY_ID_ALLOW` | WRF_POHF_KEY_ID_ALLOW | — | CHAR | 1 | 0 | Consider Budget |
| `AUREL_ALLOW` | WRF_POHF_AUREL_ALLOW | — | CHAR | 1 | 0 | Take Account of Alloc. Table Relevance |
| `DELPER_ALLOW` | WRF_POHF_DELPER_ALLOW | — | CHAR | 1 | 0 | Take Account of Dlvy Period |
| `EINDT_ALLOW` | WRF_POHF_EINDT_ALLOW | — | CHAR | 1 | 0 | Take Account of Delivery Date |
| `LTSNR_ALLOW` | WRF_POHF_LTSNR_ALLOW | — | CHAR | 1 | 0 | Include Vendor Subrange |
| `OTB_LEVEL` | WRF_POTB_CHECK_LEVEL | — | CHAR | 1 | 0 | OTB Check Level |
| `OTB_COND_TYPE` | WRF_POTB_COND_TYPE | — | CHAR | 4 | 0 | OTB Condition Type |
| `KEY_ID` | WRF_BUDG_KEY_ID | — | NUMC | 16 | 0 | Unique Number of Budget |
| `OTB_VALUE` | WRF_POTB_VALUE | — | CURR | 17 | 2 | Required Budget |
| `OTB_CURR` | WRF_POTB_CURRENCY | — | CUKY | 5 | 0 | OTB Currency |
| `OTB_RES_VALUE` | WRF_POTB_RES_VALUE | — | CURR | 17 | 2 | Reserved Budget for OTB-Relevant Purchasing Document |
| `OTB_SPEC_VALUE` | WRF_POTB_SPECIAL_VALUE | — | CURR | 17 | 2 | Special Release Budget |
| `SPR_RSN_PROFILE` | WRF_POTB_SPR_RSN_PROFILE | — | CHAR | 4 | 0 | Reason Profile for OTB Special Release |
| `BUDG_TYPE` | WRF_BUDG_TYPE | — | CHAR | 2 | 0 | Budget Type |
| `OTB_STATUS` | WRF_POTB_STATUS | — | CHAR | 1 | 0 | OTB Check Status |
| `OTB_REASON` | WRF_POTB_STATUS_REASON | — | CHAR | 3 | 0 | Reason Indicator for OTB Check Status |
| `CHECK_TYPE` | WRF_BUDG_OTB_CHECK | — | CHAR | 1 | 0 | Type of OTB Check |
| `CON_OTB_REQ` | WRF_POTB_CON_REQ | — | CHAR | 1 | 0 | OTB-Relevant Contract |
| `CON_PREBOOK_LEV` | WRF_POTB_PREBOOK_LEVEL | — | CHAR | 1 | 0 | OTB Indicator Level for Contracts |
| `CON_DISTR_LEV` | WRF_POTB_DISTRIB_LEVEL | — | CHAR | 1 | 0 | Distribution Using Target Value or Item Data |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABSGR` | EKKO | MANDT | T165R |  | |
| `ABSGR` | EKKO | ABSGR | T165R |  | |
| `AUSNR` | EKKO | MANDT | EKKO |  | |
| `AUSNR` | EKKO | AUSNR | EKKO |  | |
| `BSART` | EKKO | BSTYP | T161 |  | |
| `BSART` | EKKO | BSART | T161 |  | |
| `BSART` | EKKO | MANDT | T161 |  | |
| `BUKRS` | EKKO | BUKRS | T001 |  | |
| `BUKRS` | EKKO | MANDT | T001 |  | |
| `EKGRP` | EKKO | MANDT | T024 |  | |
| `EKGRP` | EKKO | EKGRP | T024 |  | |
| `EKORG` | EKKO | MANDT | T024E |  | |
| `EKORG` | EKKO | EKORG | T024E |  | |
| `EXNUM` | EKKO | MANDT | EIKP |  | |
| `EXNUM` | EKKO | EXNUM | EIKP |  | |
| `FRGGR` | EKKO | MANDT | T16FG |  | |
| `FRGGR` | EKKO | FRGGR | T16FG |  | |
| `FRGKE` | EKKO | MANDT | T16FB |  | |
| `FRGKE` | EKKO | FRGKE | T16FB |  | |
| `FRGSX` | EKKO | MANDT | T16FS |  | |
| `FRGSX` | EKKO | FRGGR | T16FS |  | |
| `FRGSX` | EKKO | FRGSX | T16FS |  | |
| `INCO1` | EKKO | MANDT | TINC |  | |
| `INCO1` | EKKO | INCO1 | TINC |  | |
| `KALSM` | EKKO | MANDT | T683 |  | |
| `KALSM` | T681V | KVEWE | T683 |  | |
| `KALSM` | T681A | KAPPL | T683 |  | |
| `KALSM` | EKKO | KALSM | T683 |  | |
| `KONNR` | EKKO | MANDT | EKKO |  | |
| `KONNR` | EKKO | KONNR | EKKO |  | |
| `KUNNR` | EKKO | MANDT | KNA1 |  | |
| `KUNNR` | EKKO | KUNNR | KNA1 |  | |
| `LANDS` | EKKO | LANDS | T005 |  | |
| `LANDS` | EKKO | MANDT | T005 |  | |
| `LBLIF` | EKKO | LBLIF | LFA1 |  | |
| `LBLIF` | EKKO | MANDT | LFA1 |  | |
| `LIFNR` | EKKO | MANDT | LFA1 |  | |
| `LIFNR` | EKKO | LIFNR | LFA1 |  | |
| `LIFRE` | EKKO | MANDT | LFA1 |  | |
| `LIFRE` | EKKO | LIFRE | LFA1 |  | |
| `LLIEF` | EKKO | LLIEF | LFA1 |  | |
| `LLIEF` | EKKO | MANDT | LFA1 |  | |
| `LPONR` | EKKO | EBELN | EKPO |  | |
| `LPONR` | EKKO | LPONR | EKPO |  | |
| `LPONR` | EKKO | MANDT | EKPO |  | |
| `MANDT` | EKKO | MANDT | T000 |  | |
| `OIC_DCITYC` | EKKO | OIC_DCITYC | T005G |  | |
| `OIC_DCITYC` | SYST | MANDT | T005G |  | |
| `OIC_DCITYC` | EKKO | OIC_DLAND1 | T005G |  | |
| `OIC_DCITYC` | EKKO | OIC_DREGIO | T005G |  | |
| `OIC_DCOUNC` | EKKO | OIC_DLAND1 | T005E |  | |
| `OIC_DCOUNC` | EKKO | OIC_DREGIO | T005E |  | |
| `OIC_DCOUNC` | EKKO | OIC_DCOUNC | T005E |  | |
| `OIC_DCOUNC` | SYST | MANDT | T005E |  | |
| `OIC_DLAND1` | SYST | MANDT | T005 |  | |
| `OIC_DLAND1` | EKKO | OIC_DLAND1 | T005 |  | |
| `OIC_DREGIO` | EKKO | OIC_DLAND1 | T005S |  | |
| `OIC_DREGIO` | EKKO | OIC_DREGIO | T005S |  | |
| `OIC_DREGIO` | SYST | MANDT | T005S |  | |
| `OIC_LIFNR` | SYST | MANDT | LFA1 |  | |
| `OIC_LIFNR` | EKKO | OIC_LIFNR | LFA1 |  | |
| `OIC_MOT` | SYST | MANDT | TVTR |  | |
| `OIC_MOT` | EKKO | OIC_MOT | TVTR |  | |
| `OIC_OCITYC` | SYST | MANDT | T005G |  | |
| `OIC_OCITYC` | EKKO | OIC_OLAND1 | T005G |  | |
| `OIC_OCITYC` | EKKO | OIC_OREGIO | T005G |  | |
| `OIC_OCITYC` | EKKO | OIC_OCITYC | T005G |  | |
| `OIC_OCOUNC` | EKKO | OIC_OREGIO | T005E |  | |
| `OIC_OCOUNC` | EKKO | OIC_OCOUNC | T005E |  | |
| `OIC_OCOUNC` | SYST | MANDT | T005E |  | |
| `OIC_OCOUNC` | EKKO | OIC_OLAND1 | T005E |  | |
| `OIC_OLAND1` | SYST | MANDT | T005 |  | |
| `OIC_OLAND1` | EKKO | OIC_OLAND1 | T005 |  | |
| `OIC_OREGIO` | SYST | MANDT | T005S |  | |
| `OIC_OREGIO` | EKKO | OIC_OLAND1 | T005S |  | |
| `OIC_OREGIO` | EKKO | OIC_OREGIO | T005S |  | |
| `RELOC_ID` | SYST | MANDT | /ISDFPS/REL |  | |
| `RELOC_ID` | EKKO | RELOC_ID | /ISDFPS/REL |  | |
| `RELOC_SEQ_ID` | SYST | MANDT | /ISDFPS/RELSEQ |  | |
| `RELOC_SEQ_ID` | EKKO | RELOC_SEQ_ID | /ISDFPS/RELSEQ |  | |
| `RESWK` | EKKO | MANDT | T001W |  | |
| `RESWK` | EKKO | RESWK | T001W |  | |
| `SPRAS` | EKKO | SPRAS | T002 |  | |
| `WAERS` | EKKO | WAERS | TCURC |  | |
| `WAERS` | EKKO | MANDT | TCURC |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AEDAT`, `BSART`, `BSTYP`, `BUKRS`, `EBELN`, `EKGRP`, `EKORG`, `ERNAM`, `INCO1`, `LIFNR`, `LOEKZ`, `STATU`, `WAERS`, `ZTERM`, `ZZVESTINC`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ebeln`

## Join Paths
- `EKKO.EBELN` → `EKPO.EBELN` — PO Header → PO Item
- `EKKO.EBELN` → `EKBE.EBELN` — PO → History

## Programs Using This Table
- `z_create_ekrs.txt`
- `zbacbe034.txt`
- `zissd00072.txt`
- `zissd00079.txt`
- `zissd00081.txt`
- `zissd00086.txt`
- `zissd00096.txt`
- `zissd00097.txt`
- `zissd00108.txt`
- `zissd_get_oa_validity_price.txt`
- `zissd_recover_ekrs_for_ers.txt`
- `zmmpri000.txt`
- `zmmpri001.txt`
- `zmmprsi01.txt`
- `zsdsodl02.txt`
- `zsdsodl06.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_