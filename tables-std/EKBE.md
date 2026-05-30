# `EKBE`

**Description:** Purchasing History — goods receipt/invoice history
**Category:** Standard SAP Table
**References:** 9 SELECT statements across 6 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/ekbe/) — validated 2026-05-30, schema v1.0
**Schema fields:** 82 fields | **Data types:** CHAR(30), CUKY(2), CURR(22), DATS(3), DEC(1), NUMC(9), QUAN(13), TIMS(1), UNIT(1)

## Key Fields
`MATNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BEWTP` | BEWTP | T163B | CHAR | 1 | 0 | PO history category |
| `BWART` | BWART | T156 | CHAR | 3 | 0 | Movement Type (Inventory Management) |
| `BUDAT` | BUDAT | — | DATS | 8 | 0 | Posting Date in the Document |
| `MENGE` | MENGE_D | — | QUAN | 13 | 3 | Quantity |
| `BPMNG` | MENGE_BPR | — | QUAN | 13 | 3 | Quantity in purchase order price unit |
| `DMBTR` | DMBTR | — | CURR | 13 | 2 | Amount in Local Currency |
| `WRBTR` | WRBTR | — | CURR | 13 | 2 | Amount in document currency |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `AREWR` | AREWR | — | CURR | 13 | 2 | GR/IR account clearing value in local currency |
| `WESBS` | WESBS | — | QUAN | 13 | 3 | Goods Receipt Blocked Stock in Order Unit |
| `BPWES` | BPWES | — | QUAN | 13 | 3 | Quantity in GR blocked stock in order price unit |
| `SHKZG` | SHKZG | — | CHAR | 1 | 0 | Debit/Credit Indicator |
| `BWTAR` | BWTAR_D | T149D | CHAR | 10 | 0 | Valuation Type |
| `ELIKZ` | ELIKZ | — | CHAR | 1 | 0 | &quot;Delivery Completed&quot; Indicator |
| `XBLNR` | XBLNR1 | — | CHAR | 16 | 0 | Reference Document Number |
| `LFGJA` | LFBJA | — | NUMC | 4 | 0 | Fiscal Year of a Reference Document |
| `LFBNR` | LFBNR | — | CHAR | 10 | 0 | Document No. of a Reference Document |
| `LFPOS` | LFPOS | — | NUMC | 4 | 0 | Item of a Reference Document |
| `GRUND` | MB_GRBEW | T157D | NUMC | 4 | 0 | Reason for Movement |
| `CPUDT` | CPUDT | — | DATS | 8 | 0 | Day On Which Accounting Document Was Entered |
| `CPUTM` | CPUTM | — | TIMS | 6 | 0 | Time of Entry |
| `REEWR` | REEWR | — | CURR | 13 | 2 | Invoice Value Entered (in Local Currency) |
| `EVERE` | EVERE | T027C | CHAR | 2 | 0 | Compliance with Shipping Instructions |
| `REFWR` | REFWR | — | CURR | 13 | 2 | Invoice value in foreign currency |
| `MATNR` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `WERKS` | WERKS_D | T001W | CHAR | 4 | 0 | Plant |
| `XWSBR` | XWSBR | — | CHAR | 1 | 0 | Reversal of GR allowed for GR-based IV despite invoice |
| `ETENS` | ETENS | — | NUMC | 4 | 0 | Sequential Number of Vendor Confirmation |
| `KNUMV` | KNUMV | — | CHAR | 10 | 0 | Number of the document condition |
| `MWSKZ` | MWSKZ | — | CHAR | 2 | 0 | Tax on sales/purchases code |
| `LSMNG` | LSMNG | — | QUAN | 13 | 3 | Quantity in Unit of Measure from Delivery Note |
| `LSMEH` | LSMEH | T006 | UNIT | 3 | 0 | Unit of Measure From Delivery Note |
| `EMATN` | EMATNR | MARA | CHAR | 18 | 0 | Material Number |
| `AREWW` | AREWW | — | CURR | 13 | 2 | Clearing value on GR/IR clearing account (transac. currency) |
| `HSWAE` | HSWAE | TCURC | CUKY | 5 | 0 | Local currency key |
| `BAMNG` | MENGE_D | — | QUAN | 13 | 3 | Quantity |
| `CHARG` | CHARG_D | — | CHAR | 10 | 0 | Batch Number |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `XWOFF` | XWOFF | — | CHAR | 1 | 0 | Calculation of val. open |
| `XUNPL` | XUNPL | — | CHAR | 1 | 0 | Unplanned Account Assignment from Invoice Verification |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `SRVPOS` | SRVPOS | — | CHAR | 18 | 0 | Service number |
| `PACKNO` | PACKNO_EKBE | — | NUMC | 10 | 0 | Package Number of Service |
| `INTROW` | INTROW_EKBE | — | NUMC | 10 | 0 | Line Number of Service |
| `BEKKN` | BEKKN | — | NUMC | 2 | 0 | Number of PO Account Assignment |
| `LEMIN` | SRVRET | — | CHAR | 1 | 0 | Returns Indicator |
| `AREWB` | AREWB | — | CURR | 13 | 2 | Clearing Value on GR/IR Account in PO Currency |
| `REWRB` | REWRB | — | CURR | 13 | 2 | Invoice Amount in PO Currency |
| `SAPRL` | SAPRL | — | CHAR | 4 | 0 | SAP Release |
| `MENGE_POP` | MENGE_D | — | QUAN | 13 | 3 | Quantity |
| `BPMNG_POP` | MENGE_BPR | — | QUAN | 13 | 3 | Quantity in purchase order price unit |
| `DMBTR_POP` | DMBTR | — | CURR | 13 | 2 | Amount in Local Currency |
| `WRBTR_POP` | WRBTR | — | CURR | 13 | 2 | Amount in document currency |
| `WESBB` | WESBB | — | QUAN | 13 | 3 | Valuated Goods Receipt Blocked Stock in Order Unit |
| `BPWEB` | BPWEB | — | QUAN | 13 | 3 | Quantity in Valuated GR Blocked Stock in Order Price Unit |
| `WEORA` | WEORA | — | CHAR | 1 | 0 | Acceptance At Origin |
| `AREWR_POP` | AREWR | — | CURR | 13 | 2 | GR/IR account clearing value in local currency |
| `KUDIF` | KUDIF | — | CURR | 13 | 2 | Exchange Rate Difference Amount |
| `RETAMT_FC` | RET_AMT_FC | — | CURR | 13 | 2 | Retention Amount in Document Currency |
| `RETAMT_LC` | RET_AMT_LC | — | CURR | 13 | 2 | Retention Amount in Company Code Currency |
| `RETAMTP_FC` | RET_AMT_POST_FC | — | CURR | 13 | 2 | Posted Retention Amount in Document Currency |
| `RETAMTP_LC` | RET_AMT_POST_LC | — | CURR | 13 | 2 | Posted Security Retention Amount in Company Code Currency |
| `XMACC` | XMACC | — | CHAR | 1 | 0 | Multiple Account Assignment |
| `WKURS` | WKURS | — | DEC | 9 | 5 | Exchange Rate |
| `INV_ITEM_ORIGIN` | INV_ITM_ORIGIN | — | CHAR | 1 | 0 | Origin of an Invoice Item |
| `VBELN_ST` | VBELN_VL | — | CHAR | 10 | 0 | Delivery |
| `VBELP_ST` | POSNR_VL | — | NUMC | 6 | 0 | Delivery Item |
| `FRBNR` | FRBNR1 | — | CHAR | 16 | 0 | Number of Bill of Lading at Time of Goods Receipt |
| `OIA_IPMVAT` | OIA_IPMVAT | — | CHAR | 1 | 0 | VAT on internally-posted material |
| `OIVATH` | DMBTR | — | CURR | 13 | 2 | Amount in Local Currency |
| `OIVATF` | WRBTR | — | CURR | 13 | 2 | Amount in document currency |
| `OIIMATV` | OIA_IMATV | — | CURR | 13 | 2 | Internal material value |
| `OIMATCYC` | OIA_MATCYC | — | NUMC | 1 | 0 | Invoicing cycle for purchase material costs |
| `OITAXVAL` | OIH_TAXVAL | — | CURR | 13 | 2 | Excise duty value in material inventory account |
| `OITAXCON` | OIH_TAXCON | — | CURR | 13 | 2 | Excise duty tax from pricing conditions |
| `OIEDCL` | OIH_EDCL | — | CURR | 13 | 2 | Excise duty clearing value |
| `ET_UPD` | ET_UPD1 | — | CHAR | 1 | 0 | Procedure for Updating the Schedule Line Quantity |
| `/CWM/BAMNG` | /CWM/BAMNG | — | QUAN | 13 | 3 | Quantity in Parallel Unit of Measure |
| `/CWM/WESBS` | /CWM/WESBS | — | QUAN | 13 | 3 | Goods Receipt Blocked Stock in Base/Parallel Unit of Measure |
| `/CWM/TY2TQ` | /CWM/TY2TQ | — | CHAR | 1 | 0 | Type of Parallel Unit of Measure |
| `/CWM/WESBB` | /CWM/WESBB | — | QUAN | 13 | 3 | Val. Goods Receipt Blocked Stock in Basis or Parallel UoM |
| `J_SC_DIE_COMP_F` | /SAPNEA/J_SC_DIE_COMP_F | — | CHAR | 1 | 0 | Depreciation completion flag |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `BEWTP` | EKBE | MANDT | T163B |  | |
| `BEWTP` | EKBE | BEWTP | T163B |  | |
| `BWART` | EKBE | MANDT | T156 |  | |
| `BWART` | EKBE | BWART | T156 |  | |
| `BWTAR` | EKBE | MANDT | T149D |  | |
| `BWTAR` | EKBE | BWTAR | T149D |  | |
| `EBELN` | EKBE | MANDT | EKKO |  | |
| `EBELN` | EKBE | EBELN | EKKO |  | |
| `EBELP` | EKBE | MANDT | EKPO |  | |
| `EBELP` | EKBE | EBELN | EKPO |  | |
| `EBELP` | EKBE | EBELP | EKPO |  | |
| `EMATN` | EKBE | EMATN | MARA |  | |
| `EMATN` | EKBE | MANDT | MARA |  | |
| `EVERE` | EKBE | EVERE | T027C |  | |
| `EVERE` | EKBE | MANDT | T027C |  | |
| `EVERE` | T027A | EVERS | T027C |  | |
| `GRUND` | EKBE | BWART | T157D |  | |
| `GRUND` | EKBE | GRUND | T157D |  | |
| `GRUND` | EKBE | MANDT | T157D |  | |
| `HSWAE` | EKBE | HSWAE | TCURC |  | |
| `HSWAE` | EKBE | MANDT | TCURC |  | |
| `LSMEH` | EKBE | MANDT | T006 |  | |
| `LSMEH` | EKBE | LSMEH | T006 |  | |
| `MANDT` | EKBE | MANDT | T000 |  | |
| `MATNR` | EKBE | MANDT | MARA |  | |
| `MATNR` | EKBE | MATNR | MARA |  | |
| `WAERS` | EKBE | MANDT | TCURC |  | |
| `WAERS` | EKBE | WAERS | TCURC |  | |
| `WERKS` | EKBE | WERKS | T001W |  | |
| `WERKS` | EKBE | MANDT | T001W |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `ziscs0120.txt`
- `zissd00027.txt`
- `zissd00038.txt`
- `zissd_recover_ekrs_for_ers.txt`
- `zmmpri001.txt`
- `zrepmir7.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_