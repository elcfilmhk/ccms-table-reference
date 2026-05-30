# `VBAK`

**Description:** Sales Document Header — sales order header
**Category:** Standard SAP Table
**References:** 137 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/vbak/) — validated 2026-05-30, schema v1.0
**Schema fields:** 245 fields | **Data types:** CHAR(191), CUKY(3), CURR(2), DATS(30), DEC(2), INT4(1), NUMC(10), QUAN(2), TIMS(4)

## Key Fields
`KUNNR` | `AUFNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERZET` | ERZET | — | TIMS | 6 | 0 | Entry time |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `ANGDT` | ANGDT_V | — | DATS | 8 | 0 | Quotation/Inquiry is valid from |
| `BNDDT` | BNDDT | — | DATS | 8 | 0 | Date until which bid/quotation is binding (valid-to date) |
| `AUDAT` | AUDAT | — | DATS | 8 | 0 | Document Date (Date Received/Sent) |
| `VBTYP` | VBTYP | — | CHAR | 1 | 0 | SD document category |
| `TRVOG` | TRVOG | — | CHAR | 1 | 0 | Transaction group |
| `AUART` | AUART | TVAK | CHAR | 4 | 0 | Sales Document Type |
| `AUGRU` | AUGRU | TVAU | CHAR | 3 | 0 | Order reason (reason for the business transaction) |
| `GWLDT` | GWLDT | — | DATS | 8 | 0 | Warranty Date |
| `SUBMI` | SUBMI_SD | — | CHAR | 10 | 0 | Collective number (SD) |
| `LIFSK` | LIFSK | TVLS | CHAR | 2 | 0 | Delivery block (document header) |
| `FAKSK` | FAKSK | TVFS | CHAR | 2 | 0 | Billing block in SD document |
| `NETWR` | NETWR_AK | — | CURR | 15 | 2 | Net Value of the Sales Order in Document Currency |
| `WAERK` | WAERK | TCURC | CUKY | 5 | 0 | SD Document Currency |
| `VKORG` | VKORG | TVKO | CHAR | 4 | 0 | Sales Organization |
| `VTWEG` | VTWEG | TVKOV | CHAR | 2 | 0 | Distribution Channel |
| `SPART` | SPART | TVTA | CHAR | 2 | 0 | Division |
| `VKGRP` | VKGRP | TVBVK | CHAR | 3 | 0 | Sales Group |
| `VKBUR` | VKBUR | TVKBZ | CHAR | 4 | 0 | Sales Office |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `GSKST` | GSKST | TGSB | CHAR | 4 | 0 | Business area from cost center |
| `GUEBG` | GUEBG | — | DATS | 8 | 0 | Valid-from date (outline agreements, product proposals) |
| `GUEEN` | GUEEN | — | DATS | 8 | 0 | Valid-to date (outline agreements, product proposals) |
| `KNUMV` | KNUMV | — | CHAR | 10 | 0 | Number of the document condition |
| `VDATU` | EDATU_VBAK | — | DATS | 8 | 0 | Requested delivery date |
| `VPRGR` | PRGRS_VBAK | — | CHAR | 1 | 0 | Proposed date type |
| `AUTLF` | AUTLF | — | CHAR | 1 | 0 | Complete delivery defined for each sales order? |
| `VBKLA` | VBKLA | — | CHAR | 9 | 0 | Original system with release and transaction control |
| `VBKLT` | VBKLT | — | CHAR | 1 | 0 | SD document indicator |
| `KALSM` | KALSMASD | T683 | CHAR | 6 | 0 | Sales and Distribution: Pricing Procedure in Pricing |
| `VSBED` | VSBED | TVSB | CHAR | 2 | 0 | Shipping Conditions |
| `FKARA` | FKARA | TVFK | CHAR | 4 | 0 | Proposed billing type for an order-related billing document |
| `AWAHR` | AWAHR_AK | — | NUMC | 3 | 0 | Sales probability |
| `KTEXT` | KTEXT_V | — | CHAR | 40 | 0 | Search term for product proposal |
| `BSTNK` | BSTNK | — | CHAR | 20 | 0 | Customer purchase order number |
| `BSARK` | BSARK | T176 | CHAR | 4 | 0 | Customer purchase order type |
| `BSTDK` | BSTDK | — | DATS | 8 | 0 | Customer purchase order date |
| `BSTZD` | BSTZD | — | CHAR | 4 | 0 | Purchase order number supplement |
| `IHREZ` | IHREZ | — | CHAR | 12 | 0 | Your Reference |
| `BNAME` | BNAME_V | — | CHAR | 35 | 0 | Name of orderer |
| `TELF1` | TELF1_VP | — | CHAR | 16 | 0 | Telephone Number |
| `MAHZA` | MAHZA | — | DEC | 3 | 0 | Number of contacts from the customer |
| `MAHDT` | MAHDT | — | DATS | 8 | 0 | Last customer contact date |
| `KUNNR` | KUNAG | KNA1 | CHAR | 10 | 0 | Sold-to party |
| `KOSTL` | KOSTL | — | CHAR | 10 | 0 | Cost Center |
| `STAFO` | STAFO | — | CHAR | 6 | 0 | Update group for statistics update |
| `STWAE` | STWAE | TCURC | CUKY | 5 | 0 | Statistics currency |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `KVGR1` | KVGR1 | TVV1 | CHAR | 3 | 0 | Customer group 1 |
| `KVGR2` | KVGR2 | TVV2 | CHAR | 3 | 0 | Customer group 2 |
| `KVGR3` | KVGR3 | TVV3 | CHAR | 3 | 0 | Customer group 3 |
| `KVGR4` | KVGR4 | TVV4 | CHAR | 3 | 0 | Customer group 4 |
| `KVGR5` | KVGR5 | TVV5 | CHAR | 3 | 0 | Customer group 5 |
| `KNUMA` | KNUMA | KONA | CHAR | 10 | 0 | Agreement (various conditions grouped together) |
| `KOKRS` | KOKRS | TKA01 | CHAR | 4 | 0 | Controlling Area |
| `PS_PSP_PNR` | PS_PSP_PNR | PRPS | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `KURST` | KURST | TCURV | CHAR | 4 | 0 | Exchange Rate Type |
| `KKBER` | KKBER | T014 | CHAR | 4 | 0 | Credit control area |
| `KNKLI` | KNKLI | KNA1 | CHAR | 10 | 0 | Customer&#039;s account number with credit limit reference |
| `GRUPP` | GRUPP_CM | — | CHAR | 4 | 0 | Customer Credit Group |
| `SBGRP` | SBGRP_CM | T024B | CHAR | 3 | 0 | Credit representative group for credit management |
| `CTLPC` | CTLPC_CM | T691A | CHAR | 3 | 0 | Credit management: Risk category |
| `CMWAE` | WAERS_CM | TCURC | CUKY | 5 | 0 | Currency key of credit control area |
| `CMFRE` | CMFRE | — | DATS | 8 | 0 | Release date of the document determined by credit management |
| `CMNUP` | CMNUP | — | DATS | 8 | 0 | Date of next credit check of document |
| `CMNGV` | CMNGV | — | DATS | 8 | 0 | Next date |
| `AMTBL` | AMTBL_CM | — | CURR | 15 | 2 | Released credit value of the document |
| `HITYP_PR` | HITYP_PR | THIT | CHAR | 1 | 0 | Hierarchy type for pricing |
| `ABRVW` | ABRVW | TVLV | CHAR | 3 | 0 | Usage Indicator |
| `ABDIS` | ABDIS | — | CHAR | 1 | 0 | MRP for delivery schedule types |
| `VGBEL` | VGBEL | VBUK | CHAR | 10 | 0 | Document number of the reference document |
| `OBJNR` | OBJKO | ONR00 | CHAR | 22 | 0 | Object number at header level |
| `BUKRS_VF` | BUKRS_VF | T001 | CHAR | 4 | 0 | Company code to be billed |
| `TAXK1` | TAXK1_AK | — | CHAR | 1 | 0 | Alternative tax classification |
| `TAXK2` | TAXK2 | — | CHAR | 1 | 0 | Tax classification 2 for customer |
| `TAXK3` | TAXK3 | — | CHAR | 1 | 0 | Tax classification 3 for customer |
| `TAXK4` | TAXK4 | — | CHAR | 1 | 0 | Tax Classification 4 Customer |
| `TAXK5` | TAXK5 | — | CHAR | 1 | 0 | Tax classification 5 for customer |
| `TAXK6` | TAXK6 | — | CHAR | 1 | 0 | Tax classification 6 for customer |
| `TAXK7` | TAXK7 | — | CHAR | 1 | 0 | Tax classification 7 for customer |
| `TAXK8` | TAXK8 | — | CHAR | 1 | 0 | Tax classification 8 for customer |
| `TAXK9` | TAXK9 | — | CHAR | 1 | 0 | Tax classification 9 for customer |
| `XBLNR` | XBLNR_V1 | — | CHAR | 16 | 0 | Reference Document Number |
| `ZUONR` | ORDNR_V | — | CHAR | 18 | 0 | Assignment number |
| `VGTYP` | VBTYP_V | — | CHAR | 1 | 0 | Document category of preceding SD document |
| `KALSM_CH` | KALSMA_CH | T683 | CHAR | 6 | 0 | Search procedure for batch determination |
| `AGRZR` | AGRZR | — | NUMC | 2 | 0 | Accrual period for order-related billing docs.to be accrued |
| `AUFNR` | AUFNR | AUFK | CHAR | 12 | 0 | Order Number |
| `QMNUM` | QMNUM | QMEL | CHAR | 12 | 0 | Notification No |
| `VBELN_GRP` | VBELN_GRP | — | CHAR | 10 | 0 | Mster contract number |
| `SCHEME_GRP` | SCHEME_GRP | TVGRPS | CHAR | 4 | 0 | Referencing requirement: Procedure |
| `ABRUF_PART` | ABRUF_PART | — | CHAR | 1 | 0 | Check partner authorizations |
| `ABHOD` | ABHOD | — | DATS | 8 | 0 | Pick up date |
| `ABHOV` | ABHOZ | — | TIMS | 6 | 0 | Pick up time |
| `ABHOB` | ABHOZ | — | TIMS | 6 | 0 | Pick up time |
| `RPLNR` | RPLNR | FPLA | CHAR | 10 | 0 | Number of payment card plan type |
| `VZEIT` | EZEIT_VBAK | — | TIMS | 6 | 0 | Proposed schedule line time (local with ref. to sales org.) |
| `STCEG_L` | LAND1TX | T005 | CHAR | 3 | 0 | Tax Destination Country |
| `LANDTX` | LANDTX | T005 | CHAR | 3 | 0 | Tax departure country |
| `XEGDR` | XEGDR | — | CHAR | 1 | 0 | Indicator: Triangular deal within the EU ? |
| `ENQUEUE_GRP` | ENQUEUE_GRP | — | CHAR | 1 | 0 | Block master contr. until all lower level contracts updated |
| `DAT_FZAU` | DAT_FZAU | — | DATS | 8 | 0 | Cml delivery order qty date |
| `FMBDAT` | MBDAT | — | DATS | 8 | 0 | Material Staging/Availability Date |
| `VSNMR_V` | VSNMR_V | — | CHAR | 12 | 0 | Sales document version number |
| `HANDLE` | TSEGGUID_VBAK | — | CHAR | 22 | 0 | International unique key for VBAK-VBELN |
| `PROLI` | ADGE_PROLI | TDGC5 | CHAR | 3 | 0 | Dangerous Goods Management Profile in SD Documents |
| `CONT_DG` | ADGE_NCDG | — | CHAR | 1 | 0 | Indicator: Document contains dangerous goods |
| `CRM_GUID` | CHAR70 | — | CHAR | 70 | 0 | Character field, length 70 |
| `UPD_TMSTMP` | TIMESTAMPL | — | DEC | 21 | 7 | UTC Time Stamp in Long Form (YYYYMMDDhhmmssmmmuuun) |
| `MSR_ID` | MSR_PROCESS_ID | — | CHAR | 10 | 0 | Process Identification Number |
| `TM_CTRL_KEY` | TM_CTRL_KEY | — | CHAR | 4 | 0 | Control Key for Document Transfer to TM |
| `HANDOVERLOC` | HANDOVER_LOC | — | CHAR | 10 | 0 | Location for a physical handover of goods |
| `/XLSO/SO_VALD_FM` | DATS | — | DATS | 8 | 0 | Field of type DATS |
| `/XLSO/SO_VALD_TO` | DATS | — | DATS | 8 | 0 | Field of type DATS |
| `/XLSO/PAYMENT_OP` | /XLSO/E_PAY_METHOD | — | CHAR | 2 | 0 | Payment Method |
| `/XLSO/TRANS_CTXT` | /XLSO/E_TRANS_CTXT | — | NUMC | 8 | 0 | Transaction Context GUID |
| `/XLSO/CATALOG_ID` | WMINR | — | CHAR | 10 | 0 | Product catalog number |
| `/XLSO/VARIANT_ID` | WMVARD | — | CHAR | 3 | 0 | Product catalog variant |
| `PSM_BUDAT` | PSM_BUDAT | — | DATS | 8 | 0 | Posting Date in the Document |
| `SWENR` | HB_SWENR | VIOB01 | CHAR | 8 | 0 | Business  Entity Number |
| `SMENR` | HB_SMENR | VIMI01 | CHAR | 8 | 0 | Number of Sales Unit |
| `PHASE` | HB_SPHSE | HBSSPH | CHAR | 11 | 0 | Sales Phase |
| `MTLAUR` | HB_MTLAUR | CHBSNCM | CHAR | 1 | 0 | Marker for Low Income Housing |
| `STAGE` | HB_STAGE | — | INT4 | 10 | 0 | Construction Stage |
| `HB_CONT_REASON` | HB_CONT | HBSCREASON | CHAR | 2 | 0 | Contingency  data |
| `HB_EXPDATE` | HB_EXP | — | DATS | 8 | 0 | Expiration date |
| `HB_RESDATE` | HB_RES | — | DATS | 8 | 0 | Resolution date |
| `MILL_APPL_ID` | MILL_APPL_ID | — | CHAR | 2 | 0 | Application ID Category for Configuration |
| `OID_EXTBOL` | OID_EXTBOL | — | CHAR | 16 | 0 | External bill of lading |
| `OID_MISCDL` | OID_MISCDL | — | CHAR | 16 | 0 | Miscellaneous delivery number |
| `OIDMSG_SHP` | OIDMSG_SHP | — | CHAR | 1 | 0 | Message type for contract restrictions ship-to party |
| `OIDSTS_SHP` | OIDSTS_SHP | — | CHAR | 1 | 0 | Status of contract restriction for ship-to party |
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
| `OIINEX` | OIH_INEX | OIH16 | CHAR | 2 | 0 | Code for internal or external excise duty rate determination |
| `OIISOIL` | OID_ISOIL | — | CHAR | 1 | 0 | Sales order created by IS-Oil: X=Yes   BLANK=No |
| `OIPTRFNC` | OID_PTRFNC | — | CHAR | 2 | 0 | Partner function |
| `OIPARTNR` | OID_PARTNR | — | CHAR | 10 | 0 | Customer name (sold-to party or ship-to party) |
| `OILASTOR` | OID_LASTOR | — | CHAR | 10 | 0 | Last order number |
| `OIDRC` | OIC_DRC | OICDC | CHAR | 5 | 0 | Differential Reference Code (DRC) |
| `OIEXGNUM` | OIA_EXGNUM | OIA01 | CHAR | 10 | 0 | Exchange agreement number |
| `OIEXGTYP` | OIA_EXGTYP | TOIA2 | CHAR | 4 | 0 | Exchange type |
| `OICHEADOFF` | KNRZE | — | CHAR | 10 | 0 | Head office account number (in branch accounts) |
| `OIPBL` | OIF_PBLNR | OIFSPBL | CHAR | 10 | 0 | Business location identifier (IS-Oil MRN) |
| `OIDRESTR` | OIDRESTR | — | CHAR | 1 | 0 | Contract restrictions flag |
| `OIDMSG_PRD` | OIDMSG_PRD | — | CHAR | 1 | 0 | Message type for product with contract restrictions |
| `OIDMSG_QTY` | OIDMSG_QTY | — | CHAR | 1 | 0 | Message type for contract restrictions quantity |
| `OIDMSG_UOM` | OIDMSG_UOM | — | CHAR | 1 | 0 | Message type for contract restrictions unit of measure |
| `OIDMSG_DAT` | OIDMSG_DAT | — | CHAR | 1 | 0 | Message type for contract restrictions validity period |
| `OIDMSG_TRM` | OIDMSG_TRM | — | CHAR | 1 | 0 | Message type for contract restrictions payment terms |
| `OICNTPER` | OID_CNTPER | — | CHAR | 35 | 0 | Contact person |
| `OICNTNTE` | OID_CNTNTE | — | CHAR | 35 | 0 | Contact note |
| `OICNTPHO` | OID_CNTPHO | — | CHAR | 16 | 0 | Contact tel. number |
| `OID_SORTL` | OID_SORTL | — | NUMC | 10 | 0 | Descending sort key for sales orders (converted date) |
| `OID_SORT2` | OID_SORT2 | — | NUMC | 10 | 0 | Descending sort key for sales orders (converted time) |
| `OICFKARTDI` | OICFKARTDI | — | CHAR | 4 | 0 | Differential invoice billing type proposal |
| `OIAEVGTYPE` | OIA_EVTYPE | — | CHAR | 1 | 0 | Evergreen type |
| `OIU_CT_TYPE_CD` | OIU_CT_TYPE_CD | OIU_CM_CTTYP | CHAR | 2 | 0 | Contract Type |
| `OIU_CUST_VEND_CD` | OIU_CUST_VEND_CD | — | CHAR | 1 | 0 | Customer/Vendor Indicator |
| `OIU_APPR_FL` | OIU_APPL_FL | — | CHAR | 1 | 0 | Approval indicator |
| `OIU_APPR_DT` | OIU_APPR_DT | — | DATS | 8 | 0 | Approval Date |
| `OIU_EXEC_DT` | OIU_EXEC_DT | — | DATS | 8 | 0 | Contract Execution Date |
| `OIU_STD_CT_FL` | OIU_STD_CT_FL | — | CHAR | 1 | 0 | Standard Contract Flag |
| `OIU_PREV_CT_NO` | OIU_PREV_CT_NO | — | CHAR | 10 | 0 | Old / Previous Contract Number |
| `OIU_GPLT_COMPANY` | OIU_GPLT_BUKRS | T001 | CHAR | 4 | 0 | Gas Plant Company |
| `OIU_GPLT_VNAME` | OIU_GPLT_VNAME | OIU_DO_JV | CHAR | 6 | 0 | Gas Plant Venture |
| `OIU_GPLT_DOI_NO` | OIU_GPLT_DOI_NO | — | CHAR | 5 | 0 | Gasplant DOI No |
| `OIU_MK_REP_NO` | OIU_MK_REP_NO | — | CHAR | 10 | 0 | Marketing Representative No |
| `OIU_MK_REP_ISQ` | OIU_MK_REP_ISQ_NO | — | CHAR | 2 | 0 | Marketing Representative Interest Sequence No |
| `OIU_DEST_SALE_CD` | OIU_DEST_SALE_CD | — | CHAR | 1 | 0 | Plant Destination Of Product Sale Codes |
| `OIU_LIFE_LSE_FL` | OIU_LIFE_LSE_FL | — | CHAR | 1 | 0 | Life Lease Flag |
| `OIU_INV_NO` | OIU_INV_NO | — | CHAR | 6 | 0 | Contract Invoice Number |
| `OIU_INV_FL` | OIU_INV_FL | — | CHAR | 1 | 0 | Invoice Flag |
| `OIU_OBLIG_DT` | OIU_OBLIG_DT | — | DATS | 8 | 0 | Obligation Date |
| `OIU_DESK_CD` | OIU_DESK_CD | — | CHAR | 3 | 0 | Desk Codes |
| `OIU_EIA_GINA_CD` | OIU_EIA_GINA_CD | — | CHAR | 2 | 0 | Energy Information Agency Report Code |
| `OIU_CT_STATUS_CD` | OIU_CT_STATUS_CD | — | CHAR | 2 | 0 | Contract Status Code |
| `OIU_SPOT_TERM_CD` | OIU_SPOT_TERM_CD | — | CHAR | 1 | 0 | Spot/Term |
| `OIU_STNDEDQ_CD` | OIU_STNDEDQ_CD | — | CHAR | 1 | 0 | Varying/Equ Daily Qu |
| `OIU_IOTR_FL` | OIU_IOTR_FL | — | CHAR | 1 | 0 | Price includes Tax Reimbursement. |
| `OIU_INTRA_INTER` | OIU_INTRA_INTER_CD | — | CHAR | 1 | 0 | Boundary (Intra/Inter) Codes |
| `OIU_EXRES_SPLT` | OIU_EXRES_SPLT_CD | — | CHAR | 1 | 0 | Excess Residue Return (Before/After) Lease Plant Split Code |
| `OIU_EVGN_FL` | OIU_EVGN_FL | — | CHAR | 1 | 0 | Evergreen Flag |
| `OIU_EVGNPD_BAS` | OIU_EVGNPD_BAS_CD | — | CHAR | 2 | 0 | Evergreen Period Basis |
| `OIU_EVGN_PERD_QY` | OIU_EVGN_PERD_QY | — | NUMC | 3 | 0 | Evergreen Period Duration |
| `OIU_PREIM_TM_CD` | OIU_PREIM_TM_CD | — | CHAR | 2 | 0 | Primary Term Basis |
| `OIU_PRIM_TM_QY` | OIU_PRIM_TM_QY | — | NUMC | 3 | 0 | Primary Term Length |
| `OIU_SEC_TM_CD` | OIU_SEC_TM_CD | — | CHAR | 2 | 0 | Secondary Term Basis |
| `OIU_SEC_TM_QY` | OIU_SEC_TM_QY | — | NUMC | 3 | 0 | Secondary Term Length |
| `OIU_EXP_NOTIF_DT` | OIU_EXP_NOTIF_DT | — | DATS | 8 | 0 | Expiration Notification Date |
| `OIU_INTIT_RDT_DT` | OIU_INTIT_RDT_DT | — | DATS | 8 | 0 | Initial Redetermination Date |
| `OIU_NEXT_RDT_DT` | OIU_NEXT_RDT_DT | — | DATS | 8 | 0 | Next redetermination date |
| `OIU_RTC_DT` | OIU_RTC_DT | — | DATS | 8 | 0 | Right to cancel date |
| `OIU_RDT_N_PERD` | OIU_RDT_N_PERD_QY | — | QUAN | 13 | 3 | Re-determination Notification Period (in Days) |
| `OIU_RDT_REFQ_CD` | OIU_RDT_REFQ_CD | — | CHAR | 2 | 0 | Redetermination Frequency Code |
| `OIU_RTF_CD` | OIU_RTF_DT | — | DATS | 8 | 0 | Ratification Date |
| `OIU_IMB_PRVSN_FL` | OIU_IMB_PRVSN_FL | — | CHAR | 1 | 0 | Imbalance Provision Flag |
| `OIU_FFEE_RMB_FL` | OIU_FFEE_RMB_FL | — | CHAR | 1 | 0 | Filing Fee Reimbursement Flag |
| `OIU_FIRM_INTRPT` | OIU_FIRM_INTRPT_CD | — | CHAR | 1 | 0 | Firm/Interruptable Code |
| `OIU_BAL_BAS_CD` | OIU_BAL_BAS_CD | — | CHAR | 1 | 0 | Balancing Basis Code |
| `OIU_PNTY_BAS_CD` | OIU_PNTY_BAS_CD | — | CHAR | 1 | 0 | Penalty Basis Code |
| `OIU_TRANSP_BA` | OIU_TRANSP_BAS_CD | — | CHAR | 1 | 0 | Transportation Basis Code |
| `OIU_DLY_MAX_T_QY` | OIU_DLY_MAX_T_QY | — | QUAN | 13 | 3 | Daily Maximum Transport Quantity |
| `OIU_PRCS_FL` | OIU_PRCS_FL | — | CHAR | 1 | 0 | Processing Flag |
| `OIU_SPR_FL` | OIU_SPR_FL | — | CHAR | 1 | 0 | Separation Flag |
| `OIU_DEHYD_FL` | OIU_DEHYD_FL | — | CHAR | 1 | 0 | Dehydration Flag |
| `OIU_COMPR_FL` | OIU_COMPR_FL | — | CHAR | 1 | 0 | Compression Flag |
| `OIU_PYMT_METH_CD` | OIU_PYMT_METH_CD | — | CHAR | 1 | 0 | Payment Method Code |
| `OIU_CON_MATNR` | OIU_CON_MATNR | — | CHAR | 18 | 0 | Contaminant material |
| `OIU_CON_MAX_QY` | OIU_CON_MAX_QY | — | NUMC | 3 | 0 | Contaminant Percent |
| `OIU_AFFIL_FL` | OIU_AFFIL_FL | — | CHAR | 1 | 0 | Affiliate Flag |
| `OIU_MMS_TYPE_CD` | OIUREP_MMS_2014_SALES_TYPE_CD | OIUREP_SALESTY | CHAR | 4 | 0 | Production:  MMS-2014 - Sales Type Code |
| `OIU_MMS_ETPAY_FL` | OIUREP_MMS_2014_CT_EST_PAY_FL | — | CHAR | 1 | 0 | MMS-2014:  Contracts with Estimated Payment |
| `OIUH_CT_NO` | OIUH_CT_NO | — | CHAR | 6 | 0 | Contract Number |
| `TAS` | FMFG_TAS | — | CHAR | 30 | 0 | Treasury Account Symbol |
| `BETC` | FMFG_BETC | — | CHAR | 10 | 0 | Business Event Type Code |
| `MOD_ALLOW` | FMFG_MOD_ALLOW | — | CHAR | 1 | 0 | Modification Allowed |
| `CANCEL_ALLOW` | FMFG_CANCEL_ALLOW | — | CHAR | 1 | 0 | Cancellation Allowed |
| `PAY_METHOD` | DZWELS | — | CHAR | 10 | 0 | List of the Payment Methods to be Considered |
| `BPN` | FMFG_BPN | T880 | CHAR | 6 | 0 | Business Partner Number |
| `REP_FREQ` | FMFG_REP_FREQ | — | CHAR | 3 | 0 | Reporting Frequency |
| `LOGSYSB` | LOGSYSB | — | CHAR | 10 | 0 | Logical system with which document was created |
| `KALCD` | KALCD | — | CHAR | 6 | 0 | Procedure for Campaign Determination |
| `MULTI` | CMPC_MULT_CAMPAIGN | — | CHAR | 1 | 0 | Multiple Campaigns/Trade Promotions Active Indicator |
| `SPPAYM` | SPPAYM | — | CHAR | 2 | 0 | Payment Form for Special Payment Method |
| `WTYSC_CLM_HDR` | WTYSC_CLM_HDR | — | CHAR | 16 | 0 | Claim header |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABRVW` | VBAK | MANDT | TVLV |  | |
| `ABRVW` | VBAK | ABRVW | TVLV |  | |
| `AUART` | VBAK | MANDT | TVAK |  | |
| `AUART` | VBAK | AUART | TVAK |  | |
| `AUFNR` | VBAK | MANDT | AUFK |  | |
| `AUFNR` | VBAK | AUFNR | AUFK |  | |
| `AUGRU` | VBAK | AUGRU | TVAU |  | |
| `AUGRU` | VBAK | MANDT | TVAU |  | |
| `BPN` | VBAK | MANDT | T880 |  | |
| `BPN` | VBAK | BPN | T880 |  | |
| `BSARK` | VBAK | MANDT | T176 |  | |
| `BSARK` | VBAK | BSARK | T176 |  | |
| `BUKRS_VF` | VBAK | MANDT | T001 |  | |
| `BUKRS_VF` | VBAK | BUKRS_VF | T001 |  | |
| `CMWAE` | VBAK | CMWAE | TCURC |  | |
| `CMWAE` | VBAK | MANDT | TCURC |  | |
| `CTLPC` | VBAK | CTLPC | T691A |  | |
| `CTLPC` | VBAK | KKBER | T691A |  | |
| `CTLPC` | VBAK | MANDT | T691A |  | |
| `FAKSK` | VBAK | MANDT | TVFS |  | |
| `FAKSK` | VBAK | FAKSK | TVFS |  | |
| `FKARA` | VBAK | FKARA | TVFK |  | |
| `FKARA` | VBAK | MANDT | TVFK |  | |
| `GSBER` | VBAK | MANDT | TGSB |  | |
| `GSBER` | VBAK | GSBER | TGSB |  | |
| `GSKST` | VBAK | MANDT | TGSB |  | |
| `GSKST` | VBAK | GSKST | TGSB |  | |
| `HB_CONT_REASON` | * |  | HBSCREASON |  | |
| `HB_CONT_REASON` | VBAK | HB_CONT_REASON | HBSCREASON |  | |
| `HITYP_PR` | VBAK | MANDT | THIT |  | |
| `HITYP_PR` | VBAK | HITYP_PR | THIT |  | |
| `KALSM` | VBAK | MANDT | T683 |  | |
| `KALSM` | T681V | KVEWE | T683 |  | |
| `KALSM` | T681A | KAPPL | T683 |  | |
| `KALSM` | VBAK | KALSM | T683 |  | |
| `KALSM_CH` | VBAK | MANDT | T683 |  | |
| `KALSM_CH` | T681V | KVEWE | T683 |  | |
| `KALSM_CH` | T681A | KAPPL | T683 |  | |
| `KALSM_CH` | VBAK | KALSM_CH | T683 |  | |
| `KKBER` | VBAK | MANDT | T014 |  | |
| `KKBER` | VBAK | KKBER | T014 |  | |
| `KNKLI` | VBAK | MANDT | KNA1 |  | |
| `KNKLI` | VBAK | KNKLI | KNA1 |  | |
| `KNUMA` | VBAK | MANDT | KONA |  | |
| `KNUMA` | VBAK | KNUMA | KONA |  | |
| `KOKRS` | VBAK | KOKRS | TKA01 |  | |
| `KOKRS` | VBAK | MANDT | TKA01 |  | |
| `KUNNR` | VBAK | MANDT | KNA1 |  | |
| `KUNNR` | VBAK | KUNNR | KNA1 |  | |
| `KURST` | VBAK | KURST | TCURV |  | |
| `KURST` | VBAK | MANDT | TCURV |  | |
| `KVGR1` | VBAK | MANDT | TVV1 |  | |
| `KVGR1` | VBAK | KVGR1 | TVV1 |  | |
| `KVGR2` | VBAK | MANDT | TVV2 |  | |
| `KVGR2` | VBAK | KVGR2 | TVV2 |  | |
| `KVGR3` | VBAK | KVGR3 | TVV3 |  | |
| `KVGR3` | VBAK | MANDT | TVV3 |  | |
| `KVGR4` | VBAK | MANDT | TVV4 |  | |
| `KVGR4` | VBAK | KVGR4 | TVV4 |  | |
| `KVGR5` | VBAK | MANDT | TVV5 |  | |
| `KVGR5` | VBAK | KVGR5 | TVV5 |  | |
| `LANDTX` | VBAK | MANDT | T005 |  | |
| `LANDTX` | VBAK | LANDTX | T005 |  | |
| `LIFSK` | VBAK | LIFSK | TVLS |  | |
| `LIFSK` | VBAK | MANDT | TVLS |  | |
| `MANDT` | VBAK | MANDT | T000 |  | |
| `MTLAUR` | * |  | CHBSNCM |  | |
| `MTLAUR` | VBAK | MTLAUR | CHBSNCM |  | |
| `OBJNR` | VBAK | MANDT | ONR00 |  | |
| `OBJNR` | VBAK | OBJNR | ONR00 |  | |
| `OIC_DCITYC` | VBAK | OIC_DCITYC | T005G |  | |
| `OIC_DCITYC` | SYST | MANDT | T005G |  | |
| `OIC_DCITYC` | VBAK | OIC_DLAND1 | T005G |  | |
| `OIC_DCITYC` | VBAK | OIC_DREGIO | T005G |  | |
| `OIC_DCOUNC` | VBAK | OIC_DLAND1 | T005E |  | |
| `OIC_DCOUNC` | VBAK | OIC_DREGIO | T005E |  | |
| `OIC_DCOUNC` | VBAK | OIC_DCOUNC | T005E |  | |
| `OIC_DCOUNC` | SYST | MANDT | T005E |  | |
| `OIC_DLAND1` | VBAK | OIC_DLAND1 | T005 |  | |
| `OIC_DLAND1` | SYST | MANDT | T005 |  | |
| `OIC_DREGIO` | VBAK | OIC_DLAND1 | T005S |  | |
| `OIC_DREGIO` | VBAK | OIC_DREGIO | T005S |  | |
| `OIC_DREGIO` | SYST | MANDT | T005S |  | |
| `OIC_LIFNR` | SYST | MANDT | LFA1 |  | |
| `OIC_LIFNR` | VBAK | OIC_LIFNR | LFA1 |  | |
| `OIC_MOT` | SYST | MANDT | TVTR |  | |
| `OIC_MOT` | VBAK | OIC_MOT | TVTR |  | |
| `OIC_OCITYC` | SYST | MANDT | T005G |  | |
| `OIC_OCITYC` | VBAK | OIC_OLAND1 | T005G |  | |
| `OIC_OCITYC` | VBAK | OIC_OREGIO | T005G |  | |
| `OIC_OCITYC` | VBAK | OIC_OCITYC | T005G |  | |
| `OIC_OCOUNC` | VBAK | OIC_OREGIO | T005E |  | |
| `OIC_OCOUNC` | VBAK | OIC_OCOUNC | T005E |  | |
| `OIC_OCOUNC` | SYST | MANDT | T005E |  | |
| `OIC_OCOUNC` | VBAK | OIC_OLAND1 | T005E |  | |
| `OIC_OLAND1` | SYST | MANDT | T005 |  | |
| `OIC_OLAND1` | VBAK | OIC_OLAND1 | T005 |  | |
| `OIC_OREGIO` | SYST | MANDT | T005S |  | |
| `OIC_OREGIO` | VBAK | OIC_OLAND1 | T005S |  | |
| `OIC_OREGIO` | VBAK | OIC_OREGIO | T005S |  | |
| `OIDRC` | VBAK | MANDT | OICDC |  | |
| `OIDRC` | VBAK | OIDRC | OICDC |  | |
| `OIEXGNUM` | VBAK | MANDT | OIA01 |  | |
| `OIEXGNUM` | VBAK | OIEXGNUM | OIA01 |  | |
| `OIEXGTYP` | VBAK | MANDT | TOIA2 |  | |
| `OIEXGTYP` | VBAK | OIEXGTYP | TOIA2 |  | |
| `OIINEX` | VBAK | OIINEX | OIH16 |  | |
| `OIINEX` | VBAK | MANDT | OIH16 |  | |
| `OIPBL` | VBAK | MANDT | OIFSPBL |  | |
| `OIPBL` | VBAK | OIPBL | OIFSPBL |  | |
| `OIU_CT_TYPE_CD` | VBAK | OIU_CT_TYPE_CD | OIU_CM_CTTYP |  | |
| `OIU_GPLT_COMPANY` | SYST | MANDT | T001 |  | |
| `OIU_GPLT_COMPANY` | VBAK | OIU_GPLT_COMPANY | T001 |  | |
| `OIU_GPLT_VNAME` | VBAK | OIU_GPLT_COMPANY | OIU_DO_JV |  | |
| `OIU_GPLT_VNAME` | VBAK | OIU_GPLT_VNAME | OIU_DO_JV |  | |
| `OIU_GPLT_VNAME` | SYST | MANDT | OIU_DO_JV |  | |
| `OIU_MMS_TYPE_CD` | SYST | MANDT | OIUREP_SALESTY |  | |
| `OIU_MMS_TYPE_CD` | VBAK | OIU_MMS_TYPE_CD | OIUREP_SALESTY |  | |
| `PHASE` | VBAK | PHASE | HBSSPH |  | |
| `PHASE` | * |  | HBSSPH |  | |
| `PHASE` | * |  | HBSSPH |  | |
| `PHASE` | VBAK | SWENR | HBSSPH |  | |
| `PROLI` | VBAK | MANDT | TDGC5 |  | |
| `PROLI` | VBAK | PROLI | TDGC5 |  | |
| `PS_PSP_PNR` | VBAK | MANDT | PRPS |  | |
| `PS_PSP_PNR` | VBAK | PS_PSP_PNR | PRPS |  | |
| `QMNUM` | VBAK | MANDT | QMEL |  | |
| `QMNUM` | VBAK | QMNUM | QMEL |  | |
| `RPLNR` | VBAK | MANDT | FPLA |  | |
| `RPLNR` | VBAK | RPLNR | FPLA |  | |
| `SBGRP` | VBAK | MANDT | T024B |  | |
| `SBGRP` | VBAK | SBGRP | T024B |  | |
| `SBGRP` | VBAK | KKBER | T024B |  | |
| `SCHEME_GRP` | VBAK | MANDT | TVGRPS |  | |
| `SCHEME_GRP` | VBAK | SCHEME_GRP | TVGRPS |  | |
| `SMENR` | VBAK | SWENR | VIMI01 |  | |
| `SMENR` | VBAK | SMENR | VIMI01 |  | |
| `SMENR` | * |  | VIMI01 |  | |
| `SMENR` | * |  | VIMI01 |  | |
| `SPART` | VBAK | MANDT | TVTA |  | |
| `SPART` | VBAK | VKORG | TVTA |  | |
| `SPART` | VBAK | VTWEG | TVTA |  | |
| `SPART` | VBAK | SPART | TVTA |  | |
| `STCEG_L` | VBAK | MANDT | T005 |  | |
| `STCEG_L` | VBAK | STCEG_L | T005 |  | |
| `STWAE` | VBAK | MANDT | TCURC |  | |
| `STWAE` | VBAK | STWAE | TCURC |  | |
| `SWENR` | * |  | VIOB01 |  | |
| `SWENR` | * |  | VIOB01 |  | |
| `SWENR` | VBAK | SWENR | VIOB01 |  | |
| `VBELN` | VBAK | MANDT | VBUK |  | |
| `VBELN` | VBAK | VBELN | VBUK |  | |
| `VGBEL` | VBAK | MANDT | VBUK |  | |
| `VGBEL` | VBAK | VGBEL | VBUK |  | |
| `VKBUR` | VBAK | MANDT | TVKBZ |  | |
| `VKBUR` | VBAK | VKORG | TVKBZ |  | |
| `VKBUR` | VBAK | VTWEG | TVKBZ |  | |
| `VKBUR` | VBAK | SPART | TVKBZ |  | |
| `VKBUR` | VBAK | VKBUR | TVKBZ |  | |
| `VKGRP` | VBAK | MANDT | TVBVK |  | |
| `VKGRP` | VBAK | VKBUR | TVBVK |  | |
| `VKGRP` | VBAK | VKGRP | TVBVK |  | |
| `VKORG` | VBAK | VKORG | TVKO |  | |
| `VKORG` | VBAK | MANDT | TVKO |  | |
| `VSBED` | VBAK | MANDT | TVSB |  | |
| `VSBED` | VBAK | VSBED | TVSB |  | |
| `VTWEG` | VBAK | MANDT | TVKOV |  | |
| `VTWEG` | VBAK | VKORG | TVKOV |  | |
| `VTWEG` | VBAK | VTWEG | TVKOV |  | |
| `WAERK` | VBAK | MANDT | TCURC |  | |
| `WAERK` | VBAK | WAERK | TCURC |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `auart`, `audat`, `bnddt`, `erdat`, `ernam`, `knumv`, `kunnr`, `kvgr3`, `mandt`, `netwr`, `spart`, `vbeln`, `vkbur`, `vkgrp`, `vkorg`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `auart`, `vbeln`

## Join Paths
- `VBAK.VBELN` → `VBAP.VBELN` — Sales Header → Item
- `VBAK.VBELN` → `VBPA.VBELN` — Sales Header → Partner
- `VBAK.VBELN` → `VBKD.VBELN` — Sales Header → Conditions
- `VBAK.VBELN` → `VBRK.VBELN` — Sales → Billing

## Programs Using This Table
- `zisfi0121.txt`
- `zisfi0238_bw.txt`
- `zissd00003.txt`
- `zissd00005.txt`
- `zissd00008.txt`
- `zissd00013.txt`
- `zissd00015.txt`
- `zissd00018.txt`
- `zissd00048.txt`
- `zissd00056.txt`
- `zissd00059.txt`
- `zissd00060.txt`
- `zissd00091.txt`
- `zissd00098.txt`
- `zissd00100.txt`
- `zissd00110.txt`
- `zsdisqry02.txt`
- `zsdisqry04.txt`
- `zsdsoblk1.txt`
- `zsdsopoc1.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_