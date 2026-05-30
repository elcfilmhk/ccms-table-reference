# `EKET`

**Description:** Schedule Line — delivery schedule lines
**Category:** Standard SAP Table
**References:** 16 SELECT statements across 11 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eket/) — validated 2026-05-30, schema v1.0
**Schema fields:** 69 fields | **Data types:** CHAR(27), CUKY(1), CURR(3), DATS(13), DEC(2), INT4(1), NUMC(4), QUAN(10), TIMS(8)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `EINDT` | EINDT | — | DATS | 8 | 0 | Item Delivery Date |
| `SLFDT` | SLFDT | — | DATS | 8 | 0 | Statistics-Relevant Delivery Date |
| `LPEIN` | LPEIN | — | CHAR | 1 | 0 | Category of Delivery Date |
| `MENGE` | ETMEN | — | QUAN | 13 | 3 | Scheduled Quantity |
| `AMENG` | VOMNG | — | QUAN | 13 | 3 | Previous Quantity (Delivery Schedule Lines) |
| `WEMNG` | WEEMG | — | QUAN | 13 | 3 | Quantity of Goods Received |
| `WAMNG` | WAMNG | — | QUAN | 13 | 3 | Issued Quantity |
| `UZEIT` | LZEIT | — | TIMS | 6 | 0 | Delivery Date Time-Spot |
| `BANFN` | BANFN | — | CHAR | 10 | 0 | Purchase Requisition Number |
| `BNFPO` | BNFPO | EBAN | NUMC | 5 | 0 | Item Number of Purchase Requisition |
| `ESTKZ` | ESTKZ | — | CHAR | 1 | 0 | Creation Indicator (Purchase Requisition/Schedule Lines) |
| `QUNUM` | QUNUM | — | CHAR | 10 | 0 | Number of Quota Arrangement |
| `QUPOS` | QUPOS | — | NUMC | 3 | 0 | Quota Arrangement Item |
| `MAHNZ` | MAHNZE | — | DEC | 3 | 0 | No. of Reminders/Expediters for Schedule Line |
| `BEDAT` | ETBDT | — | DATS | 8 | 0 | Order date of schedule line |
| `RSNUM` | RSNUM | — | NUMC | 10 | 0 | Number of Reservation/Dependent Requirement |
| `SERNR` | SERNR | — | CHAR | 8 | 0 | BOM explosion number |
| `FIXKZ` | ETFIX | — | CHAR | 1 | 0 | Schedule Line is &quot;Fixed&quot; |
| `GLMNG` | GLMNG | — | QUAN | 13 | 3 | Quantity Delivered (Stock Transfer) |
| `DABMG` | DABMG | — | QUAN | 13 | 3 | Quantity Reduced (MRP) |
| `CHARG` | CHARG_D | — | CHAR | 10 | 0 | Batch Number |
| `LICHA` | LICHN | — | CHAR | 15 | 0 | Vendor Batch Number |
| `CHKOM` | CHKOM | — | CHAR | 1 | 0 | Components |
| `VERID` | VERID | — | CHAR | 4 | 0 | Production Version |
| `ABART` | MEABART | — | CHAR | 1 | 0 | Scheduling agreement release type |
| `MNG02` | MNG06 | — | QUAN | 13 | 3 | Committed Quantity |
| `DAT01` | DAT05 | — | DATS | 8 | 0 | Committed Date |
| `ALTDT` | ALTDT | — | DATS | 8 | 0 | Previous delivery date |
| `AULWE` | AULWE | VALW | CHAR | 10 | 0 | Route Schedule |
| `MBDAT` | MBDAT | — | DATS | 8 | 0 | Material Staging/Availability Date |
| `MBUHR` | MBUHR | — | TIMS | 6 | 0 | Material Staging Time (Local, Relating to a Plant) |
| `LDDAT` | LDDAT | — | DATS | 8 | 0 | Loading Date |
| `LDUHR` | LDUHR | — | TIMS | 6 | 0 | Loading Time (Local Time Relating to a Shipping Point) |
| `TDDAT` | TDDAT_D | — | DATS | 8 | 0 | Transportation Planning Date |
| `TDUHR` | TDUHR | — | TIMS | 6 | 0 | Transp. Planning Time (Local, Relating to a Shipping Point) |
| `WADAT` | WADAT | — | DATS | 8 | 0 | Goods Issue Date |
| `WAUHR` | WAUHR | — | TIMS | 6 | 0 | Time of Goods Issue (Local, Relating to a Plant) |
| `ELDAT` | ELDAT | — | DATS | 8 | 0 | Goods Receipt End Date |
| `ELUHR` | ELUHR | — | TIMS | 6 | 0 | Goods Receipt End Time (Local, Relating to a Plant) |
| `ANZSN` | ANZSN | — | INT4 | 10 | 0 | Number of serial numbers |
| `NODISP` | NODISP | — | CHAR | 1 | 0 | Ind: Reserv. not applicable to MRP;Purc. req. not created |
| `GEO_ROUTE` | /SPE/DE_ROUTE_ID | — | CHAR | 10 | 0 | Description of a Geographical Route |
| `ROUTE_GTS` | /SPE/DE_ROUTE_GTS_CODE | — | CHAR | 10 | 0 | Route Code for SAP Global Trade Services |
| `GTS_IND` | /SPE/DE_LEG_GTS_CODE | — | CHAR | 2 | 0 | Goods Traffic Type |
| `TSP` | SPDNR | — | CHAR | 10 | 0 | Forwarding agent |
| `CD_LOCNO` | APOLOCNO | — | CHAR | 20 | 0 | Location number in APO |
| `CD_LOCTYPE` | APOLOCTYPE | — | CHAR | 4 | 0 | APO location type |
| `HANDOVERDATE` | HANDOVER_DATE | — | DATS | 8 | 0 | Handover Date at the Handover Location |
| `HANDOVERTIME` | HANDOVER_TIME | — | TIMS | 6 | 0 | Handover time at the handover location |
| `/CWM/MENGE` | /CWM/ETMEN | — | QUAN | 13 | 3 | Schedule Line Quantity in Base/Parallel Unit of Measure |
| `/CWM/DABMG` | /CWM/DABMG | — | QUAN | 13 | 3 | MRP Reduced Quantity in Base/Parallel UoM |
| `/CWM/WEMNG` | /CWM/WEMNG | — | QUAN | 13 | 3 | Goods Receipt Quantity in Base or Parallel Unit of Measure |
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
| `DL_ID` | WRF_PSCD_DL_ID | — | CHAR | 22 | 0 | Date Line ID (GUID) |
| `HANDOVER_DATE` | WRF_PSCD_HANDOVER_DATE | — | DATS | 8 | 0 | Transfer Date |
| `NO_SCEM` | WRF_PSCD_NO_SCEM | — | CHAR | 1 | 0 | Purchase Order Not Transferred to SCEM |
| `DNG_DATE` | WRF_PCTR_DNG_DATE | — | DATS | 8 | 0 | Creation Date of Reminder Message Record |
| `DNG_TIME` | WRF_PCTR_DNG_TIME | — | TIMS | 6 | 0 | Creation Time of Reminder Message Record |
| `CNCL_ANCMNT_DONE` | WRF_PCTR_CNCL_ANCMT_DONE | — | CHAR | 1 | 0 | Cancellation Threat Made |
| `DATESHIFT_NUMBER` | WRF_PCTR_DATESHIFT_NUMBER | — | DEC | 3 | 0 | Number of Current Date Shifts |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `AULWE` | SYST | MANDT | VALW |  | |
| `AULWE` | EKET | AULWE | VALW |  | |
| `BNFPO` | EKET | MANDT | EBAN |  | |
| `BNFPO` | EKET | BANFN | EBAN |  | |
| `BNFPO` | EKET | BNFPO | EBAN |  | |
| `EBELN` | EKET | MANDT | EKKO |  | |
| `EBELN` | EKET | EBELN | EKKO |  | |
| `EBELP` | EKET | EBELN | EKPO |  | |
| `EBELP` | EKET | EBELP | EKPO |  | |
| `EBELP` | EKET | MANDT | EKPO |  | |
| `MANDT` | EKET | MANDT | T000 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zissd00041.txt`
- `zissd00079.txt`
- `zissd00081.txt`
- `zissd00098.txt`
- `zmmpri000.txt`
- `zmmprsi01.txt`
- `zmmprsi13.txt`
- `zsdsoblk1.txt`
- `zsdsocbo1.txt`
- `zsdsodl01.txt`
- `zsdsodl02.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_