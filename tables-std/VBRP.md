# `VBRP`

**Description:** Billing Document Item — billing line item
**Category:** Standard SAP Table
**References:** 31 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/vbrp/) — validated 2026-05-30, schema v1.0
**Schema fields:** 319 fields | **Data types:** CHAR(218), CURR(19), DATS(16), DEC(6), FLTP(3), NUMC(25), QUAN(20), RAW(3), TIMS(2), UNIT(7)

## Key Fields
`MATNR` | `AUFNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `UEPOS` | UEPOS | VBUP | NUMC | 6 | 0 | Higher-level item in bill of material structures |
| `FKIMG` | FKIMG | — | QUAN | 13 | 3 | Actual Invoiced Quantity |
| `VRKME` | VRKME | T006 | UNIT | 3 | 0 | Sales unit |
| `UMVKZ` | UMVKZ | — | DEC | 5 | 0 | Numerator (factor) for conversion of sales quantity into SKU |
| `UMVKN` | UMVKN | — | DEC | 5 | 0 | Denominator (Divisor) for Conversion of Sales Qty into SKU |
| `MEINS` | MEINS | T006 | UNIT | 3 | 0 | Base Unit of Measure |
| `SMENG` | SMENG | — | QUAN | 13 | 3 | Scale quantity in base unit of measure |
| `FKLMG` | FKLMG | — | QUAN | 13 | 3 | Billing quantity in stockkeeping unit |
| `LMENG` | LMENG | — | QUAN | 13 | 3 | Required quantity for mat.management in stockkeeping units |
| `NTGEW` | NTGEW_15 | — | QUAN | 15 | 3 | Net weight |
| `BRGEW` | BRGEW_15 | — | QUAN | 15 | 3 | Gross weight |
| `GEWEI` | GEWEI | T006 | UNIT | 3 | 0 | Weight Unit |
| `VOLUM` | VOLUM_15 | — | QUAN | 15 | 3 | Volume |
| `VOLEH` | VOLEH | T006 | UNIT | 3 | 0 | Volume unit |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `PRSDT` | PRSDT | — | DATS | 8 | 0 | Date for pricing and exchange rate |
| `FBUDA` | FBUDA | — | DATS | 8 | 0 | Date on which services rendered |
| `KURSK` | KURSK | — | DEC | 9 | 5 | Exchange Rate for Price Determination |
| `NETWR` | NETWR_FP | — | CURR | 15 | 2 | Net value of the billing item in document currency |
| `VBELV` | VBELV | VBUK | CHAR | 10 | 0 | Originating document |
| `POSNV` | POSNV | VBUP | NUMC | 6 | 0 | Originating item |
| `VGBEL` | VGBEL | VBUK | CHAR | 10 | 0 | Document number of the reference document |
| `VGPOS` | VGPOS | VBUP | NUMC | 6 | 0 | Item number of the reference item |
| `VGTYP` | VBTYP_V | — | CHAR | 1 | 0 | Document category of preceding SD document |
| `AUBEL` | VBELN_VA | VBUK | CHAR | 10 | 0 | Sales Document |
| `AUPOS` | POSNR_VA | VBUP | NUMC | 6 | 0 | Sales Document Item |
| `AUREF` | AUREF | — | CHAR | 1 | 0 | Sales document was created from reference |
| `MATNR` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `ARKTX` | ARKTX | — | CHAR | 40 | 0 | Short text for sales order item |
| `PMATN` | PMATN | MARA | CHAR | 18 | 0 | Pricing Reference Material |
| `CHARG` | CHARG_D | MCHA | CHAR | 10 | 0 | Batch Number |
| `MATKL` | MATKL | T023 | CHAR | 9 | 0 | Material Group |
| `PSTYV` | PSTYV | — | CHAR | 4 | 0 | Sales document item category |
| `POSAR` | POSAR | — | CHAR | 1 | 0 | Item type |
| `PRODH` | PRODH_D | T179 | CHAR | 18 | 0 | Product hierarchy |
| `VSTEL` | VSTEL | TVST | CHAR | 4 | 0 | Shipping Point/Receiving Point |
| `ATPKZ` | ATPKZ | — | CHAR | 1 | 0 | Replacement part |
| `SPART` | SPART | TSPA | CHAR | 2 | 0 | Division |
| `POSPA` | POSPA | VBUP | NUMC | 6 | 0 | Item number in the partner segment |
| `WERKS` | WERKS_D | T001W | CHAR | 4 | 0 | Plant |
| `ALAND` | ALAND | T005 | CHAR | 3 | 0 | Departure country (country from which the goods are sent) |
| `WKREG` | WKREG | T005S | CHAR | 3 | 0 | Region in which plant is located |
| `WKCOU` | WKCOU | — | CHAR | 3 | 0 | County in which plant is located |
| `WKCTY` | WKCTY | — | CHAR | 4 | 0 | City in which plant is located |
| `TAXM1` | TAXM1 | — | CHAR | 1 | 0 | Tax classification material |
| `TAXM2` | TAXM2 | — | CHAR | 1 | 0 | Tax classification 2 for material |
| `TAXM3` | TAXM3 | — | CHAR | 1 | 0 | Tax classification 3 for material |
| `TAXM4` | TAXM4 | — | CHAR | 1 | 0 | Tax Classification 4 Material |
| `TAXM5` | TAXM5 | — | CHAR | 1 | 0 | Tax classification 5 for material |
| `TAXM6` | TAXM6 | — | CHAR | 1 | 0 | Tax classification 6 for material |
| `TAXM7` | TAXM7 | — | CHAR | 1 | 0 | Tax classification 7 for material |
| `TAXM8` | TAXM8 | — | CHAR | 1 | 0 | Tax Classification 8 Material |
| `TAXM9` | TAXM9 | — | CHAR | 1 | 0 | Tax Classification 9 Material |
| `KOWRR` | KOWRR | — | CHAR | 1 | 0 | Statistical values |
| `PRSFD` | PRSFD | — | CHAR | 1 | 0 | Carry out pricing |
| `SKTOF` | SKTOF | — | CHAR | 1 | 0 | Cash discount indicator |
| `SKFBP` | SKFBP | — | CURR | 13 | 2 | Amount eligible for cash discount in document currency |
| `KONDM` | KONDM | T178 | CHAR | 2 | 0 | Material Pricing Group |
| `KTGRM` | KTGRM | TVKM | CHAR | 2 | 0 | Account assignment group for this material |
| `KOSTL` | KOSTL | — | CHAR | 10 | 0 | Cost Center |
| `BONUS` | BONUS | TVBO | CHAR | 2 | 0 | Volume rebate group |
| `PROVG` | PROVG | TVPR | CHAR | 2 | 0 | Commission group |
| `EANNR` | EANNR | — | CHAR | 13 | 0 | European Article Number (EAN) - obsolete!!!!! |
| `VKGRP` | VKGRP | TVKGR | CHAR | 3 | 0 | Sales Group |
| `VKBUR` | VKBUR | TVBUR | CHAR | 4 | 0 | Sales Office |
| `SPARA` | SPART_AK | TSPA | CHAR | 2 | 0 | Division for order header |
| `SHKZG` | SHKZG_VF | — | CHAR | 1 | 0 | Returns item |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERZET` | ERZET | — | TIMS | 6 | 0 | Entry time |
| `BWTAR` | BWTAR_D | T149D | CHAR | 10 | 0 | Valuation Type |
| `LGORT` | LGORT_D | T001L | CHAR | 4 | 0 | Storage Location |
| `STAFO` | STAFO | — | CHAR | 6 | 0 | Update group for statistics update |
| `WAVWR` | WAVWR | — | CURR | 13 | 2 | Cost in document currency |
| `KZWI1` | KZWI1 | — | CURR | 13 | 2 | Subtotal 1 from pricing procedure for condition |
| `KZWI2` | KZWI2 | — | CURR | 13 | 2 | Subtotal 2 from pricing procedure for condition |
| `KZWI3` | KZWI3 | — | CURR | 13 | 2 | Subtotal 3 from pricing procedure for condition |
| `KZWI4` | KZWI4 | — | CURR | 13 | 2 | Subtotal 4 from pricing procedure for condition |
| `KZWI5` | KZWI5 | — | CURR | 13 | 2 | Subtotal 5 from pricing procedure for condition |
| `KZWI6` | KZWI6 | — | CURR | 13 | 2 | Subtotal 6 from pricing procedure for condition |
| `STCUR` | STCUR_AP | — | DEC | 9 | 5 | Exchange rate for statistics (Exch.rate at time of creation) |
| `UVPRS` | UVPRS | — | CHAR | 1 | 0 | Incomplete with respect to pricing |
| `UVALL` | UVALL | — | CHAR | 1 | 0 | Generally incomplete |
| `EAN11` | EAN11 | — | CHAR | 18 | 0 | International Article Number (EAN/UPC) |
| `PRCTR` | PRCTR | — | CHAR | 10 | 0 | Profit Center |
| `KVGR1` | KVGR1 | TVV1 | CHAR | 3 | 0 | Customer group 1 |
| `KVGR2` | KVGR2 | TVV2 | CHAR | 3 | 0 | Customer group 2 |
| `KVGR3` | KVGR3 | TVV3 | CHAR | 3 | 0 | Customer group 3 |
| `KVGR4` | KVGR4 | TVV4 | CHAR | 3 | 0 | Customer group 4 |
| `KVGR5` | KVGR5 | TVV5 | CHAR | 3 | 0 | Customer group 5 |
| `MVGR1` | MVGR1 | TVM1 | CHAR | 3 | 0 | Material group 1 |
| `MVGR2` | MVGR2 | TVM2 | CHAR | 3 | 0 | Material group 2 |
| `MVGR3` | MVGR3 | TVM3 | CHAR | 3 | 0 | Material group 3 |
| `MVGR4` | MVGR4 | TVM4 | CHAR | 3 | 0 | Material group 4 |
| `MVGR5` | MVGR5 | TVM5 | CHAR | 3 | 0 | Material group 5 |
| `MATWA` | MATWA | MARA | CHAR | 18 | 0 | Material entered |
| `BONBA` | BONBA | — | CURR | 13 | 2 | Rebate basis 1 |
| `KOKRS` | KOKRS | TKA01 | CHAR | 4 | 0 | Controlling Area |
| `PAOBJNR` | RKEOBJNR | — | NUMC | 10 | 0 | Profitability Segment Number (CO-PA) |
| `PS_PSP_PNR` | PS_PSP_PNR | — | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `AUFNR` | AUFNR | AUFK | CHAR | 12 | 0 | Order Number |
| `TXJCD` | TXJCD | — | CHAR | 15 | 0 | Tax Jurisdiction |
| `CMPRE` | CMPRE | — | CURR | 11 | 2 | Item credit price |
| `CMPNT` | CMPNT | — | CHAR | 1 | 0 | ID: Item with active credit function / relevant for credit |
| `CUOBJ` | CUOBJ_VA | — | NUMC | 18 | 0 | Configuration |
| `CUOBJ_CH` | CUOBJ_CH | — | NUMC | 18 | 0 | Internal object number of the batch classification |
| `KOUPD` | KOUPD | — | CHAR | 1 | 0 | Condition update |
| `UECHA` | UECHA | — | NUMC | 6 | 0 | Higher-Level Item of Batch Split Item |
| `XCHAR` | XCHAR | — | CHAR | 1 | 0 | Batch management indicator (internal) |
| `ABRVW` | ABRVW | TVLV | CHAR | 3 | 0 | Usage Indicator |
| `SERNR` | SERNR | SNUM | CHAR | 8 | 0 | BOM explosion number |
| `BZIRK_AUFT` | BZIRK_AUFT | T171 | CHAR | 6 | 0 | Sales district of sales order |
| `KDGRP_AUFT` | KDGRP_AUFT | T151 | CHAR | 2 | 0 | Customer group of sales order |
| `KONDA_AUFT` | KONDA_AUFT | T188 | CHAR | 2 | 0 | Price group of sales order |
| `LLAND_AUFT` | LLAND_AUFT | T005 | CHAR | 3 | 0 | Country of destination of sales order |
| `MPROK` | MPROK | — | CHAR | 1 | 0 | Status manual price change |
| `PLTYP_AUFT` | PLTYP_AUFT | T189 | CHAR | 2 | 0 | Price list type of sales order |
| `REGIO_AUFT` | REGIO_AUFT | T005S | CHAR | 3 | 0 | Region of sales order |
| `VKORG_AUFT` | VKORG_AUFT | TVKO | CHAR | 4 | 0 | Sales organization of sales order |
| `VTWEG_AUFT` | VTWEG_AUFT | TVTW | CHAR | 2 | 0 | Distribution channel of sales order |
| `ABRBG` | ABRBG | — | DATS | 8 | 0 | Start of accounting settlement period |
| `PROSA` | PROSA | — | CHAR | 1 | 0 | ID for material determination |
| `UEPVW` | UEPVW | — | CHAR | 1 | 0 | ID for higher-level item usage |
| `AUTYP` | VBTYP | — | CHAR | 1 | 0 | SD document category |
| `STADAT` | STADAT | — | DATS | 8 | 0 | Statistics date |
| `FPLNR` | FPLNR | FPLA | CHAR | 10 | 0 | Billing plan number / invoicing plan number |
| `FPLTR` | FPLTR | — | NUMC | 6 | 0 | Item for billing plan/invoice plan/payment cards |
| `AKTNR` | WAKTION | WAKH | CHAR | 10 | 0 | Promotion |
| `KNUMA_PI` | KNUMA_PI | KONA | CHAR | 10 | 0 | Promotion |
| `KNUMA_AG` | KNUMA_AG | KONA | CHAR | 10 | 0 | Sales deal |
| `PREFE` | PREFE | — | CHAR | 1 | 0 | Preference indicator in export/import |
| `MWSBP` | MWSBP | — | CURR | 13 | 2 | Tax amount in document currency |
| `AUGRU_AUFT` | AUGRU | TVAU | CHAR | 3 | 0 | Order reason (reason for the business transaction) |
| `FAREG` | FAREG | — | CHAR | 1 | 0 | Rule in billing plan/invoice plan |
| `UPMAT` | UPMAT | MARA | CHAR | 18 | 0 | Pricing reference material of main item |
| `UKONM` | UKONM | T178 | CHAR | 2 | 0 | Material pricing group of main item |
| `CMPRE_FLT` | CMPRE_FLT | — | FLTP | 16 | 16 | Item credit price |
| `ABFOR` | ABSFORM_CM | T691K | CHAR | 2 | 0 | Form of payment guarantee |
| `ABGES` | ABGES_CM | — | FLTP | 16 | 16 | Guaranteed (factor between 0 and 1) |
| `J_1ARFZ` | J_1ARFZVAT | J_1ARFZ | CHAR | 1 | 0 | Reason for zero VAT |
| `J_1AREGIO` | REGIO | T005S | CHAR | 3 | 0 | Region (State, Province, County) |
| `J_1AGICD` | J_1AGICD_D | J_1AGICD | CHAR | 2 | 0 | Activity Code for Gross Income Tax |
| `J_1ADTYP` | J_1ADTYP_D | J_1ADTYP | CHAR | 2 | 0 | Distribution Type for Employment Tax |
| `J_1ATXREL` | J_1ATXREL_ | J_1ATXREL | CHAR | 10 | 0 | Tax relevant classification |
| `J_1BCFOP` | J_1BCFOP | J_1BAG | CHAR | 10 | 0 | CFOP Code and Extension |
| `J_1BTAXLW1` | J_1BTAXLW1 | J_1BATL1 | CHAR | 3 | 0 | Tax law: ICMS |
| `J_1BTAXLW2` | J_1BTAXLW2 | J_1BATL2 | CHAR | 3 | 0 | Tax law: IPI |
| `J_1BTXSDC` | J_1BTXSDC_ | J_1BTXSDC | CHAR | 2 | 0 | SD tax code |
| `BRTWR` | BRTWR_FP | — | CURR | 15 | 2 | Gross value of the billing item in document currency |
| `WKTNR` | WKTNR | VBUK | CHAR | 10 | 0 | Value contract no. |
| `WKTPS` | WKTPS | VBUP | NUMC | 6 | 0 | Value contract item |
| `RPLNR` | RPLNR_AU | FPLA | CHAR | 10 | 0 | Payment card plan number of sales document |
| `KURSK_DAT` | WWERT_D | — | DATS | 8 | 0 | Translation Date |
| `WGRU1` | WGRU_HIE1 | — | CHAR | 18 | 0 | Material group hierarchy 1 |
| `WGRU2` | WGRU_HIE2 | — | CHAR | 18 | 0 | Material group hierarchy 2 |
| `KDKG1` | KDKG1 | TVKGG | CHAR | 2 | 0 | Customer condition group 1 |
| `KDKG2` | KDKG2 | TVKGG | CHAR | 2 | 0 | Customer condition group 2 |
| `KDKG3` | KDKG3 | TVKGG | CHAR | 2 | 0 | Customer condition group 3 |
| `KDKG4` | KDKG4 | TVKGG | CHAR | 2 | 0 | Customer condition group 4 |
| `KDKG5` | KDKG5 | TVKGG | CHAR | 2 | 0 | Customer condition group 5 |
| `VKAUS` | ABRVW | TVLV | CHAR | 3 | 0 | Usage Indicator |
| `J_1AINDXP` | J_1AINDXP | J_1AINFT20 | CHAR | 5 | 0 | Inflation Index |
| `J_1AIDATEP` | J_1AIDATES | — | DATS | 8 | 0 | Indexing base date |
| `KZFME` | KZFME | — | CHAR | 1 | 0 | ID: Leading unit of measure for completing a transaction |
| `MWSKZ` | MWSKZ | — | CHAR | 2 | 0 | Tax on sales/purchases code |
| `VERTT` | RANTYP | — | CHAR | 1 | 0 | Contract Type |
| `VERTN` | RANL | — | CHAR | 13 | 0 | Contract Number |
| `SGTXT` | SGTXT | — | CHAR | 50 | 0 | Item Text |
| `DELCO` | DELCO | — | CHAR | 3 | 0 | Agreed delivery time |
| `BEMOT` | BEMOT | TBMOT | CHAR | 2 | 0 | Accounting Indicator |
| `RRREL` | RR_RELTYP | — | CHAR | 1 | 0 | Revenue recognition category |
| `AKKUR` | AKKUR | — | DEC | 9 | 5 | Exchange rate for letter-of-credit procg in foreign trade |
| `WMINR` | WMINR | WWMI | CHAR | 10 | 0 | Product catalog number |
| `VGBEL_EX` | VGBEL | — | CHAR | 10 | 0 | Document number of the reference document |
| `VGPOS_EX` | VGPOS | — | NUMC | 6 | 0 | Item number of the reference item |
| `LOGSYS` | LOGSYS | — | CHAR | 10 | 0 | Logical system |
| `VGTYP_EX` | VGTYP_EX | — | CHAR | 3 | 0 | Category of an external transaction or element |
| `J_1BTAXLW3` | J_1BTAXLW3 | J_1BATL3 | CHAR | 3 | 0 | ISS Tax Law |
| `J_1BTAXLW4` | J_1BTAXLW4 | J_1BATL4A | CHAR | 3 | 0 | COFINS Tax Law |
| `J_1BTAXLW5` | J_1BTAXLW5 | J_1BATL5 | CHAR | 3 | 0 | PIS Tax Law |
| `MSR_ID` | MSR_PROCESS_ID | — | CHAR | 10 | 0 | Process Identification Number |
| `MSR_REFUND_CODE` | MSR_RETURNS_REFUND_CODE | MSR_C_RET_REFUND | CHAR | 3 | 0 | Returns Refund Code |
| `MSR_RET_REASON` | MSR_RETURNS_REASON | MSR_C_RET_REASON | CHAR | 3 | 0 | Return Reason |
| `NRAB_KNUMH` | KNUMH | — | CHAR | 10 | 0 | Condition record number |
| `NRAB_VALUE` | KWERT | — | CURR | 13 | 2 | Condition value |
| `DISPUTE_CASE` | DISPUTE_CASE | — | RAW | 16 | 0 | Dispute Case |
| `FUND_USAGE_ITEM` | FUND_USAGE_ITEM | — | RAW | 16 | 0 | Fund Usage Item |
| `CLAIMS_TAXATION` | CLAIMS_TAXATION | — | CHAR | 1 | 0 | Claims Taxation |
| `KURRF_DAT_ORIG` | WWERT_D | — | DATS | 8 | 0 | Translation Date |
| `VGTYP_EXT` | TDD_VBTYP_EXT_V | — | CHAR | 4 | 0 | Extension of SD document category of preceding document |
| `Z_PRS_OFFSHORE` | Z_PRS_OFFSHORE | — | CHAR | 1 | 0 | Professional Services: Delivery Type |
| `Z_PRS_BILL_FLAG` | Z_PRS_BILLABLE_FLAG | — | CHAR | 1 | 0 | Professional Services: Billable/Non-Billable |
| `Z_PRS_COUNTRY` | LAND1 | — | CHAR | 3 | 0 | Country Key |
| `Z_PRS_CHARGELEVL` | Z_PRS_CHARGELEVEL | — | CHAR | 2 | 0 | Professional Services: Charge Level |
| `/CWM/MENGE` | /CWM/MENGE | — | QUAN | 13 | 3 | Quantity in Parallel Unit of Measure |
| `/CWM/MEINS` | /CWM/MEINS | — | UNIT | 3 | 0 | Parallel Unit of Measure |
| `AUFPL` | CO_AUFPL | — | NUMC | 10 | 0 | Routing number of operations in the order |
| `APLZL` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `DPCNR` | /SAPPCE/DPCNR | — | CHAR | 10 | 0 | Down Payment Chain Number |
| `DCPNR` | /SAPPCE/DPCPNR | — | NUMC | 3 | 0 | Transaction Number |
| `DPNRB` | /SAPPCE/DPCPNRB | — | NUMC | 3 | 0 | Sequence Number of Accounting Document in Transaction |
| `PEROP_BEG` | FM_PEROP_SD_LOW | — | DATS | 8 | 0 | Period of Performance Start Date |
| `PEROP_END` | FM_PEROP_SD_HIGH | — | DATS | 8 | 0 | Period of Performance End Date |
| `FONDS` | BP_GEBER | — | CHAR | 10 | 0 | Fund |
| `FISTL` | FISTL | — | CHAR | 16 | 0 | Funds Center |
| `FKBER` | FKBER | — | CHAR | 16 | 0 | Functional Area |
| `GRANT_NBR` | GM_GRANT_NBR | — | CHAR | 20 | 0 | Grant |
| `BUDGET_PD` | FM_BUDGET_PERIOD | — | CHAR | 10 | 0 | FM: Budget Period |
| `OIEDOK` | OIH_EDOK | — | CHAR | 1 | 0 | Excise duty validation indicator |
| `OID_EXTBOL` | OID_EXTBOL | — | CHAR | 16 | 0 | External bill of lading |
| `OID_MISCDL` | OID_MISCDL | — | CHAR | 16 | 0 | Miscellaneous delivery number |
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
| `CMETH` | OIB_CMETH | — | CHAR | 1 | 0 | Quantity Conversion Method |
| `OITAXFROM` | OIH_TAXFRO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;from&#039; location |
| `OIHANTYP` | OIH_HANTYP | OIH5 | CHAR | 2 | 0 | Excise Duty Handling Type |
| `OITAXGRP` | OIH_TAXGRP | OIH2 | CHAR | 2 | 0 | Excise Duty Group |
| `OITAXTO` | OIH_TAXTO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;to&#039; location |
| `OICERTF1` | OIH_CERTF1 | — | CHAR | 15 | 0 | Excise tax external license number |
| `OIOILCON` | OIH_OILCON | — | DEC | 5 | 2 | Oil content in a material as a percentage |
| `OIDATFM1` | OIH_DATFM1 | — | DATS | 8 | 0 | Excise Duty License Valid from Date |
| `OIDATTO1` | OIH_DATTO1 | — | DATS | 8 | 0 | Valid to date for excise duty tax certificate |
| `OIEDBAL` | OIH_EDBAL | — | CHAR | 1 | 0 | Excise duty balancing is required (indicator) |
| `OIPRICIE` | OIH_PRICIE | — | CHAR | 1 | 0 | ED pricing: external (indicator) |
| `OIINEX` | OIH_INEX | OIH16 | CHAR | 2 | 0 | Code for internal or external excise duty rate determination |
| `OIEDBALM` | OIH_EDBALM | — | CHAR | 1 | 0 | Excise duty balancing method indicator |
| `OITAXLOD` | OIH_TAXLOD | — | CURR | 13 | 2 | Excise duty tax value for goods loading |
| `OITAXISS` | OIH_TAXISS | — | CURR | 13 | 2 | Excise duty value for goods issue |
| `OITAXINV` | OIH_TAXINV | — | CURR | 13 | 2 | Excise duty tax value for an invoice |
| `OIDRC` | OIC_DRC | — | CHAR | 5 | 0 | Differential Reference Code (DRC) |
| `OIC_DRCTRY` | OIC_DRCTRY | — | CHAR | 3 | 0 | DRC country |
| `OIC_DRCREG` | OIC_DRCREG | — | CHAR | 3 | 0 | DRC region |
| `OIMETIND` | OIC_METIND | — | CHAR | 4 | 0 | Metropolitan indicator |
| `OIWAP` | OIC_WAP | — | CHAR | 3 | 0 | Wide-area pricing zone |
| `OISLF` | OIC_SLF | — | CHAR | 3 | 0 | State license fee zone |
| `OIPSDRC` | OIC_PSDRC | — | CHAR | 5 | 0 | Pricing DRC (grouping customers by DRC for pricing) |
| `OICONTNR` | OIC_CONTNR | — | CHAR | 10 | 0 | Outline agreement: contract |
| `OIC_KMPOS` | OIC_KMPOS | — | NUMC | 6 | 0 | Reference contract line item number |
| `OIC_TIME` | OIC_TIME | — | TIMS | 6 | 0 | Time for time-pricing |
| `OIC_DATE` | OIC_DATE | — | DATS | 8 | 0 | Date for time pricing |
| `OIFEECH` | OIA_FEECH | — | CHAR | 1 | 0 | Fee edit control |
| `OIEXGNUM` | OIA_EXGNUM | — | CHAR | 10 | 0 | Exchange agreement number |
| `OIEXGTYP` | OIA_EXGTYP | TOIA2 | CHAR | 4 | 0 | Exchange type |
| `OIFEETOT` | OIA_FEETOT | — | CURR | 13 | 2 | Fee total |
| `OIFEEDT` | OIA_FEEDT | — | DATS | 8 | 0 | Fee pricing condition date |
| `OINETCYC` | OIA_NETCYC | T008 | CHAR | 1 | 0 | Netting cycle (FI blocking indicator) |
| `OIH_LICTP` | OIH_LICTP | OIH20 | CHAR | 4 | 0 | License type |
| `OIH_LICIN` | OIH_LICIN | OIHL | CHAR | 10 | 0 | Excise tax internal license number |
| `OIH_LCFOL` | OIH_LCFOL | OIHL | CHAR | 10 | 0 | Follow-on license for quantity license |
| `OIH_FOLQTY` | OIH_FOLQTY | — | QUAN | 13 | 3 | Excise Tax Follow-On License Quantity |
| `OIPBL` | OIF_PBLNR | OIFSPBL | CHAR | 10 | 0 | Business location identifier (IS-Oil MRN) |
| `OISBREL` | OIA_SBREL | — | NUMC | 3 | 0 | Sub product/ base product relevence indicator |
| `OIBASPROD` | OIA_SBMAT | — | CHAR | 18 | 0 | Base product number |
| `OITITLE` | OIC_TITLE | — | CHAR | 1 | 0 | Location of title transfer for Incoterms purposes |
| `OIGNRULE` | OIC_GNRULE | — | NUMC | 3 | 0 | Gross/net pricing rule |
| `OIA_IPMVAT` | OIA_IPMVAT | — | CHAR | 1 | 0 | VAT on internally-posted material |
| `OIINVCYC1` | OIA_INCYCA | — | CHAR | 1 | 0 | Invoice cycle indicator active (X/ ) |
| `OIINVCYC2` | OIA_INCYCA | — | CHAR | 1 | 0 | Invoice cycle indicator active (X/ ) |
| `OIINVCYC3` | OIA_INCYCA | — | CHAR | 1 | 0 | Invoice cycle indicator active (X/ ) |
| `OIINVCYC4` | OIA_INCYCA | — | CHAR | 1 | 0 | Invoice cycle indicator active (X/ ) |
| `OIINVCYC5` | OIA_INCYCA | — | CHAR | 1 | 0 | Invoice cycle indicator active (X/ ) |
| `OIINVCYC6` | OIA_INCYCA | — | CHAR | 1 | 0 | Invoice cycle indicator active (X/ ) |
| `OIINVCYC7` | OIA_INCYCA | — | CHAR | 1 | 0 | Invoice cycle indicator active (X/ ) |
| `OIINVCYC8` | OIA_INCYCA | — | CHAR | 1 | 0 | Invoice cycle indicator active (X/ ) |
| `OIINVCYC9` | OIA_INCYCA | — | CHAR | 1 | 0 | Invoice cycle indicator active (X/ ) |
| `OILIKWTF` | OIA_OLIKWT | — | CURR | 19 | 2 | Open delivery credit value transferred during billing |
| `OILIMETF` | OIA_OLIMET | — | QUAN | 15 | 3 | Open delivery quantity transferred during billing |
| `OIFKIMG` | FKIMG | — | QUAN | 13 | 3 | Actual Invoiced Quantity |
| `OISMENG` | SMENG | — | QUAN | 13 | 3 | Scale quantity in base unit of measure |
| `OIFKLMG` | FKLMG | — | QUAN | 13 | 3 | Billing quantity in stockkeeping unit |
| `OILMENG` | LMENG | — | QUAN | 13 | 3 | Required quantity for mat.management in stockkeeping units |
| `OINTGEW` | NTGEW_15 | — | QUAN | 15 | 3 | Net weight |
| `OIBRGEW` | BRGEW_15 | — | QUAN | 15 | 3 | Gross weight |
| `OIVOLUM` | VOLUM_15 | — | QUAN | 15 | 3 | Volume |
| `OIHFOLQTY` | OIH_FOLQTY | — | QUAN | 13 | 3 | Excise Tax Follow-On License Quantity |
| `OIVMENG` | OIC_VMENG | — | QUAN | 13 | 3 | Req. quantity for mat.management in base uom (stand. conv.) |
| `OISTYP` | OIRA_STYP | — | CHAR | 4 | 0 | Service type |
| `OIRELPCGROUP` | OIRE_LPCGROUP | — | CHAR | 4 | 0 | Location Payment Card Grouping |
| `OIU_RUN_TKT_NO` | — | — | CHAR | 7 | 0 | OIU_RUN_TKT_NO |
| `OIU_A_H_VAL_FCT` | — | — | QUAN | 13 | 3 | OIU_A_H_VAL_FCT |
| `OIU_A_H_VAL_F_U` | — | — | UNIT | 3 | 0 | OIU_A_H_VAL_F_U |
| `OIU_GRV_AM` | — | — | FLTP | 16 | 16 | OIU_GRV_AM |
| `OIU_DENSITY_U` | — | — | UNIT | 3 | 0 | OIU_DENSITY_U |
| `OIU_SALE_DT_FROM` | — | — | DATS | 8 | 0 | OIU_SALE_DT_FROM |
| `OIU_SALE_DT_TO` | — | — | DATS | 8 | 0 | OIU_SALE_DT_TO |
| `OIU_PC_WC_NO` | — | — | CHAR | 5 | 0 | OIU_PC_WC_NO |
| `OIU_PC_MP_NO` | — | — | CHAR | 20 | 0 | OIU_PC_MP_NO |
| `OIU_PC_WL_NO` | — | — | CHAR | 15 | 0 | OIU_PC_WL_NO |
| `OIU_DENSTYP` | — | — | CHAR | 1 | 0 | OIU_DENSTYP |
| `OIU_VLTXNS_NO` | — | — | NUMC | 12 | 0 | OIU_VLTXNS_NO |
| `OIU_POS_NO` | — | — | NUMC | 3 | 0 | OIU_POS_NO |
| `OIU_TRNSP_NO` | — | — | CHAR | 10 | 0 | OIU_TRNSP_NO |
| `OIU_TRNSP_REF_NO` | — | — | CHAR | 25 | 0 | OIU_TRNSP_REF_NO |
| `OIU_ORIG_MP_NO` | — | — | CHAR | 20 | 0 | OIU_ORIG_MP_NO |
| `PRS_WORK_PERIOD` | PRS_WORK_PERIOD | — | NUMC | 7 | 0 | Work Period (Internal Representation) |
| `PPRCTR` | PPRCTR | — | CHAR | 10 | 0 | Partner Profit Center |
| `PARGB` | PARGB | — | CHAR | 4 | 0 | Trading partner&#039;s business area |
| `AUFPL_OAA` | CO_AUFPL | — | NUMC | 10 | 0 | Routing number of operations in the order |
| `APLZL_OAA` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `CAMPAIGN` | CGPL_GUID16_R3 | — | RAW | 16 | 0 | Generic project planning: GUID from external R/3 system |
| `COMPREAS` | CMP_COMPREAS_COPY | — | CHAR | 4 | 0 | Abbreviation for Complaints Reason |
| `YYCALLID` | YCALLID | — | CHAR | 3 | 0 | Call Center ID |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABFOR` | VBRP | ABFOR | T691K |  | |
| `ABFOR` | VBRP | MANDT | T691K |  | |
| `ABRVW` | VBRP | MANDT | TVLV |  | |
| `ABRVW` | VBRP | ABRVW | TVLV |  | |
| `AKTNR` | VBRP | AKTNR | WAKH |  | |
| `AKTNR` | VBRP | MANDT | WAKH |  | |
| `ALAND` | VBRP | MANDT | T005 |  | |
| `ALAND` | VBRP | ALAND | T005 |  | |
| `AUBEL` | VBRP | MANDT | VBUK |  | |
| `AUBEL` | VBRP | AUBEL | VBUK |  | |
| `AUFNR` | VBRP | MANDT | AUFK |  | |
| `AUFNR` | VBRP | AUFNR | AUFK |  | |
| `AUGRU_AUFT` | VBRP | MANDT | TVAU |  | |
| `AUGRU_AUFT` | VBRP | AUGRU_AUFT | TVAU |  | |
| `AUPOS` | VBRP | MANDT | VBUP |  | |
| `AUPOS` | VBRP | AUBEL | VBUP |  | |
| `AUPOS` | VBRP | AUPOS | VBUP |  | |
| `BEMOT` | VBRP | MANDT | TBMOT |  | |
| `BEMOT` | VBRP | BEMOT | TBMOT |  | |
| `BONUS` | VBRP | BONUS | TVBO |  | |
| `BONUS` | VBRP | MANDT | TVBO |  | |
| `BWTAR` | VBRP | BWTAR | T149D |  | |
| `BWTAR` | VBRP | MANDT | T149D |  | |
| `BZIRK_AUFT` | VBRP | MANDT | T171 |  | |
| `BZIRK_AUFT` | VBRP | BZIRK_AUFT | T171 |  | |
| `CHARG` | VBRP | WERKS | MCHA |  | |
| `CHARG` | VBRP | CHARG | MCHA |  | |
| `CHARG` | VBRP | MANDT | MCHA |  | |
| `CHARG` | VBRP | MATNR | MCHA |  | |
| `FPLNR` | VBRP | MANDT | FPLA |  | |
| `FPLNR` | VBRP | FPLNR | FPLA |  | |
| `GEWEI` | VBRP | MANDT | T006 |  | |
| `GEWEI` | VBRP | GEWEI | T006 |  | |
| `GSBER` | VBRP | MANDT | TGSB |  | |
| `GSBER` | VBRP | GSBER | TGSB |  | |
| `J_1ADTYP` | VBRP | MANDT | J_1ADTYP |  | |
| `J_1ADTYP` | VBRK | BUKRS | J_1ADTYP |  | |
| `J_1ADTYP` | VBRP | J_1ADTYP | J_1ADTYP |  | |
| `J_1AGICD` | VBRP | J_1AGICD | J_1AGICD |  | |
| `J_1AGICD` | VBRP | MANDT | J_1AGICD |  | |
| `J_1AGICD` | VBRP | ALAND | J_1AGICD |  | |
| `J_1AINDXP` | VBRP | MANDT | J_1AINFT20 |  | |
| `J_1AINDXP` | VBRP | J_1AINDXP | J_1AINFT20 |  | |
| `J_1AREGIO` | VBRP | ALAND | T005S |  | |
| `J_1AREGIO` | VBRP | J_1AREGIO | T005S |  | |
| `J_1AREGIO` | VBRP | MANDT | T005S |  | |
| `J_1ARFZ` | VBRP | MANDT | J_1ARFZ |  | |
| `J_1ARFZ` | VBRP | J_1ARFZ | J_1ARFZ |  | |
| `J_1ATXREL` | VBRP | MANDT | J_1ATXREL |  | |
| `J_1ATXREL` | VBRP | J_1ATXREL | J_1ATXREL |  | |
| `J_1BCFOP` | VBRP | MANDT | J_1BAG |  | |
| `J_1BCFOP` | VBRP | J_1BCFOP | J_1BAG |  | |
| `J_1BTAXLW1` | VBRP | MANDT | J_1BATL1 |  | |
| `J_1BTAXLW1` | VBRP | J_1BTAXLW1 | J_1BATL1 |  | |
| `J_1BTAXLW2` | VBRP | MANDT | J_1BATL2 |  | |
| `J_1BTAXLW2` | VBRP | J_1BTAXLW2 | J_1BATL2 |  | |
| `J_1BTAXLW3` | VBRP | MANDT | J_1BATL3 |  | |
| `J_1BTAXLW3` | VBRP | J_1BTAXLW3 | J_1BATL3 |  | |
| `J_1BTAXLW4` | VBRP | J_1BTAXLW4 | J_1BATL4A |  | |
| `J_1BTAXLW4` | VBRP | MANDT | J_1BATL4A |  | |
| `J_1BTAXLW5` | VBRP | MANDT | J_1BATL5 |  | |
| `J_1BTAXLW5` | VBRP | J_1BTAXLW5 | J_1BATL5 |  | |
| `J_1BTXSDC` | VBRP | MANDT | J_1BTXSDC |  | |
| `J_1BTXSDC` | VBRP | J_1BTXSDC | J_1BTXSDC |  | |
| `KDGRP_AUFT` | VBRP | MANDT | T151 |  | |
| `KDGRP_AUFT` | VBRP | KDGRP_AUFT | T151 |  | |
| `KDKG1` | VBRP | MANDT | TVKGG |  | |
| `KDKG1` | VBRP | KDKG1 | TVKGG |  | |
| `KDKG2` | VBRP | MANDT | TVKGG |  | |
| `KDKG2` | VBRP | KDKG2 | TVKGG |  | |
| `KDKG3` | VBRP | MANDT | TVKGG |  | |
| `KDKG3` | VBRP | KDKG3 | TVKGG |  | |
| `KDKG4` | VBRP | KDKG4 | TVKGG |  | |
| `KDKG4` | VBRP | MANDT | TVKGG |  | |
| `KDKG5` | VBRP | MANDT | TVKGG |  | |
| `KDKG5` | VBRP | KDKG5 | TVKGG |  | |
| `KNUMA_AG` | VBRP | MANDT | KONA |  | |
| `KNUMA_AG` | VBRP | KNUMA_AG | KONA |  | |
| `KNUMA_PI` | VBRP | MANDT | KONA |  | |
| `KNUMA_PI` | VBRP | KNUMA_PI | KONA |  | |
| `KOKRS` | VBRP | MANDT | TKA01 |  | |
| `KOKRS` | VBRP | KOKRS | TKA01 |  | |
| `KONDA_AUFT` | VBRP | MANDT | T188 |  | |
| `KONDA_AUFT` | VBRP | KONDA_AUFT | T188 |  | |
| `KONDM` | VBRP | MANDT | T178 |  | |
| `KONDM` | VBRP | KONDM | T178 |  | |
| `KTGRM` | VBRP | KTGRM | TVKM |  | |
| `KTGRM` | VBRP | MANDT | TVKM |  | |
| `KVGR1` | VBRP | KVGR1 | TVV1 |  | |
| `KVGR1` | VBRP | MANDT | TVV1 |  | |
| `KVGR2` | VBRP | MANDT | TVV2 |  | |
| `KVGR2` | VBRP | KVGR2 | TVV2 |  | |
| `KVGR3` | VBRP | MANDT | TVV3 |  | |
| `KVGR3` | VBRP | KVGR3 | TVV3 |  | |
| `KVGR4` | VBRP | KVGR4 | TVV4 |  | |
| `KVGR4` | VBRP | MANDT | TVV4 |  | |
| `KVGR5` | VBRP | MANDT | TVV5 |  | |
| `KVGR5` | VBRP | KVGR5 | TVV5 |  | |
| `LGORT` | VBRP | MANDT | T001L |  | |
| `LGORT` | VBRP | WERKS | T001L |  | |
| `LGORT` | VBRP | LGORT | T001L |  | |
| `LLAND_AUFT` | VBRP | MANDT | T005 |  | |
| `LLAND_AUFT` | VBRP | LLAND_AUFT | T005 |  | |
| `MANDT` | VBRP | MANDT | T000 |  | |
| `MATKL` | VBRP | MANDT | T023 |  | |
| `MATKL` | VBRP | MATKL | T023 |  | |
| `MATNR` | VBRP | MANDT | MARA |  | |
| `MATNR` | VBRP | MATNR | MARA |  | |
| `MATWA` | VBRP | MANDT | MARA |  | |
| `MATWA` | VBRP | MATWA | MARA |  | |
| `MEINS` | VBRP | MANDT | T006 |  | |
| `MEINS` | VBRP | MEINS | T006 |  | |
| `MSR_REFUND_CODE` | VBRP | MANDT | MSR_C_RET_REFUND |  | |
| `MSR_REFUND_CODE` | VBRP | MSR_REFUND_CODE | MSR_C_RET_REFUND |  | |
| `MSR_RET_REASON` | VBRP | MANDT | MSR_C_RET_REASON |  | |
| `MSR_RET_REASON` | VBRP | MSR_RET_REASON | MSR_C_RET_REASON |  | |
| `MVGR1` | VBRP | MANDT | TVM1 |  | |
| `MVGR1` | VBRP | MVGR1 | TVM1 |  | |
| `MVGR2` | VBRP | MVGR2 | TVM2 |  | |
| `MVGR2` | VBRP | MANDT | TVM2 |  | |
| `MVGR3` | VBRP | MANDT | TVM3 |  | |
| `MVGR3` | VBRP | MVGR3 | TVM3 |  | |
| `MVGR4` | VBRP | MANDT | TVM4 |  | |
| `MVGR4` | VBRP | MVGR4 | TVM4 |  | |
| `MVGR5` | VBRP | MVGR5 | TVM5 |  | |
| `MVGR5` | VBRP | MANDT | TVM5 |  | |
| `OIC_DCITYC` | SYST | MANDT | T005G |  | |
| `OIC_DCITYC` | VBRP | OIC_DLAND1 | T005G |  | |
| `OIC_DCITYC` | VBRP | OIC_DREGIO | T005G |  | |
| `OIC_DCITYC` | VBRP | OIC_DCITYC | T005G |  | |
| `OIC_DCOUNC` | VBRP | OIC_DLAND1 | T005E |  | |
| `OIC_DCOUNC` | VBRP | OIC_DREGIO | T005E |  | |
| `OIC_DCOUNC` | VBRP | OIC_DCOUNC | T005E |  | |
| `OIC_DCOUNC` | SYST | MANDT | T005E |  | |
| `OIC_DLAND1` | SYST | MANDT | T005 |  | |
| `OIC_DLAND1` | VBRP | OIC_DLAND1 | T005 |  | |
| `OIC_DREGIO` | SYST | MANDT | T005S |  | |
| `OIC_DREGIO` | VBRP | OIC_DLAND1 | T005S |  | |
| `OIC_DREGIO` | VBRP | OIC_DREGIO | T005S |  | |
| `OIC_LIFNR` | SYST | MANDT | LFA1 |  | |
| `OIC_LIFNR` | VBRP | OIC_LIFNR | LFA1 |  | |
| `OIC_MOT` | SYST | MANDT | TVTR |  | |
| `OIC_MOT` | VBRP | OIC_MOT | TVTR |  | |
| `OIC_OCITYC` | SYST | MANDT | T005G |  | |
| `OIC_OCITYC` | VBRP | OIC_OLAND1 | T005G |  | |
| `OIC_OCITYC` | VBRP | OIC_OREGIO | T005G |  | |
| `OIC_OCITYC` | VBRP | OIC_OCITYC | T005G |  | |
| `OIC_OCOUNC` | VBRP | OIC_OREGIO | T005E |  | |
| `OIC_OCOUNC` | VBRP | OIC_OCOUNC | T005E |  | |
| `OIC_OCOUNC` | SYST | MANDT | T005E |  | |
| `OIC_OCOUNC` | VBRP | OIC_OLAND1 | T005E |  | |
| `OIC_OLAND1` | SYST | MANDT | T005 |  | |
| `OIC_OLAND1` | VBRP | OIC_OLAND1 | T005 |  | |
| `OIC_OREGIO` | SYST | MANDT | T005S |  | |
| `OIC_OREGIO` | VBRP | OIC_OLAND1 | T005S |  | |
| `OIC_OREGIO` | VBRP | OIC_OREGIO | T005S |  | |
| `OIEXGTYP` | SYST | MANDT | TOIA2 |  | |
| `OIEXGTYP` | VBRP | OIEXGTYP | TOIA2 |  | |
| `OIHANTYP` | T000 | MANDT | OIH5 |  | |
| `OIHANTYP` | VBRP | OIHANTYP | OIH5 |  | |
| `OIH_LCFOL` | VBRP | OIH_LICTP | OIHL |  | |
| `OIH_LCFOL` | VBRP | MANDT | OIHL |  | |
| `OIH_LCFOL` | VBRP | OIH_LCFOL | OIHL |  | |
| `OIH_LICIN` | VBRP | MANDT | OIHL |  | |
| `OIH_LICIN` | VBRP | OIH_LICIN | OIHL |  | |
| `OIH_LICIN` | VBRP | OIH_LICTP | OIHL |  | |
| `OIH_LICTP` | VBRP | MANDT | OIH20 |  | |
| `OIH_LICTP` | VBRP | OIH_LICTP | OIH20 |  | |
| `OIINEX` | T000 | MANDT | OIH16 |  | |
| `OIINEX` | VBRP | OIINEX | OIH16 |  | |
| `OINETCYC` | SYST | MANDT | T008 |  | |
| `OINETCYC` | VBRP | OINETCYC | T008 |  | |
| `OIPBL` | VBRP | MANDT | OIFSPBL |  | |
| `OIPBL` | VBRP | OIPBL | OIFSPBL |  | |
| `OITAXFROM` | T000 | MANDT | OIH4 |  | |
| `OITAXFROM` | VBRP | OITAXFROM | OIH4 |  | |
| `OITAXGRP` | VBRP | OITAXGRP | OIH2 |  | |
| `OITAXGRP` | T000 | MANDT | OIH2 |  | |
| `OITAXTO` | T000 | MANDT | OIH4 |  | |
| `OITAXTO` | VBRP | OITAXTO | OIH4 |  | |
| `PLTYP_AUFT` | VBRP | MANDT | T189 |  | |
| `PLTYP_AUFT` | VBRP | PLTYP_AUFT | T189 |  | |
| `PMATN` | VBRP | PMATN | MARA |  | |
| `PMATN` | VBRP | MANDT | MARA |  | |
| `POSNR` | VBRP | MANDT | VBUP |  | |
| `POSNR` | VBRP | VBELN | VBUP |  | |
| `POSNR` | VBRP | POSNR | VBUP |  | |
| `POSNV` | VBRP | POSNV | VBUP |  | |
| `POSNV` | VBRP | MANDT | VBUP |  | |
| `POSNV` | VBRP | VBELV | VBUP |  | |
| `POSPA` | VBRP | MANDT | VBUP |  | |
| `POSPA` | VBRP | AUBEL | VBUP |  | |
| `POSPA` | VBRP | POSPA | VBUP |  | |
| `PRODH` | VBRP | PRODH | T179 |  | |
| `PRODH` | VBRP | MANDT | T179 |  | |
| `PROVG` | VBRP | MANDT | TVPR |  | |
| `PROVG` | VBRP | PROVG | TVPR |  | |
| `REGIO_AUFT` | VBRP | MANDT | T005S |  | |
| `REGIO_AUFT` | VBRP | LLAND_AUFT | T005S |  | |
| `REGIO_AUFT` | VBRP | REGIO_AUFT | T005S |  | |
| `RPLNR` | VBRP | MANDT | FPLA |  | |
| `RPLNR` | VBRP | RPLNR | FPLA |  | |
| `SERNR` | VBRP | SERNR | SNUM |  | |
| `SERNR` | VBRP | MANDT | SNUM |  | |
| `SPARA` | VBRP | SPARA | TSPA |  | |
| `SPARA` | VBRP | MANDT | TSPA |  | |
| `SPART` | VBRP | MANDT | TSPA |  | |
| `SPART` | VBRP | SPART | TSPA |  | |
| `UEPOS` | VBRP | VBELN | VBUP |  | |
| `UEPOS` | VBRP | UEPOS | VBUP |  | |
| `UEPOS` | VBRP | MANDT | VBUP |  | |
| `UKONM` | VBRP | MANDT | T178 |  | |
| `UKONM` | VBRP | UKONM | T178 |  | |
| `UPMAT` | VBRP | MANDT | MARA |  | |
| `UPMAT` | VBRP | UPMAT | MARA |  | |
| `VBELN` | VBRP | MANDT | VBUK |  | |
| `VBELN` | VBRP | VBELN | VBUK |  | |
| `VBELV` | VBRP | MANDT | VBUK |  | |
| `VBELV` | VBRP | VBELV | VBUK |  | |
| `VGBEL` | VBRP | VGBEL | VBUK |  | |
| `VGBEL` | VBRP | MANDT | VBUK |  | |
| `VGPOS` | VBRP | MANDT | VBUP |  | |
| `VGPOS` | VBRP | VGBEL | VBUP |  | |
| `VGPOS` | VBRP | VGPOS | VBUP |  | |
| `VKAUS` | VBRP | MANDT | TVLV |  | |
| `VKAUS` | VBRP | VKAUS | TVLV |  | |
| `VKBUR` | VBRP | MANDT | TVBUR |  | |
| `VKBUR` | VBRP | VKBUR | TVBUR |  | |
| `VKGRP` | VBRP | MANDT | TVKGR |  | |
| `VKGRP` | VBRP | VKGRP | TVKGR |  | |
| `VKORG_AUFT` | VBRP | MANDT | TVKO |  | |
| `VKORG_AUFT` | VBRP | VKORG_AUFT | TVKO |  | |
| `VOLEH` | VBRP | MANDT | T006 |  | |
| `VOLEH` | VBRP | VOLEH | T006 |  | |
| `VRKME` | VBRP | VRKME | T006 |  | |
| `VRKME` | VBRP | MANDT | T006 |  | |
| `VSTEL` | VBRP | MANDT | TVST |  | |
| `VSTEL` | VBRP | VSTEL | TVST |  | |
| `VTWEG_AUFT` | VBRP | MANDT | TVTW |  | |
| `VTWEG_AUFT` | VBRP | VTWEG_AUFT | TVTW |  | |
| `WERKS` | VBRP | MANDT | T001W |  | |
| `WERKS` | VBRP | WERKS | T001W |  | |
| `WKREG` | VBRP | MANDT | T005S |  | |
| `WKREG` | VBRP | ALAND | T005S |  | |
| `WKREG` | VBRP | WKREG | T005S |  | |
| `WKTNR` | VBRP | MANDT | VBUK |  | |
| `WKTNR` | VBRP | WKTNR | VBUK |  | |
| `WKTPS` | VBRP | WKTNR | VBUP |  | |
| `WKTPS` | VBRP | WKTPS | VBUP |  | |
| `WKTPS` | VBRP | MANDT | VBUP |  | |
| `WMINR` | VBRP | MANDT | WWMI |  | |
| `WMINR` | VBRP | WMINR | WWMI |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `aubel`, `aupos`, `erdat`, `erzet`, `matnr`, `netwr`, `posnr`, `vbeln`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `aubel`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `ziscs0523_f01.txt`
- `zisfi0030.txt`
- `zisfi0235.txt`
- `zissd00002.txt`
- `zissd00004.txt`
- `zissd00006.txt`
- `zissd00007.txt`
- `zissd00011.txt`
- `zissd00016.txt`
- `zissd00023.txt`
- `zissd00045.txt`
- `zissd00048.txt`
- `zissd00050.txt`
- `zissd00054.txt`
- `zissd00072.txt`
- `zsdbidl01.txt`
- `zsdbidl02.txt`
- `zsdisqry02.txt`
- `zsdslcrm01.txt`
- `zsdsodl05.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_