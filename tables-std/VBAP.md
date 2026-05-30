# `VBAP`

**Description:** Sales Document Item — sales order item
**Category:** Standard SAP Table
**References:** 105 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/vbap/) — validated 2026-05-30, schema v1.0
**Schema fields:** 351 fields | **Data types:** CHAR(252), CUKY(1), CURR(13), DATS(9), DEC(17), FLTP(3), INT4(1), NUMC(31), QUAN(15), TIMS(2), UNIT(7)

## Key Fields
`MATNR` | `AUFNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `MATNR` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `MATWA` | MATWA | MARA | CHAR | 18 | 0 | Material entered |
| `PMATN` | PMATN | MARA | CHAR | 18 | 0 | Pricing Reference Material |
| `CHARG` | CHARG_D | MCHA | CHAR | 10 | 0 | Batch Number |
| `MATKL` | MATKL | T023 | CHAR | 9 | 0 | Material Group |
| `ARKTX` | ARKTX | — | CHAR | 40 | 0 | Short text for sales order item |
| `PSTYV` | PSTYV | TVPT | CHAR | 4 | 0 | Sales document item category |
| `POSAR` | POSAR | — | CHAR | 1 | 0 | Item type |
| `LFREL` | LFREL_AP | — | CHAR | 1 | 0 | Item is relevant for delivery |
| `FKREL` | FKREL | — | CHAR | 1 | 0 | Relevant for Billing |
| `UEPOS` | UEPOS | — | NUMC | 6 | 0 | Higher-level item in bill of material structures |
| `GRPOS` | GRPOS | — | NUMC | 6 | 0 | Item for which this item is an alternative |
| `ABGRU` | ABGRU_VA | TVAG | CHAR | 2 | 0 | Reason for rejection of quotations and sales orders |
| `PRODH` | PRODH_D | T179 | CHAR | 18 | 0 | Product hierarchy |
| `ZWERT` | DZWERT | — | CURR | 13 | 2 | Target Value for Outline Agreement in Document Currency |
| `ZMENG` | DZMENG | — | QUAN | 13 | 3 | Target quantity in sales units |
| `ZIEME` | DZIEME | T006 | UNIT | 3 | 0 | Target quantity UoM |
| `UMZIZ` | UMZIZ | — | DEC | 5 | 0 | Factor for converting sales units to base units (target qty) |
| `UMZIN` | UMZIN | — | DEC | 5 | 0 | Factor for converting sales units to base units (target qty) |
| `MEINS` | MEINS | T006 | UNIT | 3 | 0 | Base Unit of Measure |
| `SMENG` | SMENG | — | QUAN | 13 | 3 | Scale quantity in base unit of measure |
| `ABLFZ` | ABLFZ | — | QUAN | 13 | 3 | Rounding quantity for delivery |
| `ABDAT` | ABDAT | — | DATS | 8 | 0 | Reconciliation Date for Agreed Cumulative Quantity |
| `ABSFZ` | ABSFZ | — | QUAN | 13 | 3 | Allowed deviation in quantity (absolute) |
| `POSEX` | POSEX | — | CHAR | 6 | 0 | Item Number of the Underlying Purchase Order |
| `KDMAT` | MATNR_KU | — | CHAR | 35 | 0 | Material Number Used by Customer |
| `KBVER` | KBVER | — | DEC | 3 | 0 | Allowed deviation in quantity (in percent) |
| `KEVER` | KEVER | — | DEC | 3 | 0 | Days by which the quantity can be shifted |
| `VKGRU` | VKGRU | TVRMAVK | CHAR | 3 | 0 | Repair Processing: Classification of Items |
| `VKAUS` | ABRVW | TVLV | CHAR | 3 | 0 | Usage Indicator |
| `GRKOR` | GRKOR | — | NUMC | 3 | 0 | Delivery group (items are delivered together) |
| `FMENG` | FMENG | — | CHAR | 1 | 0 | Quantity is Fixed |
| `UEBTK` | UEBTK_V | — | CHAR | 1 | 0 | Unlimited overdelivery allowed |
| `UEBTO` | UEBTO | — | DEC | 3 | 1 | Overdelivery Tolerance Limit |
| `UNTTO` | UNTTO | — | DEC | 3 | 1 | Underdelivery Tolerance Limit |
| `FAKSP` | FAKSP_AP | TVFS | CHAR | 2 | 0 | Billing block for item |
| `ATPKZ` | ATPKZ | — | CHAR | 1 | 0 | Replacement part |
| `RKFKF` | RKFKF | — | CHAR | 1 | 0 | Method of billing for CO/PPC orders |
| `SPART` | SPART | TSPA | CHAR | 2 | 0 | Division |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `NETWR` | NETWR_AP | — | CURR | 15 | 2 | Net value of the order item in document currency |
| `WAERK` | WAERK | TCURC | CUKY | 5 | 0 | SD Document Currency |
| `ANTLF` | ANTLF | — | DEC | 1 | 0 | Maximum Number of Partial Deliveries Allowed Per Item |
| `KZTLF` | KZTLF | — | CHAR | 1 | 0 | Partial delivery at item level |
| `CHSPL` | CHSPL | — | CHAR | 1 | 0 | Batch split allowed |
| `KWMENG` | KWMENG | — | QUAN | 15 | 3 | Cumulative Order Quantity in Sales Units |
| `LSMENG` | LSMENG | — | QUAN | 15 | 3 | Cumulative required delivery qty (all dlv-relev.sched.lines) |
| `KBMENG` | KBMENG | — | QUAN | 15 | 3 | Cumulative confirmed quantity in sales unit |
| `KLMENG` | KLMENG | — | QUAN | 15 | 3 | Cumulative confirmed quantity in base unit |
| `VRKME` | VRKME | T006 | UNIT | 3 | 0 | Sales unit |
| `UMVKZ` | UMVKZ | — | DEC | 5 | 0 | Numerator (factor) for conversion of sales quantity into SKU |
| `UMVKN` | UMVKN | — | DEC | 5 | 0 | Denominator (Divisor) for Conversion of Sales Qty into SKU |
| `BRGEW` | BRGEW_AP | — | QUAN | 15 | 3 | Gross Weight of the Item |
| `NTGEW` | NTGEW_AP | — | QUAN | 15 | 3 | Net Weight of the Item |
| `GEWEI` | GEWEI | T006 | UNIT | 3 | 0 | Weight Unit |
| `VOLUM` | VOLUM_AP | — | QUAN | 15 | 3 | Volume of the item |
| `VOLEH` | VOLEH | T006 | UNIT | 3 | 0 | Volume unit |
| `VBELV` | VBELV | VBUK | CHAR | 10 | 0 | Originating document |
| `POSNV` | POSNV | VBUP | NUMC | 6 | 0 | Originating item |
| `VGBEL` | VGBEL | VBUK | CHAR | 10 | 0 | Document number of the reference document |
| `VGPOS` | VGPOS | VBUP | NUMC | 6 | 0 | Item number of the reference item |
| `VOREF` | VOREF | — | CHAR | 1 | 0 | Complete reference indicator |
| `UPFLU` | UPFLV | — | CHAR | 1 | 0 | Update indicator for sales document document flow |
| `ERLRE` | ERLRE | — | CHAR | 1 | 0 | Completion rule for quotation / contract |
| `LPRIO` | LPRIO | TPRIO | NUMC | 2 | 0 | Delivery Priority |
| `WERKS` | WERKS_EXT | — | CHAR | 4 | 0 | Plant (Own or External) |
| `LGORT` | LGORT_D | T001L | CHAR | 4 | 0 | Storage Location |
| `VSTEL` | VSTEL | TVST | CHAR | 4 | 0 | Shipping Point/Receiving Point |
| `ROUTE` | ROUTE | TVRO | CHAR | 6 | 0 | Route |
| `STKEY` | STKEY | — | CHAR | 1 | 0 | Origin of the bill of material |
| `STDAT` | STDAT | — | DATS | 8 | 0 | Key date of the bill of material |
| `STLNR` | STNUM | — | CHAR | 8 | 0 | Bill of material |
| `STPOS` | STPOS_VBAP | — | DEC | 5 | 0 | Bill of material item number VBAP not used |
| `AWAHR` | AWAHR | — | NUMC | 3 | 0 | Order probability of the item |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `ERZET` | ERZET | — | TIMS | 6 | 0 | Entry time |
| `TAXM1` | TAXMT | — | CHAR | 1 | 0 | Tax classification material |
| `TAXM2` | TAXMT | — | CHAR | 1 | 0 | Tax classification material |
| `TAXM3` | TAXMT | — | CHAR | 1 | 0 | Tax classification material |
| `TAXM4` | TAXMT | — | CHAR | 1 | 0 | Tax classification material |
| `TAXM5` | TAXMT | — | CHAR | 1 | 0 | Tax classification material |
| `TAXM6` | TAXMT | — | CHAR | 1 | 0 | Tax classification material |
| `TAXM7` | TAXMT | — | CHAR | 1 | 0 | Tax classification material |
| `TAXM8` | TAXMT | — | CHAR | 1 | 0 | Tax classification material |
| `TAXM9` | TAXMT | — | CHAR | 1 | 0 | Tax classification material |
| `VBEAF` | VBEAF | — | DEC | 5 | 2 | Fixed shipping processing time in days (= setup time) |
| `VBEAV` | VBEAV | — | DEC | 5 | 2 | Variable shipping processing time in days |
| `VGREF` | VGREF | — | CHAR | 1 | 0 | Preceding document has resulted from reference |
| `NETPR` | NETPR | — | CURR | 11 | 2 | Net price |
| `KPEIN` | KPEIN | — | DEC | 5 | 0 | Condition pricing unit |
| `KMEIN` | KMEIN | T006 | UNIT | 3 | 0 | Condition unit |
| `SHKZG` | SHKZG_VA | — | CHAR | 1 | 0 | Returns Item |
| `SKTOF` | SKTOF | — | CHAR | 1 | 0 | Cash discount indicator |
| `MTVFP` | MTVFP | TMVF | CHAR | 2 | 0 | Checking Group for Availability Check |
| `SUMBD` | SUMBD | — | CHAR | 1 | 0 | Summing up of requirements |
| `KONDM` | KONDM | T178 | CHAR | 2 | 0 | Material Pricing Group |
| `KTGRM` | KTGRM | TVKM | CHAR | 2 | 0 | Account assignment group for this material |
| `BONUS` | BONUS | TVBO | CHAR | 2 | 0 | Volume rebate group |
| `PROVG` | PROVG | TVPR | CHAR | 2 | 0 | Commission group |
| `EANNR` | EANNR | — | CHAR | 13 | 0 | European Article Number (EAN) - obsolete!!!!! |
| `PRSOK` | PRSOK | — | CHAR | 1 | 0 | Pricing is OK |
| `BWTAR` | BWTAR_D | T149D | CHAR | 10 | 0 | Valuation Type |
| `BWTEX` | BWTEX | — | CHAR | 1 | 0 | Indicator: Separate valuation |
| `XCHPF` | XCHPF | — | CHAR | 1 | 0 | Batch management requirement indicator |
| `XCHAR` | XCHAR | — | CHAR | 1 | 0 | Batch management indicator (internal) |
| `LFMNG` | MINLF | — | QUAN | 13 | 3 | Minimum delivery quantity in delivery note processing |
| `STAFO` | STAFO | — | CHAR | 6 | 0 | Update group for statistics update |
| `WAVWR` | WAVWR | — | CURR | 13 | 2 | Cost in document currency |
| `KZWI1` | KZWI1 | — | CURR | 13 | 2 | Subtotal 1 from pricing procedure for condition |
| `KZWI2` | KZWI2 | — | CURR | 13 | 2 | Subtotal 2 from pricing procedure for condition |
| `KZWI3` | KZWI3 | — | CURR | 13 | 2 | Subtotal 3 from pricing procedure for condition |
| `KZWI4` | KZWI4 | — | CURR | 13 | 2 | Subtotal 4 from pricing procedure for condition |
| `KZWI5` | KZWI5 | — | CURR | 13 | 2 | Subtotal 5 from pricing procedure for condition |
| `KZWI6` | KZWI6 | — | CURR | 13 | 2 | Subtotal 6 from pricing procedure for condition |
| `STCUR` | STCUR_AP | — | DEC | 9 | 5 | Exchange rate for statistics (Exch.rate at time of creation) |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `EAN11` | EAN11 | — | CHAR | 18 | 0 | International Article Number (EAN/UPC) |
| `FIXMG` | FIXMG | — | CHAR | 1 | 0 | Delivery date and quantity fixed |
| `PRCTR` | PRCTR | — | CHAR | 10 | 0 | Profit Center |
| `MVGR1` | MVGR1 | TVM1 | CHAR | 3 | 0 | Material group 1 |
| `MVGR2` | MVGR2 | TVM2 | CHAR | 3 | 0 | Material group 2 |
| `MVGR3` | MVGR3 | TVM3 | CHAR | 3 | 0 | Material group 3 |
| `MVGR4` | MVGR4 | TVM4 | CHAR | 3 | 0 | Material group 4 |
| `MVGR5` | MVGR5 | TVM5 | CHAR | 3 | 0 | Material group 5 |
| `KMPMG` | KMPMG | — | QUAN | 13 | 3 | Component quantity |
| `SUGRD` | SUGRD | TVSU | CHAR | 4 | 0 | Reason for material substitution |
| `SOBKZ` | SOBKZ | T148 | CHAR | 1 | 0 | Special Stock Indicator |
| `VPZUO` | VPZUO | — | CHAR | 1 | 0 | Allocation Indicator |
| `PAOBJNR` | RKEOBJNR | — | NUMC | 10 | 0 | Profitability Segment Number (CO-PA) |
| `PS_PSP_PNR` | PS_PSP_PNR | PRPS | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `AUFNR` | AUFNR | AUFK | CHAR | 12 | 0 | Order Number |
| `VPMAT` | VPMAT | MARA | CHAR | 18 | 0 | Planning material |
| `VPWRK` | VPWRK | T001W | CHAR | 4 | 0 | Planning plant |
| `PRBME` | PRBME | T006 | UNIT | 3 | 0 | Base unit of measure for product group |
| `UMREF` | UMREFF | — | FLTP | 16 | 16 | Conversion factor: quantities |
| `KNTTP` | KNTTP | T163K | CHAR | 1 | 0 | Account Assignment Category |
| `KZVBR` | KZVBR | — | CHAR | 1 | 0 | Consumption Posting |
| `SERNR` | SERNR | SNUM | CHAR | 8 | 0 | BOM explosion number |
| `OBJNR` | OBJPO | ONR00 | CHAR | 22 | 0 | Object number at item level |
| `ABGRS` | ABGR_SCHL | TKKAA | CHAR | 6 | 0 | Results Analysis Key |
| `BEDAE` | BEDAE | T459A | CHAR | 4 | 0 | Requirements type |
| `CMPRE` | CMPRE | — | CURR | 11 | 2 | Item credit price |
| `CMTFG` | CMTFG | — | CHAR | 1 | 0 | ID for partial release of order item, credit block |
| `CMPNT` | CMPNT | — | CHAR | 1 | 0 | ID: Item with active credit function / relevant for credit |
| `CMKUA` | CMKUA | — | DEC | 9 | 5 | Credit data exchange rate for requested delivery date |
| `CUOBJ` | CUOBJ_VA | — | NUMC | 18 | 0 | Configuration |
| `CUOBJ_CH` | CUOBJ_CH | — | NUMC | 18 | 0 | Internal object number of the batch classification |
| `CEPOK` | CEPOK | — | CHAR | 1 | 0 | Status expected price |
| `KOUPD` | KOUPD | — | CHAR | 1 | 0 | Condition update |
| `SERAIL` | SERAIL | T377P | CHAR | 4 | 0 | Serial Number Profile |
| `ANZSN` | ANZSN | — | INT4 | 10 | 0 | Number of serial numbers |
| `NACHL` | NACHL | — | CHAR | 1 | 0 | Customer has not posted goods receipt |
| `MAGRV` | MAGRV | TVEGR | CHAR | 4 | 0 | Material Group: Packaging Materials |
| `MPROK` | MPROK | — | CHAR | 1 | 0 | Status manual price change |
| `VGTYP` | VBTYP_V | — | CHAR | 1 | 0 | Document category of preceding SD document |
| `PROSA` | PROSA | — | CHAR | 1 | 0 | ID for material determination |
| `UEPVW` | UEPVW | — | CHAR | 1 | 0 | ID for higher-level item usage |
| `KALNR` | CK_KALNR | — | NUMC | 12 | 0 | Cost Estimate Number for Cost Est. w/o Qty Structure |
| `KLVAR` | CK_KLVAR | — | CHAR | 4 | 0 | Costing Variant |
| `SPOSN` | SPOSN | — | CHAR | 4 | 0 | BOM Item Number |
| `KOWRR` | KOWRR | — | CHAR | 1 | 0 | Statistical values |
| `STADAT` | STADAT | — | DATS | 8 | 0 | Statistics date |
| `EXART` | EXART | T605 | CHAR | 2 | 0 | Business Transaction Type for Foreign Trade |
| `PREFE` | PREFE | — | CHAR | 1 | 0 | Preference indicator in export/import |
| `KNUMH` | KNUMH_CH | — | CHAR | 10 | 0 | Number of condition record from batch determination |
| `CLINT` | CLINT | KLAH | NUMC | 10 | 0 | Internal Class Number |
| `CHMVS` | CHMVS | — | NUMC | 3 | 0 | Batches: Exit to quantity proposal |
| `STLTY` | STLTY | — | CHAR | 1 | 0 | BOM category |
| `STLKN` | STLKN | — | NUMC | 8 | 0 | BOM item node number |
| `STPOZ` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `STMAN` | CUINK | — | CHAR | 1 | 0 | Inconsistent configuration |
| `ZSCHL_K` | AUFZSCHL | — | CHAR | 6 | 0 | Overhead key |
| `KALSM_K` | AUFKALSM | T683 | CHAR | 6 | 0 | Costing Sheet |
| `KALVAR` | CK_KLVAR | TCK03 | CHAR | 4 | 0 | Costing Variant |
| `KOSCH` | KOSCH | T190S | CHAR | 18 | 0 | Product allocation determination procedure |
| `UPMAT` | UPMAT | MARA | CHAR | 18 | 0 | Pricing reference material of main item |
| `UKONM` | UKONM | T178 | CHAR | 2 | 0 | Material pricing group of main item |
| `MFRGR` | MFRGR | TMFG | CHAR | 8 | 0 | Material freight group |
| `PLAVO` | PLAVO | TVZP | CHAR | 4 | 0 | Planning delivery schedule instruction |
| `KANNR` | KANNR | — | CHAR | 35 | 0 | KANBAN/sequence number |
| `CMPRE_FLT` | CMPRE_FLT | — | FLTP | 16 | 16 | Item credit price |
| `ABFOR` | ABSFORM_CM | T691K | CHAR | 2 | 0 | Form of payment guarantee |
| `ABGES` | ABGES_CM | — | FLTP | 16 | 16 | Guaranteed (factor between 0 and 1) |
| `J_1BCFOP` | J_1BCFOP | J_1BAG | CHAR | 10 | 0 | CFOP Code and Extension |
| `J_1BTAXLW1` | J_1BTAXLW1 | J_1BATL1 | CHAR | 3 | 0 | Tax law: ICMS |
| `J_1BTAXLW2` | J_1BTAXLW2 | J_1BATL2 | CHAR | 3 | 0 | Tax law: IPI |
| `J_1BTXSDC` | J_1BTXSDC_ | J_1BTXSDC | CHAR | 2 | 0 | SD tax code |
| `WKTNR` | WKTNR | VBUK | CHAR | 10 | 0 | Value contract no. |
| `WKTPS` | WKTPS | VBUP | NUMC | 6 | 0 | Value contract item |
| `SKOPF` | W_SORTK | WSOH | CHAR | 18 | 0 | Assortment module |
| `KZBWS` | KZBWS | — | CHAR | 1 | 0 | Valuation of Special Stock |
| `WGRU1` | WGRU_HIE1 | — | CHAR | 18 | 0 | Material group hierarchy 1 |
| `WGRU2` | WGRU_HIE2 | — | CHAR | 18 | 0 | Material group hierarchy 2 |
| `KNUMA_PI` | KNUMA_PI | KONA | CHAR | 10 | 0 | Promotion |
| `KNUMA_AG` | KNUMA_AG | KONA | CHAR | 10 | 0 | Sales deal |
| `KZFME` | KZFME | — | CHAR | 1 | 0 | ID: Leading unit of measure for completing a transaction |
| `LSTANR` | LSTANR | — | CHAR | 1 | 0 | Free goods delivery control |
| `TECHS` | TECHS | — | CHAR | 12 | 0 | Parameter Variant/Standard Variant |
| `MWSBP` | MWSBP | — | CURR | 13 | 2 | Tax amount in document currency |
| `BERID` | BERID | — | CHAR | 10 | 0 | MRP Area |
| `PCTRF` | PCTRF | — | CHAR | 10 | 0 | Profit Center for Billing |
| `LOGSYS_EXT` | LOGSYS | — | CHAR | 10 | 0 | Logical system |
| `J_1BTAXLW3` | J_1BTAXLW3 | J_1BATL3 | CHAR | 3 | 0 | ISS Tax Law |
| `J_1BTAXLW4` | J_1BTAXLW4 | J_1BATL4A | CHAR | 3 | 0 | COFINS Tax Law |
| `J_1BTAXLW5` | J_1BTAXLW5 | J_1BATL5 | CHAR | 3 | 0 | PIS Tax Law |
| `STOCKLOC` | STOCKLOC | — | CHAR | 20 | 0 | First Inventory-Managing Location |
| `SLOCTYPE` | SLOCTYPE | — | CHAR | 4 | 0 | Type of First Inventory-Managing Location |
| `MSR_RET_REASON` | MSR_RETURNS_REASON | MSR_C_RET_REASON | CHAR | 3 | 0 | Return Reason |
| `MSR_REFUND_CODE` | MSR_RETURNS_REFUND_CODE | MSR_C_RET_REFUND | CHAR | 3 | 0 | Returns Refund Code |
| `MSR_APPROV_BLOCK` | MSR_APPROVAL_BLOCK | — | CHAR | 1 | 0 | Approval Block |
| `NRAB_KNUMH` | KNUMH | — | CHAR | 10 | 0 | Condition record number |
| `TRMRISK_RELEVANT` | SLS_TRM_RISK_RELEVANCY | — | CHAR | 2 | 0 | Risk Relevancy in Sales |
| `HANDOVERLOC` | HANDOVER_LOC | — | CHAR | 10 | 0 | Location for a physical handover of goods |
| `HANDOVERDATE` | HANDOVER_DATE | — | DATS | 8 | 0 | Handover Date at the Handover Location |
| `HANDOVERTIME` | HANDOVER_TIME | — | TIMS | 6 | 0 | Handover time at the handover location |
| `Z_PRS_OFFSHORE` | Z_PRS_OFFSHORE | — | CHAR | 1 | 0 | Professional Services: Delivery Type |
| `Z_PRS_BILL_FLAG` | Z_PRS_BILLABLE_FLAG | — | CHAR | 1 | 0 | Professional Services: Billable/Non-Billable |
| `Z_PRS_COUNTRY` | LAND1 | — | CHAR | 3 | 0 | Country Key |
| `Z_PRS_CHARGELEVL` | Z_PRS_CHARGELEVEL | — | CHAR | 2 | 0 | Professional Services: Charge Level |
| `TC_AUT_DET` | J_1BTC_AUT_DET | — | CHAR | 2 | 0 | Tax Code Automatically Determined |
| `MANUAL_TC_REASON` | J_1BMANUAL_TC_REASON | — | CHAR | 2 | 0 | Manual Tax Code Reason |
| `FISCAL_INCENTIVE` | J_1BFISCAL_INCENTIVE_CODE | — | CHAR | 4 | 0 | Tax Incentive Type |
| `TAX_SUBJECT_ST` | J_1BTC_TAX_SUBJECT_ST | — | CHAR | 1 | 0 | TAX_SUBJECT_ST |
| `FISCAL_INCENTIVE_ID` | J_1BFISCAL_INCENTIVE_ID_SD | — | CHAR | 4 | 0 | Incentive ID |
| `SPCSTO` | J_1BSPCSTO_SD | — | NUMC | 2 | 0 | Nota Fiscal Special Case for CFOP Determination |
| `/BEV1/SRFUND` | /BEV1/SRBEFUND | — | CHAR | 2 | 0 | Analysis/Reason for Rejection |
| `CPD_UPDAT` | /CPD/PFP_TSTMP | — | DEC | 15 | 0 | Time Stamp |
| `AUFPL_OLC` | CO_AUFPL | — | NUMC | 10 | 0 | Routing number of operations in the order |
| `APLZL_OLC` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `/XLSO/COURSE_ID` | /XLSO/E_PRODUCT_ID | — | NUMC | 8 | 0 | Product ID |
| `/XLSO/COURSE_BDA` | BEGDA | — | DATS | 8 | 0 | Start Date |
| `/XLSO/COURSE_EDA` | ENDDA | — | DATS | 8 | 0 | End Date |
| `FERC_IND` | FE_IND | FERC_C7 | CHAR | 4 | 0 | Regulatory indicator |
| `KOSTL` | KOSTL | — | CHAR | 10 | 0 | Cost Center |
| `FONDS` | BP_GEBER | — | CHAR | 10 | 0 | Fund |
| `FISTL` | FISTL | — | CHAR | 16 | 0 | Funds Center |
| `FKBER` | FKBER | — | CHAR | 16 | 0 | Functional Area |
| `GRANT_NBR` | GM_GRANT_NBR | — | CHAR | 20 | 0 | Grant |
| `BUDGET_PD` | FM_BUDGET_PERIOD | — | CHAR | 10 | 0 | FM: Budget Period |
| `IUID_RELEVANT` | IUID_RELEVANT_CUST | — | CHAR | 1 | 0 | IUID Relevant for Customer |
| `MILL_SE_GPOSN` | MILL_SE_GPOSN | — | NUMC | 6 | 0 | Global Item |
| `OID_EXTBOL` | OID_EXTBOL | — | CHAR | 16 | 0 | External bill of lading |
| `OID_MISCDL` | OID_MISCDL | — | CHAR | 16 | 0 | Miscellaneous delivery number |
| `OIPLANTD` | OID_PLANTD | — | CHAR | 1 | 0 | Plant determination active or not active |
| `OIBYPASS` | OID_BYPASS | — | CHAR | 1 | 0 | IS-Oil plant determination indicator:  x=yes   blank=no |
| `OIEDOK` | OIH_EDOK | — | CHAR | 1 | 0 | Excise duty validation indicator |
| `CMETH` | OIB_CMETH | — | CHAR | 1 | 0 | Quantity Conversion Method |
| `OITAXFROM` | OIH_TAXFRO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;from&#039; location |
| `OIHANTYP` | OIH_HANTYP | OIH5 | CHAR | 2 | 0 | Excise Duty Handling Type |
| `OITAXGRP` | OIH_TAXGRP | OIH2 | CHAR | 2 | 0 | Excise Duty Group |
| `OITAXTO` | OIH_TAXTO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;to&#039; location |
| `OICERTF1` | OIH_CERTF1 | — | CHAR | 15 | 0 | Excise tax external license number |
| `OIOILCON` | OIH_OILCON | — | DEC | 5 | 2 | Oil content in a material as a percentage |
| `OIEDBAL` | OIH_EDBAL | — | CHAR | 1 | 0 | Excise duty balancing is required (indicator) |
| `OIPRICIE` | OIH_PRICIE | — | CHAR | 1 | 0 | ED pricing: external (indicator) |
| `OIINEX` | OIH_INEX | OIH16 | CHAR | 2 | 0 | Code for internal or external excise duty rate determination |
| `OIEDBALM` | OIH_EDBALM | — | CHAR | 1 | 0 | Excise duty balancing method indicator |
| `OIDRC` | OIC_DRC | OICDC | CHAR | 5 | 0 | Differential Reference Code (DRC) |
| `OIC_DRCTRY` | OIC_DRCTRY | — | CHAR | 3 | 0 | DRC country |
| `OIC_DRCREG` | OIC_DRCREG | — | CHAR | 3 | 0 | DRC region |
| `OIMETIND` | OIC_METIND | — | CHAR | 4 | 0 | Metropolitan indicator |
| `OIWAP` | OIC_WAP | — | CHAR | 3 | 0 | Wide-area pricing zone |
| `OISLF` | OIC_SLF | — | CHAR | 3 | 0 | State license fee zone |
| `OIPSDRC` | OIC_PSDRC | — | CHAR | 5 | 0 | Pricing DRC (grouping customers by DRC for pricing) |
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
| `OIEXGNUM` | OIA_EXGNUM | — | CHAR | 10 | 0 | Exchange agreement number |
| `OIEXGTYP` | OIA_EXGTYP | TOIA2 | CHAR | 4 | 0 | Exchange type |
| `OIFEETOT` | OIA_FEETOT | — | CURR | 13 | 2 | Fee total |
| `OIFEEDT` | OIA_FEEDT | — | DATS | 8 | 0 | Fee pricing condition date |
| `OINETCYC` | OIA_NETCYC | T008 | CHAR | 1 | 0 | Netting cycle (FI blocking indicator) |
| `OICONTNR` | OIC_CONTNR | — | CHAR | 10 | 0 | Outline agreement: contract |
| `OIC_KMPOS` | OIC_KMPOS | — | NUMC | 6 | 0 | Reference contract line item number |
| `OIFEECH` | OIA_FEECH | — | CHAR | 1 | 0 | Fee edit control |
| `OIH_LICTP` | OIH_LICTP | OIH20 | CHAR | 4 | 0 | License type |
| `OIH_LICIN` | OIH_LICIN | — | CHAR | 10 | 0 | Excise tax internal license number |
| `OIH_LCFOL` | OIH_LCFOL | OIHL | CHAR | 10 | 0 | Follow-on license for quantity license |
| `OIH_FOLQTY` | OIH_FOLQTY | — | QUAN | 13 | 3 | Excise Tax Follow-On License Quantity |
| `OISBREL` | OIA_SBREL | — | NUMC | 3 | 0 | Sub product/ base product relevence indicator |
| `OIBASPROD` | OIA_SBMAT | — | CHAR | 18 | 0 | Base product number |
| `OIDMSG_PRD` | OIDMSG_PRD | — | CHAR | 1 | 0 | Message type for product with contract restrictions |
| `OIDMSG_QTY` | OIDMSG_QTY | — | CHAR | 1 | 0 | Message type for contract restrictions quantity |
| `OIDMSG_UOM` | OIDMSG_UOM | — | CHAR | 1 | 0 | Message type for contract restrictions unit of measure |
| `OIDMSG_DAT` | OIDMSG_DAT | — | CHAR | 1 | 0 | Message type for contract restrictions validity period |
| `OIDMSG_TRM` | OIDMSG_TRM | — | CHAR | 1 | 0 | Message type for contract restrictions payment terms |
| `OIDMSG_SHP` | OIDMSG_SHP | — | CHAR | 1 | 0 | Message type for contract restrictions ship-to party |
| `OIGNRULE` | OIC_GNRULE | — | NUMC | 3 | 0 | Gross/net pricing rule |
| `OID_SHIP` | KUNWE | — | CHAR | 10 | 0 | Ship-to party |
| `OIBWTAR_IM` | BWTAR_D | T149D | CHAR | 10 | 0 | Valuation Type |
| `OIHANTYP_IM` | OIH_HANTYP | OIH5 | CHAR | 2 | 0 | Excise Duty Handling Type |
| `OITAXGRP_IM` | OIH_TAXGRP | OIH2 | CHAR | 2 | 0 | Excise Duty Group |
| `OITAXFROM_IM` | OIH_TAXFRO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;from&#039; location |
| `OITAXTO_IM` | OIH_TAXTO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;to&#039; location |
| `OIEDBAL_IM` | OIH_EDBAL | — | CHAR | 1 | 0 | Excise duty balancing is required (indicator) |
| `OIEDBALM_IM` | OIH_EDBALM | — | CHAR | 1 | 0 | Excise duty balancing method indicator |
| `OIPRICIE_IM` | OIH_PRICIE | — | CHAR | 1 | 0 | ED pricing: external (indicator) |
| `OIBWTAR_EX` | BWTAR_D | T149D | CHAR | 10 | 0 | Valuation Type |
| `OIHANTYP_EX` | OIH_HANTYP | OIH5 | CHAR | 2 | 0 | Excise Duty Handling Type |
| `OITAXGRP_EX` | OIH_TAXGRP | OIH2 | CHAR | 2 | 0 | Excise Duty Group |
| `OITAXFROM_EX` | OIH_TAXFRO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;from&#039; location |
| `OITAXTO_EX` | OIH_TAXTO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;to&#039; location |
| `OIEDBAL_EX` | OIH_EDBAL | — | CHAR | 1 | 0 | Excise duty balancing is required (indicator) |
| `OIEDBALM_EX` | OIH_EDBALM | — | CHAR | 1 | 0 | Excise duty balancing method indicator |
| `OIPRICIE_EX` | OIH_PRICIE | — | CHAR | 1 | 0 | ED pricing: external (indicator) |
| `OIINEX_EX` | OIH_INEX | OIH16 | CHAR | 2 | 0 | Code for internal or external excise duty rate determination |
| `OICERTF1_EX` | OIH_CERTF1 | — | CHAR | 15 | 0 | Excise tax external license number |
| `OIH_LICTP_EX` | OIH_LICTP | OIH20 | CHAR | 4 | 0 | License type |
| `OIH_LICIN_EX` | OIH_LICIN | — | CHAR | 10 | 0 | Excise tax internal license number |
| `OIH_LCFOL_EX` | OIH_LCFOL | OIHL | CHAR | 10 | 0 | Follow-on license for quantity license |
| `OIH_FOLQTY_EX` | OIH_FOLQTY | — | QUAN | 13 | 3 | Excise Tax Follow-On License Quantity |
| `OIHTAXRCP_EX` | OIHTAXRCP | — | CHAR | 10 | 0 | Tax Recipient |
| `OIHNOTWERKS` | OIH_SHADOWPL | — | CHAR | 4 | 0 | Cross Excise Duty Plant |
| `OIHNOTLGORT` | OIH_SHADOWLOC | — | CHAR | 4 | 0 | Cross Excise Duty Storage Location |
| `OIHCOTDISCH` | OIHCOTDISCH | — | CHAR | 1 | 0 | Trigger Import Posting at Proof of Delivery Receipt |
| `OIU_MP_NO` | — | — | CHAR | 20 | 0 | OIU_MP_NO |
| `OIU_WL_NO` | — | — | CHAR | 15 | 0 | OIU_WL_NO |
| `OIU_WC_NO` | — | — | CHAR | 5 | 0 | OIU_WC_NO |
| `PRS_OBJNR` | PRS_OBJNR | — | CHAR | 22 | 0 | Engagement mgmt: Object number |
| `PRS_SD_SPSNR` | PRS_SD_SPSNR | — | NUMC | 8 | 0 | Standard WBS Element for Project Inception via SD |
| `PRS_WORK_PERIOD` | PRS_WORK_PERIOD | — | NUMC | 7 | 0 | Work Period (Internal Representation) |
| `TAS` | FMFG_TAS | — | CHAR | 30 | 0 | Treasury Account Symbol |
| `BETC` | FMFG_BETC | — | CHAR | 10 | 0 | Business Event Type Code |
| `MOD_ALLOW` | FMFG_MOD_ALLOW | — | CHAR | 1 | 0 | Modification Allowed |
| `CANCEL_ALLOW` | FMFG_CANCEL_ALLOW | — | CHAR | 1 | 0 | Cancellation Allowed |
| `PAY_METHOD` | DZWELS | — | CHAR | 10 | 0 | List of the Payment Methods to be Considered |
| `BPN` | FMFG_BPN | T880 | CHAR | 6 | 0 | Business Partner Number |
| `REP_FREQ` | FMFG_REP_FREQ | — | CHAR | 3 | 0 | Reporting Frequency |
| `PARGB` | PARGB | — | CHAR | 4 | 0 | Trading partner&#039;s business area |
| `AUFPL_OAA` | CO_AUFPL | — | NUMC | 10 | 0 | Routing number of operations in the order |
| `APLZL_OAA` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `ARSNUM` | WTYSC_RSNUM | — | NUMC | 10 | 0 | Number of reservation/dependent requirements |
| `ARSPOS` | WTYSC_RSPOS | — | NUMC | 4 | 0 | Item number of reservation/dependent requirements |
| `WTYSC_CLMITEM` | WTYSC_CLMITEM | — | CHAR | 16 | 0 | Claim item number |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABFOR` | VBAP | MANDT | T691K |  | |
| `ABFOR` | VBAP | ABFOR | T691K |  | |
| `ABGRS` | VBAP | MANDT | TKKAA |  | |
| `ABGRS` | VBAP | ABGRS | TKKAA |  | |
| `ABGRU` | VBAP | ABGRU | TVAG |  | |
| `ABGRU` | VBAP | MANDT | TVAG |  | |
| `AUFNR` | VBAP | MANDT | AUFK |  | |
| `AUFNR` | VBAP | AUFNR | AUFK |  | |
| `BEDAE` | VBAP | MANDT | T459A |  | |
| `BEDAE` | VBAP | BEDAE | T459A |  | |
| `BONUS` | VBAP | MANDT | TVBO |  | |
| `BONUS` | VBAP | BONUS | TVBO |  | |
| `BPN` | VBAP | MANDT | T880 |  | |
| `BPN` | VBAP | BPN | T880 |  | |
| `BWTAR` | VBAP | MANDT | T149D |  | |
| `BWTAR` | VBAP | BWTAR | T149D |  | |
| `CHARG` | VBAP | WERKS | MCHA |  | |
| `CHARG` | VBAP | CHARG | MCHA |  | |
| `CHARG` | VBAP | MANDT | MCHA |  | |
| `CHARG` | VBAP | MATNR | MCHA |  | |
| `CLINT` | VBAP | MANDT | KLAH |  | |
| `CLINT` | VBAP | CLINT | KLAH |  | |
| `EXART` | VBAP | MANDT | T605 |  | |
| `EXART` | T001W | LAND1 | T605 |  | |
| `EXART` | VBAP | EXART | T605 |  | |
| `FAKSP` | VBAP | FAKSP | TVFS |  | |
| `FAKSP` | VBAP | MANDT | TVFS |  | |
| `FERC_IND` | VBAP | MANDT | FERC_C7 |  | |
| `FERC_IND` | VBAP | FERC_IND | FERC_C7 |  | |
| `GEWEI` | VBAP | GEWEI | T006 |  | |
| `GEWEI` | VBAP | MANDT | T006 |  | |
| `GSBER` | VBAP | MANDT | TGSB |  | |
| `GSBER` | VBAP | GSBER | TGSB |  | |
| `J_1BCFOP` | VBAP | MANDT | J_1BAG |  | |
| `J_1BCFOP` | VBAP | J_1BCFOP | J_1BAG |  | |
| `J_1BTAXLW1` | VBAP | MANDT | J_1BATL1 |  | |
| `J_1BTAXLW1` | VBAP | J_1BTAXLW1 | J_1BATL1 |  | |
| `J_1BTAXLW2` | VBAP | MANDT | J_1BATL2 |  | |
| `J_1BTAXLW2` | VBAP | J_1BTAXLW2 | J_1BATL2 |  | |
| `J_1BTAXLW3` | VBAP | J_1BTAXLW3 | J_1BATL3 |  | |
| `J_1BTAXLW3` | VBAP | MANDT | J_1BATL3 |  | |
| `J_1BTAXLW4` | VBAP | MANDT | J_1BATL4A |  | |
| `J_1BTAXLW4` | VBAP | J_1BTAXLW4 | J_1BATL4A |  | |
| `J_1BTAXLW5` | VBAP | MANDT | J_1BATL5 |  | |
| `J_1BTAXLW5` | VBAP | J_1BTAXLW5 | J_1BATL5 |  | |
| `J_1BTXSDC` | VBAP | MANDT | J_1BTXSDC |  | |
| `J_1BTXSDC` | VBAP | J_1BTXSDC | J_1BTXSDC |  | |
| `KALSM_K` | &#039;A&#039; |  | T683 |  | |
| `KALSM_K` | &#039;KA&#039; |  | T683 |  | |
| `KALSM_K` | VBAP | KALSM_K | T683 |  | |
| `KALSM_K` | VBAP | MANDT | T683 |  | |
| `KALVAR` | VBAP | MANDT | TCK03 |  | |
| `KALVAR` | VBAP | KALVAR | TCK03 |  | |
| `KMEIN` | VBAP | MANDT | T006 |  | |
| `KMEIN` | VBAP | KMEIN | T006 |  | |
| `KNTTP` | VBAP | MANDT | T163K |  | |
| `KNTTP` | VBAP | KNTTP | T163K |  | |
| `KNUMA_AG` | VBAP | MANDT | KONA |  | |
| `KNUMA_AG` | VBAP | KNUMA_AG | KONA |  | |
| `KNUMA_PI` | VBAP | MANDT | KONA |  | |
| `KNUMA_PI` | VBAP | KNUMA_PI | KONA |  | |
| `KONDM` | VBAP | MANDT | T178 |  | |
| `KONDM` | VBAP | KONDM | T178 |  | |
| `KOSCH` | VBAP | MANDT | T190S |  | |
| `KOSCH` | VBAP | KOSCH | T190S |  | |
| `KTGRM` | VBAP | MANDT | TVKM |  | |
| `KTGRM` | VBAP | KTGRM | TVKM |  | |
| `LGORT` | VBAP | MANDT | T001L |  | |
| `LGORT` | VBAP | WERKS | T001L |  | |
| `LGORT` | VBAP | LGORT | T001L |  | |
| `LPRIO` | VBAP | MANDT | TPRIO |  | |
| `LPRIO` | VBAP | LPRIO | TPRIO |  | |
| `MAGRV` | VBAP | MANDT | TVEGR |  | |
| `MAGRV` | VBAP | MAGRV | TVEGR |  | |
| `MANDT` | VBAP | MANDT | T000 |  | |
| `MATKL` | VBAP | MATKL | T023 |  | |
| `MATKL` | VBAP | MANDT | T023 |  | |
| `MATNR` | VBAP | MATNR | MARA |  | |
| `MATNR` | VBAP | MANDT | MARA |  | |
| `MATWA` | VBAP | MANDT | MARA |  | |
| `MATWA` | VBAP | MATWA | MARA |  | |
| `MEINS` | VBAP | MANDT | T006 |  | |
| `MEINS` | VBAP | MEINS | T006 |  | |
| `MFRGR` | VBAP | MFRGR | TMFG |  | |
| `MFRGR` | VBAP | MANDT | TMFG |  | |
| `MSR_REFUND_CODE` | VBAP | MSR_REFUND_CODE | MSR_C_RET_REFUND |  | |
| `MSR_REFUND_CODE` | VBAP | MANDT | MSR_C_RET_REFUND |  | |
| `MSR_RET_REASON` | VBAP | MANDT | MSR_C_RET_REASON |  | |
| `MSR_RET_REASON` | VBAP | MSR_RET_REASON | MSR_C_RET_REASON |  | |
| `MTVFP` | VBAP | MANDT | TMVF |  | |
| `MTVFP` | VBAP | MTVFP | TMVF |  | |
| `MVGR1` | VBAP | MANDT | TVM1 |  | |
| `MVGR1` | VBAP | MVGR1 | TVM1 |  | |
| `MVGR2` | VBAP | MANDT | TVM2 |  | |
| `MVGR2` | VBAP | MVGR2 | TVM2 |  | |
| `MVGR3` | VBAP | MVGR3 | TVM3 |  | |
| `MVGR3` | VBAP | MANDT | TVM3 |  | |
| `MVGR4` | VBAP | MANDT | TVM4 |  | |
| `MVGR4` | VBAP | MVGR4 | TVM4 |  | |
| `MVGR5` | VBAP | MANDT | TVM5 |  | |
| `MVGR5` | VBAP | MVGR5 | TVM5 |  | |
| `OBJNR` | VBAP | MANDT | ONR00 |  | |
| `OBJNR` | VBAP | OBJNR | ONR00 |  | |
| `OIBWTAR_EX` | SYST | MANDT | T149D |  | |
| `OIBWTAR_EX` | VBAP | OIBWTAR_EX | T149D |  | |
| `OIBWTAR_IM` | SYST | MANDT | T149D |  | |
| `OIBWTAR_IM` | VBAP | OIBWTAR_IM | T149D |  | |
| `OIC_DCITYC` | SYST | MANDT | T005G |  | |
| `OIC_DCITYC` | VBAP | OIC_DLAND1 | T005G |  | |
| `OIC_DCITYC` | VBAP | OIC_DREGIO | T005G |  | |
| `OIC_DCITYC` | VBAP | OIC_DCITYC | T005G |  | |
| `OIC_DCOUNC` | VBAP | OIC_DREGIO | T005E |  | |
| `OIC_DCOUNC` | VBAP | OIC_DCOUNC | T005E |  | |
| `OIC_DCOUNC` | SYST | MANDT | T005E |  | |
| `OIC_DCOUNC` | VBAP | OIC_DLAND1 | T005E |  | |
| `OIC_DLAND1` | SYST | MANDT | T005 |  | |
| `OIC_DLAND1` | VBAP | OIC_DLAND1 | T005 |  | |
| `OIC_DREGIO` | VBAP | OIC_DREGIO | T005S |  | |
| `OIC_DREGIO` | SYST | MANDT | T005S |  | |
| `OIC_DREGIO` | VBAP | OIC_DLAND1 | T005S |  | |
| `OIC_LIFNR` | SYST | MANDT | LFA1 |  | |
| `OIC_LIFNR` | VBAP | OIC_LIFNR | LFA1 |  | |
| `OIC_MOT` | SYST | MANDT | TVTR |  | |
| `OIC_MOT` | VBAP | OIC_MOT | TVTR |  | |
| `OIC_OCITYC` | SYST | MANDT | T005G |  | |
| `OIC_OCITYC` | VBAP | OIC_OLAND1 | T005G |  | |
| `OIC_OCITYC` | VBAP | OIC_OREGIO | T005G |  | |
| `OIC_OCITYC` | VBAP | OIC_OCITYC | T005G |  | |
| `OIC_OCOUNC` | VBAP | OIC_OCOUNC | T005E |  | |
| `OIC_OCOUNC` | SYST | MANDT | T005E |  | |
| `OIC_OCOUNC` | VBAP | OIC_OLAND1 | T005E |  | |
| `OIC_OCOUNC` | VBAP | OIC_OREGIO | T005E |  | |
| `OIC_OLAND1` | SYST | MANDT | T005 |  | |
| `OIC_OLAND1` | VBAP | OIC_OLAND1 | T005 |  | |
| `OIC_OREGIO` | SYST | MANDT | T005S |  | |
| `OIC_OREGIO` | VBAP | OIC_OLAND1 | T005S |  | |
| `OIC_OREGIO` | VBAP | OIC_OREGIO | T005S |  | |
| `OIDRC` | VBAP | MANDT | OICDC |  | |
| `OIDRC` | VBAP | OIDRC | OICDC |  | |
| `OIEXGTYP` | SYST | MANDT | TOIA2 |  | |
| `OIEXGTYP` | VBAP | OIEXGTYP | TOIA2 |  | |
| `OIHANTYP` | T000 | MANDT | OIH5 |  | |
| `OIHANTYP` | VBAP | OIHANTYP | OIH5 |  | |
| `OIHANTYP_EX` | VBAP | OIHANTYP_EX | OIH5 |  | |
| `OIHANTYP_EX` | SYST | MANDT | OIH5 |  | |
| `OIHANTYP_IM` | SYST | MANDT | OIH5 |  | |
| `OIHANTYP_IM` | VBAP | OIHANTYP_IM | OIH5 |  | |
| `OIH_LCFOL` | VBAP | OIH_LICTP | OIHL |  | |
| `OIH_LCFOL` | MANDT | VBAP | OIHL |  | |
| `OIH_LCFOL` | VBAP | OIH_LCFOL | OIHL |  | |
| `OIH_LCFOL_EX` | SYST | MANDT | OIHL |  | |
| `OIH_LCFOL_EX` | VBAP | OIH_LCFOL_EX | OIHL |  | |
| `OIH_LCFOL_EX` | VBAP | OIH_LICTP_EX | OIHL |  | |
| `OIH_LICTP` | VBAP | MANDT | OIH20 |  | |
| `OIH_LICTP` | VBAP | OIH_LICTP | OIH20 |  | |
| `OIH_LICTP_EX` | VBAP | OIH_LICTP_EX | OIH20 |  | |
| `OIH_LICTP_EX` | SYST | MANDT | OIH20 |  | |
| `OIINEX` | T000 | MANDT | OIH16 |  | |
| `OIINEX` | VBAP | OIINEX | OIH16 |  | |
| `OIINEX_EX` | SYST | MANDT | OIH16 |  | |
| `OIINEX_EX` | VBAP | OIINEX_EX | OIH16 |  | |
| `OINETCYC` | SYST | MANDT | T008 |  | |
| `OINETCYC` | VBAP | OINETCYC | T008 |  | |
| `OITAXFROM` | T000 | MANDT | OIH4 |  | |
| `OITAXFROM` | VBAP | OITAXFROM | OIH4 |  | |
| `OITAXFROM_EX` | SYST | MANDT | OIH4 |  | |
| `OITAXFROM_EX` | VBAP | OITAXFROM_EX | OIH4 |  | |
| `OITAXFROM_IM` | SYST | MANDT | OIH4 |  | |
| `OITAXFROM_IM` | VBAP | OITAXFROM_IM | OIH4 |  | |
| `OITAXGRP` | T000 | MANDT | OIH2 |  | |
| `OITAXGRP` | VBAP | OITAXGRP | OIH2 |  | |
| `OITAXGRP_EX` | SYST | MANDT | OIH2 |  | |
| `OITAXGRP_EX` | VBAP | OITAXGRP_EX | OIH2 |  | |
| `OITAXGRP_IM` | SYST | MANDT | OIH2 |  | |
| `OITAXGRP_IM` | VBAP | OITAXGRP_IM | OIH2 |  | |
| `OITAXTO` | T000 | MANDT | OIH4 |  | |
| `OITAXTO` | VBAP | OITAXTO | OIH4 |  | |
| `OITAXTO_EX` | SYST | MANDT | OIH4 |  | |
| `OITAXTO_EX` | VBAP | OITAXTO_EX | OIH4 |  | |
| `OITAXTO_IM` | SYST | MANDT | OIH4 |  | |
| `OITAXTO_IM` | VBAP | OITAXTO_IM | OIH4 |  | |
| `PLAVO` | VBAP | MANDT | TVZP |  | |
| `PLAVO` | VBAP | PLAVO | TVZP |  | |
| `PMATN` | VBAP | MANDT | MARA |  | |
| `PMATN` | VBAP | PMATN | MARA |  | |
| `POSNR` | VBAP | MANDT | VBUP |  | |
| `POSNR` | VBAP | VBELN | VBUP |  | |
| `POSNR` | VBAP | POSNR | VBUP |  | |
| `POSNV` | VBAP | MANDT | VBUP |  | |
| `POSNV` | VBAP | VBELV | VBUP |  | |
| `POSNV` | VBAP | POSNV | VBUP |  | |
| `PRBME` | VBAP | MANDT | T006 |  | |
| `PRBME` | VBAP | PRBME | T006 |  | |
| `PRODH` | VBAP | PRODH | T179 |  | |
| `PRODH` | VBAP | MANDT | T179 |  | |
| `PROVG` | VBAP | PROVG | TVPR |  | |
| `PROVG` | VBAP | MANDT | TVPR |  | |
| `PSTYV` | VBAP | MANDT | TVPT |  | |
| `PSTYV` | VBAP | PSTYV | TVPT |  | |
| `PS_PSP_PNR` | VBAP | MANDT | PRPS |  | |
| `PS_PSP_PNR` | VBAP | PS_PSP_PNR | PRPS |  | |
| `ROUTE` | VBAP | MANDT | TVRO |  | |
| `ROUTE` | VBAP | ROUTE | TVRO |  | |
| `SERAIL` | VBAP | MANDT | T377P |  | |
| `SERAIL` | VBAP | SERAIL | T377P |  | |
| `SERNR` | VBAP | MANDT | SNUM |  | |
| `SERNR` | VBAP | SERNR | SNUM |  | |
| `SKOPF` | VBAP | MANDT | WSOH |  | |
| `SKOPF` | VBAP | SKOPF | WSOH |  | |
| `SOBKZ` | VBAP | MANDT | T148 |  | |
| `SOBKZ` | VBAP | SOBKZ | T148 |  | |
| `SPART` | VBAP | MANDT | TSPA |  | |
| `SPART` | VBAP | SPART | TSPA |  | |
| `SUGRD` | VBAP | SUGRD | TVSU |  | |
| `SUGRD` | VBAP | MANDT | TVSU |  | |
| `UKONM` | VBAP | MANDT | T178 |  | |
| `UKONM` | VBAP | UKONM | T178 |  | |
| `UPMAT` | VBAP | MANDT | MARA |  | |
| `UPMAT` | VBAP | UPMAT | MARA |  | |
| `VBELN` | VBAP | VBELN | VBUK |  | |
| `VBELN` | VBAP | MANDT | VBUK |  | |
| `VBELV` | VBAP | MANDT | VBUK |  | |
| `VBELV` | VBAP | VBELV | VBUK |  | |
| `VGBEL` | VBAP | MANDT | VBUK |  | |
| `VGBEL` | VBAP | VGBEL | VBUK |  | |
| `VGPOS` | VBAP | MANDT | VBUP |  | |
| `VGPOS` | VBAP | VGBEL | VBUP |  | |
| `VGPOS` | VBAP | VGPOS | VBUP |  | |
| `VKAUS` | VBAP | MANDT | TVLV |  | |
| `VKAUS` | VBAP | VKAUS | TVLV |  | |
| `VKGRU` | VBAP | MANDT | TVRMAVK |  | |
| `VKGRU` | VBAP | VKGRU | TVRMAVK |  | |
| `VOLEH` | VBAP | MANDT | T006 |  | |
| `VOLEH` | VBAP | VOLEH | T006 |  | |
| `VPMAT` | VBAP | MANDT | MARA |  | |
| `VPMAT` | VBAP | VPMAT | MARA |  | |
| `VPWRK` | VBAP | MANDT | T001W |  | |
| `VPWRK` | VBAP | VPWRK | T001W |  | |
| `VRKME` | VBAP | MANDT | T006 |  | |
| `VRKME` | VBAP | VRKME | T006 |  | |
| `VSTEL` | VBAP | MANDT | TVST |  | |
| `VSTEL` | VBAP | VSTEL | TVST |  | |
| `WAERK` | VBAP | WAERK | TCURC |  | |
| `WAERK` | VBAP | MANDT | TCURC |  | |
| `WKTNR` | VBAP | MANDT | VBUK |  | |
| `WKTNR` | VBAP | WKTNR | VBUK |  | |
| `WKTPS` | VBAP | MANDT | VBUP |  | |
| `WKTPS` | VBAP | VBELN | VBUP |  | |
| `WKTPS` | VBAP | WKTPS | VBUP |  | |
| `ZIEME` | VBAP | MANDT | T006 |  | |
| `ZIEME` | VBAP | ZIEME | T006 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `abgru`, `arktx`, `cuobj`, `erdat`, `kondm`, `kwmeng`, `matnr`, `mvgr1`, `netwr`, `posnr`, `uepos`, `vbeln`, `vkaus`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `cuobj`, `vbeln`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `ziscs0522_f01.txt`
- `ziscseec_comm_frmwrk_eeus_ea.txt`
- `zisfi0121.txt`
- `zissd00003.txt`
- `zissd00005.txt`
- `zissd00008.txt`
- `zissd00013.txt`
- `zissd00015.txt`
- `zissd00018.txt`
- `zissd00048.txt`
- `zissd00056.txt`
- `zissd00059.txt`
- `zissd00066.txt`
- `zissd00091.txt`
- `zissd00101.txt`
- `zsdisqry02.txt`
- `zsdisqry04.txt`
- `zsdsoblk1.txt`
- `zsdsoc001.txt`
- `zsdsopoc1.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_