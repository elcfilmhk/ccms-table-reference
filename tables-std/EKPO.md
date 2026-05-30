# `EKPO`

**Description:** Purchasing Document Item — PO item
**Category:** Standard SAP Table
**References:** 42 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/ekpo/) — validated 2026-05-30, schema v1.0
**Schema fields:** 357 fields | **Data types:** CHAR(251), CURR(25), DATS(16), DEC(19), INT4(1), NUMC(25), QUAN(13), TIMS(1), UNIT(6)

## Key Fields
`MATNR` | `BUKRS` | `KUNNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `LOEKZ` | ELOEK | — | CHAR | 1 | 0 | Deletion Indicator in Purchasing Document |
| `STATU` | ASTAT | — | CHAR | 1 | 0 | RFQ status |
| `AEDAT` | PAEDT | — | DATS | 8 | 0 | Purchasing Document Item Change Date |
| `TXZ01` | TXZ01 | — | CHAR | 40 | 0 | Short Text |
| `MATNR` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `EMATN` | EMATNR | MARA | CHAR | 18 | 0 | Material Number |
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `WERKS` | EWERK | T001W | CHAR | 4 | 0 | Plant |
| `LGORT` | LGORT_D | T001L | CHAR | 4 | 0 | Storage Location |
| `BEDNR` | BEDNR | — | CHAR | 10 | 0 | Requirement Tracking Number |
| `MATKL` | MATKL | T023 | CHAR | 9 | 0 | Material Group |
| `INFNR` | INFNR | EINA | CHAR | 10 | 0 | Number of Purchasing Info Record |
| `IDNLF` | IDNLF | — | CHAR | 35 | 0 | Material Number Used by Vendor |
| `KTMNG` | KTMNG | — | QUAN | 13 | 3 | Target Quantity |
| `MENGE` | BSTMG | — | QUAN | 13 | 3 | Purchase Order Quantity |
| `MEINS` | BSTME | T006 | UNIT | 3 | 0 | Purchase Order Unit of Measure |
| `BPRME` | BBPRM | T006 | UNIT | 3 | 0 | Order Price Unit (Purchasing) |
| `BPUMZ` | BPUMZ | — | DEC | 5 | 0 | Numerator for Conversion of Order Price Unit into Order Unit |
| `BPUMN` | BPUMN | — | DEC | 5 | 0 | Denominator for Conv. of Order Price Unit into Order Unit |
| `UMREZ` | UMBSZ | — | DEC | 5 | 0 | Numerator for Conversion of Order Unit to Base Unit |
| `UMREN` | UMBSN | — | DEC | 5 | 0 | Denominator for Conversion of Order Unit to Base Unit |
| `NETPR` | BPREI | — | CURR | 11 | 2 | Net Price in Purchasing Document (in Document Currency) |
| `PEINH` | EPEIN | — | DEC | 5 | 0 | Price Unit |
| `NETWR` | BWERT | — | CURR | 13 | 2 | Net Order Value in PO Currency |
| `BRTWR` | BBWERT | — | CURR | 13 | 2 | Gross order value in PO currency |
| `AGDAT` | ANGAB | — | DATS | 8 | 0 | Deadline for Submission of Bid/Quotation |
| `WEBAZ` | WEBAZ | — | DEC | 3 | 0 | Goods Receipt Processing Time in Days |
| `MWSKZ` | MWSKZ | T007A | CHAR | 2 | 0 | Tax on sales/purchases code |
| `BONUS` | EBONU | — | CHAR | 2 | 0 | Settlement Group 1 (Purchasing) |
| `INSMK` | INSMK | — | CHAR | 1 | 0 | Stock Type |
| `SPINF` | SPINF | — | CHAR | 1 | 0 | Indicator: Update Info Record |
| `PRSDR` | PRSDR | — | CHAR | 1 | 0 | Price Printout |
| `SCHPR` | SCHPR | — | CHAR | 1 | 0 | Indicator: Estimated Price |
| `MAHNZ` | MAHNZ | — | DEC | 3 | 0 | Number of Reminders/Expediters |
| `MAHN1` | MAHN1 | — | DEC | 3 | 0 | Number of Days for First Reminder/Expediter |
| `MAHN2` | MAHN2 | — | DEC | 3 | 0 | Number of Days for Second Reminder/Expediter |
| `MAHN3` | MAHN3 | — | DEC | 3 | 0 | Number of Days for Third Reminder/Expediter |
| `UEBTO` | UEBTO | — | DEC | 3 | 1 | Overdelivery Tolerance Limit |
| `UEBTK` | UEBTK | — | CHAR | 1 | 0 | Indicator: Unlimited Overdelivery Allowed |
| `UNTTO` | UNTTO | — | DEC | 3 | 1 | Underdelivery Tolerance Limit |
| `BWTAR` | BWTAR_D | T149D | CHAR | 10 | 0 | Valuation Type |
| `BWTTY` | BWTTY_D | T149C | CHAR | 1 | 0 | Valuation Category |
| `ABSKZ` | ABSKZ | — | CHAR | 1 | 0 | Rejection Indicator |
| `AGMEM` | AGMEM | TMAM | CHAR | 3 | 0 | Internal Comment on Quotation |
| `ELIKZ` | ELIKZ | — | CHAR | 1 | 0 | &quot;Delivery Completed&quot; Indicator |
| `EREKZ` | EREKZ | — | CHAR | 1 | 0 | Final Invoice Indicator |
| `PSTYP` | PSTYP | T163 | CHAR | 1 | 0 | Item Category in Purchasing Document |
| `KNTTP` | KNTTP | T163K | CHAR | 1 | 0 | Account Assignment Category |
| `KZVBR` | KZVBR | — | CHAR | 1 | 0 | Consumption Posting |
| `VRTKZ` | VRTKZ | — | CHAR | 1 | 0 | Distribution indicator for multiple account assignment |
| `TWRKZ` | TWRKZ | — | CHAR | 1 | 0 | Partial Invoice Indicator |
| `WEPOS` | WEPOS | — | CHAR | 1 | 0 | Goods Receipt Indicator |
| `WEUNB` | WEUNB | — | CHAR | 1 | 0 | Goods Receipt, Non-Valuated |
| `REPOS` | REPOS | — | CHAR | 1 | 0 | Invoice Receipt Indicator |
| `WEBRE` | WEBRE | — | CHAR | 1 | 0 | Indicator: GR-Based Invoice Verification |
| `KZABS` | KZABS | — | CHAR | 1 | 0 | Order Acknowledgment Requirement |
| `LABNR` | LABNR | — | CHAR | 20 | 0 | Order Acknowledgment Number |
| `KONNR` | KONNR | EKKO | CHAR | 10 | 0 | Number of Principal Purchase Agreement |
| `KTPNR` | KTPNR | EKPO | NUMC | 5 | 0 | Item Number of Principal Purchase Agreement |
| `ABDAT` | ABDAT | — | DATS | 8 | 0 | Reconciliation Date for Agreed Cumulative Quantity |
| `ABFTZ` | ABFTZ | — | QUAN | 13 | 3 | Agreed Cumulative Quantity |
| `ETFZ1` | ETFZ1 | — | DEC | 3 | 0 | Firm Zone (Go-Ahead for Production) |
| `ETFZ2` | ETFZ2 | — | DEC | 3 | 0 | Trade-Off Zone (Go-Ahead for Materials Procurement) |
| `KZSTU` | MRPRE | — | CHAR | 1 | 0 | Firm/Trade-Off Zones Binding with Regard to Mat. Planning |
| `NOTKZ` | NOTKZ | — | CHAR | 1 | 0 | Exclusion in Outline Agreement Item with Material Class |
| `LMEIN` | LAGME | T006 | UNIT | 3 | 0 | Base Unit of Measure |
| `EVERS` | EVERS | T027A | CHAR | 2 | 0 | Shipping Instructions |
| `ZWERT` | DZWERT | — | CURR | 13 | 2 | Target Value for Outline Agreement in Document Currency |
| `NAVNW` | NAVNW | — | CURR | 13 | 2 | Non-deductible input tax |
| `ABMNG` | NORAM | — | QUAN | 13 | 3 | Standard release order quantity |
| `PRDAT` | PREDT | — | DATS | 8 | 0 | Date of Price Determination |
| `BSTYP` | BSTYP | — | CHAR | 1 | 0 | Purchasing Document Category |
| `EFFWR` | EFFWR | — | CURR | 13 | 2 | Effective value of item |
| `XOBLR` | XOBLR | — | CHAR | 1 | 0 | Item affects commitments |
| `KUNNR` | EKUNNR | KNA1 | CHAR | 10 | 0 | Customer |
| `ADRNR` | ADRNR_MM | ADRC | CHAR | 10 | 0 | Manual address number in purchasing document item |
| `EKKOL` | EKKOG | — | CHAR | 4 | 0 | Condition Group with Vendor |
| `SKTOF` | ESKTOF | — | CHAR | 1 | 0 | Item Does Not Qualify for Cash Discount |
| `STAFO` | STAFO | — | CHAR | 6 | 0 | Update group for statistics update |
| `PLIFZ` | EPLIF | — | DEC | 3 | 0 | Planned Delivery Time in Days |
| `NTGEW` | ENTGE | — | QUAN | 13 | 3 | Net Weight |
| `GEWEI` | EGEWE | T006 | UNIT | 3 | 0 | Unit of Weight |
| `TXJCD` | TXJCD | TTXJ | CHAR | 15 | 0 | Tax Jurisdiction |
| `ETDRK` | ETDRK | — | CHAR | 1 | 0 | Indicator: Print-relevant schedule lines exist |
| `SOBKZ` | SOBKZ | T148 | CHAR | 1 | 0 | Special Stock Indicator |
| `ARSNR` | ARSNR | — | NUMC | 10 | 0 | Settlement reservation number |
| `ARSPS` | ARSPS | — | NUMC | 4 | 0 | Item number of the settlement reservation |
| `INSNC` | INSNC | — | CHAR | 1 | 0 | Quality inspection indicator cannot be changed |
| `SSQSS` | QSSPUR | TQ08 | CHAR | 8 | 0 | Control Key for Quality Management in Procurement |
| `ZGTYP` | QZGTYP | TQ05 | CHAR | 4 | 0 | Certificate Type |
| `EAN11` | EAN11 | — | CHAR | 18 | 0 | International Article Number (EAN/UPC) |
| `BSTAE` | BSTAE | T163L | CHAR | 4 | 0 | Confirmation Control Key |
| `REVLV` | REVLV | — | CHAR | 2 | 0 | Revision Level |
| `GEBER` | BP_GEBER | — | CHAR | 10 | 0 | Fund |
| `FISTL` | FISTL | — | CHAR | 16 | 0 | Funds Center |
| `FIPOS` | FIPOS | FMFPO | CHAR | 14 | 0 | Commitment Item |
| `KO_GSBER` | GSBER_GP | — | CHAR | 4 | 0 | Business area reported to the partner |
| `KO_PARGB` | PARGB_GP | — | CHAR | 4 | 0 | assumed business area of the business partner |
| `KO_PRCTR` | PRCTR | CEPC | CHAR | 10 | 0 | Profit Center |
| `KO_PPRCTR` | PPRCTR | CEPC | CHAR | 10 | 0 | Partner Profit Center |
| `MEPRF` | MEPRF | — | CHAR | 1 | 0 | Price Determination (Pricing) Date Control |
| `BRGEW` | BRGEW | — | QUAN | 13 | 3 | Gross Weight |
| `VOLUM` | VOLUM | — | QUAN | 13 | 3 | Volume |
| `VOLEH` | VOLEH | T006 | UNIT | 3 | 0 | Volume unit |
| `INCO1` | INCO1 | TINC | CHAR | 3 | 0 | Incoterms (Part 1) |
| `INCO2` | INCO2 | — | CHAR | 28 | 0 | Incoterms (Part 2) |
| `VORAB` | VORAB | — | CHAR | 1 | 0 | Advance procurement: project stock |
| `KOLIF` | KOLIF | LFA1 | CHAR | 10 | 0 | Prior Vendor |
| `LTSNR` | LTSNR | WYT1 | CHAR | 6 | 0 | Vendor Subrange |
| `PACKNO` | PACKNO | ESLH | NUMC | 10 | 0 | Package number |
| `FPLNR` | IPLNR | — | CHAR | 10 | 0 | Invoicing plan number |
| `GNETWR` | GNETWR | — | CURR | 13 | 2 | Currently not used |
| `STAPO` | STAPO | — | CHAR | 1 | 0 | Item is statistical |
| `UEBPO` | UEBPO | EKPO | NUMC | 5 | 0 | Higher-Level Item in Purchasing Documents |
| `LEWED` | LEWED | — | DATS | 8 | 0 | Latest Possible Goods Receipt |
| `EMLIF` | EMLIF | LFA1 | CHAR | 10 | 0 | Vendor to be supplied/who is to receive delivery |
| `LBLKZ` | LBLKZ | — | CHAR | 1 | 0 | Subcontracting vendor |
| `SATNR` | SATNR | MARA | CHAR | 18 | 0 | Cross-Plant Configurable Material |
| `ATTYP` | ATTYP | — | CHAR | 2 | 0 | Material Category |
| `VSART` | VERSART | — | CHAR | 2 | 0 | Shipping type |
| `HANDOVERLOC` | HANDOVER_LOC | — | CHAR | 10 | 0 | Location for a physical handover of goods |
| `KANBA` | KBNKZ | — | CHAR | 1 | 0 | Kanban Indicator |
| `ADRN2` | ADRN2 | ADRC | CHAR | 10 | 0 | Number of delivery address |
| `CUOBJ` | CUOBJ | — | NUMC | 18 | 0 | Configuration (internal object number) |
| `XERSY` | XERSY | — | CHAR | 1 | 0 | Evaluated Receipt Settlement (ERS) |
| `EILDT` | EILDT | — | DATS | 8 | 0 | Start Date for GR-Based Settlement |
| `DRDAT` | DRDAT | — | DATS | 8 | 0 | Last Transmission |
| `DRUHR` | DRUHR | — | TIMS | 6 | 0 | Time |
| `DRUNR` | DRUNR | — | NUMC | 4 | 0 | Sequential Number |
| `AKTNR` | WAKTION | WAKH | CHAR | 10 | 0 | Promotion |
| `ABELN` | ABELN | AUKO | CHAR | 10 | 0 | Allocation Table Number |
| `ABELP` | ABELP | — | NUMC | 5 | 0 | Item number of allocation table |
| `ANZPU` | ANZPU | — | QUAN | 13 | 3 | Number of Points |
| `PUNEI` | PUNEI | T006 | UNIT | 3 | 0 | Points unit |
| `SAISO` | SAISO | T6WSP | CHAR | 4 | 0 | Season Category |
| `SAISJ` | SAISJ | — | CHAR | 4 | 0 | Season Year |
| `EBON2` | EBON2 | — | CHAR | 2 | 0 | Settlement Group 2 (Rebate Settlement, Purchasing) |
| `EBON3` | EBON3 | — | CHAR | 2 | 0 | Settlement Group 3 (Rebate Settlement, Purchasing) |
| `EBONF` | EBONY | — | CHAR | 1 | 0 | Item Relevant to Subsequent (Period-End Rebate) Settlement |
| `MLMAA` | CK_ML_MAAC | — | CHAR | 1 | 0 | Material ledger activated at material level |
| `MHDRZ` | MHDRZ | — | DEC | 4 | 0 | Minimum Remaining Shelf Life |
| `ANFNR` | ANFNR | EKKO | CHAR | 10 | 0 | RFQ Number |
| `ANFPS` | ANFPS | EKPO | NUMC | 5 | 0 | Item Number of RFQ |
| `KZKFG` | KZCUH | — | CHAR | 1 | 0 | Origin of Configuration |
| `USEQU` | USEQU | TMQ2 | CHAR | 1 | 0 | Quota arrangement usage |
| `UMSOK` | UMSOK | — | CHAR | 1 | 0 | Special Stock Indicator for Physical Stock Transfer |
| `BANFN` | BANFN | — | CHAR | 10 | 0 | Purchase Requisition Number |
| `BNFPO` | BNFPO | EBAN | NUMC | 5 | 0 | Item Number of Purchase Requisition |
| `MTART` | MTART | T134 | CHAR | 4 | 0 | Material Type |
| `UPTYP` | UPTYP | TMSI1 | CHAR | 1 | 0 | Subitem Category, Purchasing Document |
| `UPVOR` | UPVOR | — | CHAR | 1 | 0 | Subitems Exist |
| `KZWI1` | KZWI1 | — | CURR | 13 | 2 | Subtotal 1 from pricing procedure for condition |
| `KZWI2` | KZWI2 | — | CURR | 13 | 2 | Subtotal 2 from pricing procedure for condition |
| `KZWI3` | KZWI3 | — | CURR | 13 | 2 | Subtotal 3 from pricing procedure for condition |
| `KZWI4` | KZWI4 | — | CURR | 13 | 2 | Subtotal 4 from pricing procedure for condition |
| `KZWI5` | KZWI5 | — | CURR | 13 | 2 | Subtotal 5 from pricing procedure for condition |
| `KZWI6` | KZWI6 | — | CURR | 13 | 2 | Subtotal 6 from pricing procedure for condition |
| `SIKGR` | SIKGR | TMSI2 | CHAR | 3 | 0 | Processing key for sub-items |
| `MFZHI` | MFZHI | — | QUAN | 15 | 3 | Maximum Cumulative Material Go-Ahead Quantity |
| `FFZHI` | FFZHI | — | QUAN | 15 | 3 | Maximum Cumulative Production Go-Ahead Quantity |
| `RETPO` | RETPO | — | CHAR | 1 | 0 | Returns Item |
| `AUREL` | AUREL | — | CHAR | 1 | 0 | Relevant to Allocation Table |
| `BSGRU` | BSGRU | TBSG | CHAR | 3 | 0 | Reason for Ordering |
| `LFRET` | LFRET | TVLK | CHAR | 4 | 0 | Delivery Type for Returns to Vendors |
| `MFRGR` | MFRGR | TMFG | CHAR | 8 | 0 | Material freight group |
| `NRFHG` | NRFHG | — | CHAR | 1 | 0 | Material qualifies for discount in kind |
| `J_1BNBM` | J_1BNBMCO1 | T604F | CHAR | 16 | 0 | Brazilian NCM Code |
| `J_1BMATUSE` | J_1BMATUSE | — | CHAR | 1 | 0 | Usage of the material |
| `J_1BMATORG` | J_1BMATORG | — | CHAR | 1 | 0 | Origin of the material |
| `J_1BOWNPRO` | J_1BOWNPRO | — | CHAR | 1 | 0 | Produced in-house |
| `J_1BINDUST` | J_1BINDUS3 | — | CHAR | 2 | 0 | Material CFOP category |
| `ABUEB` | ABUEB | T163P | CHAR | 4 | 0 | Release Creation Profile |
| `NLABD` | NLABD | — | DATS | 8 | 0 | Next Forecast Delivery Schedule Transmission |
| `NFABD` | NFABD | — | DATS | 8 | 0 | Next JIT Delivery Schedule Transmission |
| `KZBWS` | KZBWS | — | CHAR | 1 | 0 | Valuation of Special Stock |
| `BONBA` | BONBA | — | CURR | 13 | 2 | Rebate basis 1 |
| `FABKZ` | FABKZ | — | CHAR | 1 | 0 | Indicator: Item Relevant to JIT Delivery Schedules |
| `J_1AINDXP` | J_1AINDXP | J_1AINFT20 | CHAR | 5 | 0 | Inflation Index |
| `J_1AIDATEP` | J_1AIDATEP | — | DATS | 8 | 0 | Inflation Index Date |
| `MPROF` | MPROF | — | CHAR | 4 | 0 | Manufacturer Part Profile |
| `EGLKZ` | EGLKZ | — | CHAR | 1 | 0 | &quot;Outward Delivery Completed&quot; Indicator |
| `KZTLF` | KZTUL | — | CHAR | 1 | 0 | Partial Delivery at Item Level (Stock Transfer) |
| `KZFME` | KZWSO | — | CHAR | 1 | 0 | Units of measure usage |
| `RDPRF` | RDPRF | RDPR | CHAR | 4 | 0 | Rounding Profile |
| `TECHS` | TECHS | — | CHAR | 12 | 0 | Parameter Variant/Standard Variant |
| `CHG_SRV` | CHG_SRV | — | CHAR | 1 | 0 | Configuration changed |
| `CHG_FPLNR` | CHG_FPLNR | — | CHAR | 1 | 0 | No invoice for this item although not free of charge |
| `MFRPN` | MFRPN | — | CHAR | 40 | 0 | Manufacturer Part Number |
| `MFRNR` | MFRNR | LFA1 | CHAR | 10 | 0 | Number of a Manufacturer |
| `EMNFR` | EMNFR | — | CHAR | 10 | 0 | External manufacturer code name or number |
| `NOVET` | NOVET | — | CHAR | 1 | 0 | Item blocked for SD delivery |
| `AFNAM` | AFNAM | — | CHAR | 12 | 0 | Name of Requisitioner/Requester |
| `TZONRC` | TSEGZONREC | — | CHAR | 6 | 0 | Time zone of recipient location |
| `IPRKZ` | DATTP | — | CHAR | 1 | 0 | Period Indicator for Shelf Life Expiration Date |
| `LEBRE` | LEBRE | — | CHAR | 1 | 0 | Indicator for Service-Based Invoice Verification |
| `BERID` | BERID | MDLV | CHAR | 10 | 0 | MRP Area |
| `XCONDITIONS` | XCONDITIONS | — | CHAR | 1 | 0 | Conditions for item although no invoice |
| `APOMS` | APOMS | — | CHAR | 1 | 0 | APO as Planning System |
| `CCOMP` | MMPUR_CCOMP | — | CHAR | 1 | 0 | Posting Logic in the Case of Stock Transfers |
| `GRANT_NBR` | GM_GRANT_NBR | — | CHAR | 20 | 0 | Grant |
| `FKBER` | FKBER | — | CHAR | 16 | 0 | Functional Area |
| `STATUS` | EPSTATU | — | CHAR | 1 | 0 | Status of Purchasing Document Item |
| `RESLO` | RESLO | T001L | CHAR | 4 | 0 | Issuing Storage Location for Stock Transport Order |
| `KBLNR` | KBLNR | — | CHAR | 10 | 0 | Document Number for Earmarked Funds |
| `KBLPOS` | KBLPOS | — | NUMC | 3 | 0 | Earmarked Funds: Document Item |
| `WEORA` | WEORA | — | CHAR | 1 | 0 | Acceptance At Origin |
| `SRV_BAS_COM` | SRV_BAS_COM | — | CHAR | 1 | 0 | Service-Based Commitment |
| `PRIO_URG` | PRIO_URG | PURG | NUMC | 2 | 0 | Requirement Urgency |
| `PRIO_REQ` | PRIO_REQ | PREQ | NUMC | 3 | 0 | Requirement Priority |
| `EMPST` | EMPST | — | CHAR | 25 | 0 | Receiving point |
| `DIFF_INVOICE` | DIFF_INVOICE | — | CHAR | 2 | 0 | Differential Invoicing |
| `TRMRISK_RELEVANT` | PUR_TRM_RISK_RELEVANCY | — | CHAR | 2 | 0 | Risk Relevancy in Purchasing |
| `SPE_ABGRU` | ABGRU | — | CHAR | 2 | 0 | Reason for rejection of quotations and sales orders |
| `SPE_CRM_SO` | /SPE/VBELN_CRM | — | CHAR | 10 | 0 | CRM Sales Order Number for TPOP Process |
| `SPE_CRM_SO_ITEM` | /SPE/POSNR_CRM | — | NUMC | 6 | 0 | CRM Sales Order Item Number in TPOP Process |
| `SPE_CRM_REF_SO` | /SPE/REF_VBELN_CRM | — | CHAR | 35 | 0 | CRM Reference Order Number for TPOP Process |
| `SPE_CRM_REF_ITEM` | /SPE/REF_POSNR_CRM | — | CHAR | 6 | 0 | CRM Reference Sales Order Item Number in TPOP Process |
| `SPE_CRM_FKREL` | /SPE/FKREL_CRM | — | CHAR | 1 | 0 | Billing Relevance CRM |
| `SPE_CHNG_SYS` | /SPE/INB_CHNG_SYS | — | CHAR | 1 | 0 | Last Changer&#039;s System Type |
| `SPE_INSMK_SRC` | /SPE/INSMK_SRC | — | CHAR | 1 | 0 | Stock Type of Source Storage Location in STO |
| `SPE_CQ_CTRLTYPE` | /SPE/CQ_CONTROL_TYPE | — | CHAR | 1 | 0 | CQ Control Type |
| `SPE_CQ_NOCQ` | /SPE/CQ_NOCQ | — | CHAR | 1 | 0 | No Transmission of Cumulative Quantities in SA Release |
| `REASON_CODE` | /SAPPSPRO/_GR_REASON_CODE | — | CHAR | 4 | 0 | Goods Receipt Reason Code |
| `CQU_SAR` | CQU_SAR | — | QUAN | 15 | 3 | Cumulative Goods Receipts from Redirected Purchase Orders |
| `ANZSN` | ANZSN | — | INT4 | 10 | 0 | Number of serial numbers |
| `SPE_EWM_DTC` | /SPE/EWM_DTC | — | CHAR | 1 | 0 | EWM Delivery Based Tolerance Check |
| `EXLIN` | EXLIN | — | CHAR | 40 | 0 | Item Number Length |
| `EXSNR` | EXSNR | — | NUMC | 5 | 0 | External Sorting |
| `EHTYP` | EHTYP | TMSRM_EHTYP | CHAR | 4 | 0 | External Hierarchy Category |
| `RETPC` | RETPZ | — | DEC | 5 | 2 | Retention in Percent |
| `DPTYP` | ME_DPTYP | — | CHAR | 4 | 0 | Down Payment Indicator |
| `DPPCT` | ME_DPPCNT | — | DEC | 5 | 2 | Down Payment Percentage |
| `DPAMT` | ME_DPAMNT | — | CURR | 11 | 2 | Down Payment Amount in Document Currency |
| `DPDAT` | ME_DPDDAT | — | DATS | 8 | 0 | Due Date for Down Payment |
| `FLS_RSTO` | FLS_RSTO | — | CHAR | 1 | 0 | Store Return with Inbound and Outbound Delivery |
| `EXT_RFX_NUMBER` | ME_PUR_EXT_DOC_ID | — | CHAR | 35 | 0 | Document Number of External Document |
| `EXT_RFX_ITEM` | ME_PUR_EXT_DOC_ITEM_ID | — | CHAR | 10 | 0 | Item Number of External Document |
| `EXT_RFX_SYSTEM` | LOGSYSTEM | — | CHAR | 10 | 0 | Logical System |
| `SRM_CONTRACT_ID` | SRM_CONTRACT_ID | — | CHAR | 10 | 0 | Central Contract |
| `SRM_CONTRACT_ITM` | SRM_CONTRACT_ITEM | — | NUMC | 10 | 0 | Central Contract Item Number |
| `BLK_REASON_ID` | BLK_REASON_ID | — | CHAR | 4 | 0 | Blocking Reason - ID |
| `BLK_REASON_TXT` | BLK_REASON_TXT | — | CHAR | 40 | 0 | Blocking Reason - Text |
| `ITCONS` | ME_IR_CO_ORDER | — | CHAR | 1 | 0 | Real-Time Consumption Posting of Subcontracting Components |
| `FIXMG` | ME_FIXMG | — | CHAR | 1 | 0 | Delivery Date and Quantity Fixed |
| `WABWE` | WABWE | — | CHAR | 1 | 0 | Indicator for GI-based goods receipt |
| `TC_AUT_DET` | J_1BTC_AUT_DET | — | CHAR | 2 | 0 | Tax Code Automatically Determined |
| `MANUAL_TC_REASON` | J_1BMANUAL_TC_REASON | — | CHAR | 2 | 0 | Manual Tax Code Reason |
| `FISCAL_INCENTIVE` | J_1BFISCAL_INCENTIVE_CODE | — | CHAR | 4 | 0 | Tax Incentive Type |
| `TAX_SUBJECT_ST` | J_1BTC_TAX_SUBJECT_ST | — | CHAR | 1 | 0 | TAX_SUBJECT_ST |
| `FISCAL_INCENTIVE_ID` | J_1BFISCAL_INCENTIVE_ID | — | CHAR | 4 | 0 | Incentive ID |
| `/BEV1/NEGEN_ITEM` | /BEV1/NEGEN_ITEM_FLAG | — | CHAR | 1 | 0 | Indicator: Item Is Generated |
| `/BEV1/NEDEPFREE` | /BEV1/NEDEPFREE | — | CHAR | 1 | 0 | Indicator: Dependent Items Are Free of Charge |
| `/BEV1/NESTRUCCAT` | /BEV1/NESTRUC_CAT | — | CHAR | 1 | 0 | Structure Category for Material Relationship |
| `/CWM/WABWE` | WABWE | — | CHAR | 1 | 0 | Indicator for GI-based goods receipt |
| `ADVCODE` | /ISDFPS/ADVCODE | — | CHAR | 2 | 0 | Advice Code |
| `BUDGET_PD` | FM_BUDGET_PERIOD | — | CHAR | 10 | 0 | FM: Budget Period |
| `EXCPE` | EXCPE | — | NUMC | 2 | 0 | Acceptance Period |
| `IUID_RELEVANT` | IUID_RELEVANT | — | CHAR | 1 | 0 | IUID-Relevant |
| `MRPIND` | J_1IRMRPIND | — | CHAR | 1 | 0 | Max. Retail Price Relevant |
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
| `OITAXFROM` | OIH_TAXFRO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;from&#039; location |
| `OIHANTYP` | OIH_HANTYP | OIH5 | CHAR | 2 | 0 | Excise Duty Handling Type |
| `OIPRICIE` | OIH_PRICIE | — | CHAR | 1 | 0 | ED pricing: external (indicator) |
| `OITAXTO` | OIH_TAXTO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;to&#039; location |
| `OITAXCON` | OIH_TAXCON | — | CURR | 13 | 2 | Excise duty tax from pricing conditions |
| `OITAXGRP` | OIH_TAXGRP | OIH2 | CHAR | 2 | 0 | Excise Duty Group |
| `OIOILCON` | OIH_OILCON | — | DEC | 5 | 2 | Oil content in a material as a percentage |
| `OIINEX` | OIH_INEX | OIH16 | CHAR | 2 | 0 | Code for internal or external excise duty rate determination |
| `OIEXGNUM` | OIA_EXGNUM | — | CHAR | 10 | 0 | Exchange agreement number |
| `OIEXGTYP` | OIA_EXGTYP | TOIA2 | CHAR | 4 | 0 | Exchange type |
| `OIFEETOT` | OIA_FEETOT | — | CURR | 13 | 2 | Fee total |
| `OIFEEDT` | OIA_FEEDT | — | DATS | 8 | 0 | Fee pricing condition date |
| `OINETCYC` | OIA_NETCYC | T008 | CHAR | 1 | 0 | Netting cycle (FI blocking indicator) |
| `OIFERP` | OIA_FERP | — | CHAR | 1 | 0 | Fee repricing indicator |
| `OIFEECH` | OIA_FEECH | — | CHAR | 1 | 0 | Fee edit control |
| `OIA_IPMVAT` | OIA_IPMVAT | — | CHAR | 1 | 0 | VAT on internally-posted material |
| `OIA_SPLTIV` | OIA_SPLTIV | — | CHAR | 1 | 0 | Indicator for split invoice verification |
| `OIVATH` | DMBTR | — | CURR | 13 | 2 | Amount in Local Currency |
| `OIVATF` | WRBTR | — | CURR | 13 | 2 | Amount in document currency |
| `OISBREL` | OIA_SBREL | — | NUMC | 3 | 0 | Sub product/ base product relevence indicator |
| `OIBASPROD` | OIA_SBMAT | — | CHAR | 18 | 0 | Base product number |
| `OITRKNR` | OIH_TRKNR | — | CHAR | 10 | 0 | Tracking number |
| `OITRKJR` | OIH_TRKJR | — | NUMC | 4 | 0 | Tracking number year |
| `OIEXTNR` | OIH_EXTNR | — | CHAR | 18 | 0 | External tracking number |
| `OIITMNR` | OIH_ITMNR | — | NUMC | 5 | 0 | Tracking number item line |
| `OIFTIND` | OIH_FTIND | — | CHAR | 1 | 0 | Final transfer indicator |
| `OIPRIOP` | OIH_PRIOP | — | CHAR | 1 | 0 | Price options for gain calculation |
| `OITRIND` | OIH_TRIND | — | CHAR | 1 | 0 | Transfer sign for plant-to-plant transfers |
| `OIGHNDL` | OIH_GHNDL | — | CHAR | 1 | 0 | Gain handling |
| `OIUMBAR` | OIH_UMBAR | T149D | CHAR | 10 | 0 | Valuation type of issuing location for two-step transfer |
| `OITXCON1` | OIH_TXCON1 | — | CURR | 13 | 2 | Excise duty tax from pricing conditions: rate 1 |
| `OITXCON2` | OIH_TXCON2 | — | CURR | 13 | 2 | Excise duty tax from pricing conditions: rate 2 |
| `OITXCON3` | OIH_TXCON3 | — | CURR | 13 | 2 | Excise duty tax from pricing conditions: rate 3 |
| `OITXCON4` | OIH_TXCON4 | — | CURR | 13 | 2 | Excise duty tax from pricing conditions: rate 4 |
| `OITXCON5` | OIH_TXCON5 | — | CURR | 13 | 2 | Excise duty tax from pricing conditions: rate 5 |
| `OITXCON6` | OIH_TXCON6 | — | CURR | 13 | 2 | Excise duty tax from pricing conditions: rate 6 |
| `OID_EXTBOL` | OID_EXTBOL | — | CHAR | 16 | 0 | External bill of lading |
| `OID_MISCDL` | OID_MISCDL | — | CHAR | 16 | 0 | Miscellaneous delivery number |
| `OIMATCYC` | OIA_MATCYC | — | NUMC | 1 | 0 | Invoicing cycle for purchase material costs |
| `OIEDOK` | OIH_EDOK | — | CHAR | 1 | 0 | Excise duty validation indicator |
| `OIEDBAL` | OIH_EDBAL | — | CHAR | 1 | 0 | Excise duty balancing is required (indicator) |
| `OIEDBALM` | OIH_EDBALM | — | CHAR | 1 | 0 | Excise duty balancing method indicator |
| `OICERTF1` | OIH_CERTF1 | — | CHAR | 15 | 0 | Excise tax external license number |
| `OIDATFM1` | OIH_DATFM1 | — | DATS | 8 | 0 | Excise Duty License Valid from Date |
| `OIDATTO1` | OIH_DATTO1 | — | DATS | 8 | 0 | Valid to date for excise duty tax certificate |
| `OIH_LICTP` | OIH_LICTP | OIH20 | CHAR | 4 | 0 | License type |
| `OIH_LICIN` | OIH_LICIN | OIHL | CHAR | 10 | 0 | Excise tax internal license number |
| `OIH_LCFOL` | OIH_LCFOL | OIHL | CHAR | 10 | 0 | Follow-on license for quantity license |
| `OIH_FOLQTY` | OIH_FOLQTY | — | QUAN | 13 | 3 | Excise Tax Follow-On License Quantity |
| `OIEDOK_GI` | OIH_EDOK_GI | — | CHAR | 1 | 0 | Excise Duty Validation Indicator for Material (STO) |
| `OIEDBAL_GI` | OIH_EDBAL_GI | — | CHAR | 1 | 0 | Excise Duty Balancing is Required for Mat. (STO) |
| `OIEDBALM_GI` | OIH_EDBALM_GI | — | CHAR | 1 | 0 | Excise Duty Balancing Method Indicator for Mat.  (STO) |
| `OIHANTYP_GI` | OIH_HANTYP_GI | — | CHAR | 2 | 0 | Excise Duty Handling Type - Denotes Use of Material |
| `OIINEX_GI` | OIH_INEX_GI | — | CHAR | 2 | 0 | Code for Internal or External Excise Duty Rate Determination |
| `OITAXGRP_GI` | OIH_TAXGRP | — | CHAR | 2 | 0 | Excise Duty Group |
| `OICERTF1_GI` | OIH_CERTF1_GI | — | CHAR | 15 | 0 | Excise Tax External License Number Used During GI (STO) |
| `OIDATFM1_GI` | OIH_DATFM1_GI | — | DATS | 8 | 0 | Excise Duty License Valid from Date for Mat. (STO) |
| `OIDATTO1_GI` | OIH_DATTO1_GI | — | DATS | 8 | 0 | Valid To Date for Excise Duty Tax Certificate for Mat. (STO) |
| `OIH_LICTP_GI` | OIH_LICTP_GI | OIH20 | CHAR | 4 | 0 | License Type to Material (STO) |
| `OIH_LICIN_GI` | OIH_LICIN_GI | OIHL | CHAR | 10 | 0 | Excise Tax Internal License Number to Mat. (STO) |
| `OIH_LCFOL_GI` | OIH_LCFOL_GI | OIHL | CHAR | 10 | 0 | Follow-On License for Quantity License to Mat. (STO) |
| `OIH_FOLQTY_GI` | OIH_FOLQTY_GI | — | QUAN | 13 | 3 | Excise Tax Follow-On License Quantity to Mat. (STO) |
| `OIO_RFBLN` | OIO_RN_RFBLN | — | CHAR | 10 | 0 | Reference document for mobilization |
| `OIO_RFBLP` | OIO_RN_RFBLP | — | NUMC | 5 | 0 | Reference document item for mobilization |
| `REFSITE` | WREFSITE | — | CHAR | 4 | 0 | Reference Site For Purchasing |
| `SERRU` | SERRU | — | CHAR | 1 | 0 | Type of subcontracting |
| `SERNP` | SERAIL | — | CHAR | 4 | 0 | Serial Number Profile |
| `DISUB_SOBKZ` | DISUB_SOBKZ_LB | — | CHAR | 1 | 0 | Special stock indicator Subcontracting |
| `DISUB_PSPNR` | PS_PSP_PNR | — | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `DISUB_KUNNR` | KUNNR | — | CHAR | 10 | 0 | Customer Number |
| `DISUB_VBELN` | VBELN | — | CHAR | 10 | 0 | Sales and Distribution Document Number |
| `DISUB_POSNR` | POSNR | — | NUMC | 6 | 0 | Item number of the SD document |
| `DISUB_OWNER` | OWNER_D | — | CHAR | 10 | 0 | Owner of stock |
| `REF_ITEM` | WRF_PSCD_REF_ITEM | — | NUMC | 5 | 0 | Reference Item for Remaining Qty Cancellation |
| `SOURCE_ID` | WRF_POHF_SOURCE_ID | WRFT_POHF_SOURCE | CHAR | 3 | 0 | Origin Profile |
| `SOURCE_KEY` | WRF_POHF_SOURCE_KEY | — | CHAR | 32 | 0 | Key in Source System |
| `PUT_BACK` | WRF_POHF_PUT_BACK_POG | — | CHAR | 1 | 0 | Indicator for Putting Back from Grouped PO Document |
| `POL_ID` | WRF_POHF_POL_ID | — | CHAR | 10 | 0 | Order List Item Number |
| `CONS_ORDER` | WRF_CONS_ORDER | — | CHAR | 1 | 0 | Purchase Order for Consignment |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABELN` | EKPO | MANDT | AUKO |  | |
| `ABELN` | EKPO | ABELN | AUKO |  | |
| `ABUEB` | EKPO | MANDT | T163P |  | |
| `ABUEB` | EKPO | WERKS | T163P |  | |
| `ABUEB` | EKPO | ABUEB | T163P |  | |
| `ADRN2` | EKPO | MANDT | ADRC |  | |
| `ADRN2` | EKPO | ADRN2 | ADRC |  | |
| `ADRN2` | * |  | ADRC |  | |
| `ADRN2` | * |  | ADRC |  | |
| `ADRNR` | EKPO | AEDAT | ADRC |  | |
| `ADRNR` | * |  | ADRC |  | |
| `ADRNR` | EKPO | MANDT | ADRC |  | |
| `ADRNR` | EKPO | ADRNR | ADRC |  | |
| `AGMEM` | EKPO | MANDT | TMAM |  | |
| `AGMEM` | EKPO | AGMEM | TMAM |  | |
| `AKTNR` | EKPO | MANDT | WAKH |  | |
| `AKTNR` | EKPO | AKTNR | WAKH |  | |
| `ANFNR` | EKPO | MANDT | EKKO |  | |
| `ANFNR` | EKPO | ANFNR | EKKO |  | |
| `ANFPS` | EKPO | MANDT | EKPO |  | |
| `ANFPS` | EKPO | ANFNR | EKPO |  | |
| `ANFPS` | EKPO | ANFPS | EKPO |  | |
| `BERID` | SYST | MANDT | MDLV |  | |
| `BERID` | EKPO | BERID | MDLV |  | |
| `BNFPO` | EKPO | MANDT | EBAN |  | |
| `BNFPO` | EKPO | BANFN | EBAN |  | |
| `BNFPO` | EKPO | BNFPO | EBAN |  | |
| `BPRME` | EKPO | MANDT | T006 |  | |
| `BPRME` | EKPO | BPRME | T006 |  | |
| `BSGRU` | EKPO | MANDT | TBSG |  | |
| `BSGRU` | EKPO | BSGRU | TBSG |  | |
| `BSTAE` | EKPO | BSTAE | T163L |  | |
| `BSTAE` | EKPO | MANDT | T163L |  | |
| `BUKRS` | EKPO | MANDT | T001 |  | |
| `BUKRS` | EKPO | BUKRS | T001 |  | |
| `BWTAR` | EKPO | MANDT | T149D |  | |
| `BWTAR` | EKPO | BWTAR | T149D |  | |
| `BWTTY` | EKPO | MANDT | T149C |  | |
| `BWTTY` | EKPO | BWTTY | T149C |  | |
| `EBELN` | EKPO | MANDT | EKKO |  | |
| `EBELN` | EKPO | EBELN | EKKO |  | |
| `EHTYP` | SYST | MANDT | TMSRM_EHTYP |  | |
| `EHTYP` | EKPO | EHTYP | TMSRM_EHTYP |  | |
| `EMATN` | EKPO | MANDT | MARA |  | |
| `EMATN` | EKPO | EMATN | MARA |  | |
| `EMLIF` | EKPO | MANDT | LFA1 |  | |
| `EMLIF` | EKPO | EMLIF | LFA1 |  | |
| `EVERS` | EKPO | EVERS | T027A |  | |
| `EVERS` | EKPO | MANDT | T027A |  | |
| `FIPOS` | EKPO | PRDAT | FMFPO |  | |
| `FIPOS` | EKPO | MANDT | FMFPO |  | |
| `FIPOS` | T001 | FIKRS | FMFPO |  | |
| `FIPOS` | EKPO | FIPOS | FMFPO |  | |
| `GEWEI` | EKPO | MANDT | T006 |  | |
| `GEWEI` | EKPO | GEWEI | T006 |  | |
| `INCO1` | EKPO | MANDT | TINC |  | |
| `INCO1` | EKPO | INCO1 | TINC |  | |
| `INFNR` | EKPO | INFNR | EINA |  | |
| `INFNR` | EKPO | MANDT | EINA |  | |
| `J_1AINDXP` | EKPO | MANDT | J_1AINFT20 |  | |
| `J_1AINDXP` | EKPO | J_1AINDXP | J_1AINFT20 |  | |
| `J_1BNBM` | T005 | LAND1 | T604F |  | |
| `J_1BNBM` | EKPO | J_1BNBM | T604F |  | |
| `J_1BNBM` | EKPO | MANDT | T604F |  | |
| `KNTTP` | EKPO | MANDT | T163K |  | |
| `KNTTP` | EKPO | KNTTP | T163K |  | |
| `KOLIF` | EKPO | MANDT | LFA1 |  | |
| `KOLIF` | EKPO | KOLIF | LFA1 |  | |
| `KONNR` | EKPO | MANDT | EKKO |  | |
| `KONNR` | EKPO | KONNR | EKKO |  | |
| `KO_PPRCTR` | EKPO | KO_PPRCTR | CEPC |  | |
| `KO_PPRCTR` | EKKO | BEDAT | CEPC |  | |
| `KO_PPRCTR` | * |  | CEPC |  | |
| `KO_PPRCTR` | EKPO | MANDT | CEPC |  | |
| `KO_PRCTR` | EKKO | BEDAT | CEPC |  | |
| `KO_PRCTR` | * |  | CEPC |  | |
| `KO_PRCTR` | EKPO | MANDT | CEPC |  | |
| `KO_PRCTR` | EKPO | KO_PRCTR | CEPC |  | |
| `KTPNR` | EKPO | MANDT | EKPO |  | |
| `KTPNR` | EKPO | KONNR | EKPO |  | |
| `KTPNR` | EKPO | KTPNR | EKPO |  | |
| `KUNNR` | EKPO | MANDT | KNA1 |  | |
| `KUNNR` | EKPO | KUNNR | KNA1 |  | |
| `LFRET` | EKPO | MANDT | TVLK |  | |
| `LFRET` | EKPO | LFRET | TVLK |  | |
| `LGORT` | EKPO | WERKS | T001L |  | |
| `LGORT` | EKPO | LGORT | T001L |  | |
| `LGORT` | EKPO | MANDT | T001L |  | |
| `LMEIN` | EKPO | MANDT | T006 |  | |
| `LMEIN` | EKPO | LMEIN | T006 |  | |
| `LTSNR` | EKPO | KOLIF | WYT1 |  | |
| `LTSNR` | EKPO | LTSNR | WYT1 |  | |
| `LTSNR` | EKPO | MANDT | WYT1 |  | |
| `MANDT` | EKPO | MANDT | T000 |  | |
| `MATKL` | EKPO | MANDT | T023 |  | |
| `MATKL` | EKPO | MATKL | T023 |  | |
| `MATNR` | EKPO | MATNR | MARA |  | |
| `MATNR` | EKPO | MANDT | MARA |  | |
| `MEINS` | EKPO | MANDT | T006 |  | |
| `MEINS` | EKPO | MEINS | T006 |  | |
| `MFRGR` | EKPO | MFRGR | TMFG |  | |
| `MFRGR` | EKPO | MANDT | TMFG |  | |
| `MFRNR` | EKPO | MANDT | LFA1 |  | |
| `MFRNR` | EKPO | MFRNR | LFA1 |  | |
| `MTART` | EKPO | MANDT | T134 |  | |
| `MTART` | EKPO | MTART | T134 |  | |
| `MWSKZ` | EKPO | MANDT | T007A |  | |
| `MWSKZ` | T005 | KALSM | T007A |  | |
| `MWSKZ` | EKPO | MWSKZ | T007A |  | |
| `OIC_DCITYC` | EKPO | OIC_DREGIO | T005G |  | |
| `OIC_DCITYC` | EKPO | OIC_DCITYC | T005G |  | |
| `OIC_DCITYC` | SYST | MANDT | T005G |  | |
| `OIC_DCITYC` | EKPO | OIC_DLAND1 | T005G |  | |
| `OIC_DCOUNC` | SYST | MANDT | T005E |  | |
| `OIC_DCOUNC` | EKPO | OIC_DLAND1 | T005E |  | |
| `OIC_DCOUNC` | EKPO | OIC_DREGIO | T005E |  | |
| `OIC_DCOUNC` | EKPO | OIC_DCOUNC | T005E |  | |
| `OIC_DLAND1` | SYST | MANDT | T005 |  | |
| `OIC_DLAND1` | EKPO | OIC_DLAND1 | T005 |  | |
| `OIC_DREGIO` | SYST | MANDT | T005S |  | |
| `OIC_DREGIO` | EKPO | OIC_DLAND1 | T005S |  | |
| `OIC_DREGIO` | EKPO | OIC_DREGIO | T005S |  | |
| `OIC_LIFNR` | SYST | MANDT | LFA1 |  | |
| `OIC_LIFNR` | EKPO | OIC_LIFNR | LFA1 |  | |
| `OIC_MOT` | EKPO | OIC_MOT | TVTR |  | |
| `OIC_MOT` | SYST | MANDT | TVTR |  | |
| `OIC_OCITYC` | EKPO | OIC_OCITYC | T005G |  | |
| `OIC_OCITYC` | SYST | MANDT | T005G |  | |
| `OIC_OCITYC` | EKPO | OIC_OLAND1 | T005G |  | |
| `OIC_OCITYC` | EKPO | OIC_OREGIO | T005G |  | |
| `OIC_OCOUNC` | EKPO | OIC_OLAND1 | T005E |  | |
| `OIC_OCOUNC` | EKPO | OIC_OREGIO | T005E |  | |
| `OIC_OCOUNC` | EKPO | OIC_OCOUNC | T005E |  | |
| `OIC_OCOUNC` | SYST | MANDT | T005E |  | |
| `OIC_OLAND1` | EKPO | OIC_OLAND1 | T005 |  | |
| `OIC_OLAND1` | SYST | MANDT | T005 |  | |
| `OIC_OREGIO` | EKPO | OIC_OREGIO | T005S |  | |
| `OIC_OREGIO` | SYST | MANDT | T005S |  | |
| `OIC_OREGIO` | EKPO | OIC_OLAND1 | T005S |  | |
| `OIEXGTYP` | SYST | MANDT | TOIA2 |  | |
| `OIEXGTYP` | EKPO | OIEXGTYP | TOIA2 |  | |
| `OIHANTYP` | SYST | MANDT | OIH5 |  | |
| `OIHANTYP` | EKPO | OIHANTYP | OIH5 |  | |
| `OIH_LCFOL` | EKPO | OIH_LICTP | OIHL |  | |
| `OIH_LCFOL` | MSEG | MANDT | OIHL |  | |
| `OIH_LCFOL` | EKPO | OIH_LCFOL | OIHL |  | |
| `OIH_LCFOL_GI` | SYST | MANDT | OIHL |  | |
| `OIH_LCFOL_GI` | EKPO | OIH_LCFOL_GI | OIHL |  | |
| `OIH_LCFOL_GI` | EKPO | OIH_LICTP_GI | OIHL |  | |
| `OIH_LICIN` | * |  | OIHL |  | |
| `OIH_LICIN` | MSEG | MANDT | OIHL |  | |
| `OIH_LICIN` | EKPO | OIH_LICIN | OIHL |  | |
| `OIH_LICIN_GI` | SYST | MANDT | OIHL |  | |
| `OIH_LICIN_GI` | EKPO | OIH_LICIN_GI | OIHL |  | |
| `OIH_LICIN_GI` | * |  | OIHL |  | |
| `OIH_LICTP` | MSEG | MANDT | OIH20 |  | |
| `OIH_LICTP` | EKPO | OIH_LICTP | OIH20 |  | |
| `OIH_LICTP_GI` | SYST | MANDT | OIH20 |  | |
| `OIH_LICTP_GI` | EKPO | OIH_LICTP_GI | OIH20 |  | |
| `OIINEX` | SYST | MANDT | OIH16 |  | |
| `OIINEX` | EKPO | OIINEX | OIH16 |  | |
| `OINETCYC` | SYST | MANDT | T008 |  | |
| `OINETCYC` | EKPO | OINETCYC | T008 |  | |
| `OITAXFROM` | SYST | MANDT | OIH4 |  | |
| `OITAXFROM` | EKPO | OITAXFROM | OIH4 |  | |
| `OITAXGRP` | SYST | MANDT | OIH2 |  | |
| `OITAXGRP` | EKPO | OITAXGRP | OIH2 |  | |
| `OITAXTO` | EKPO | OITAXTO | OIH4 |  | |
| `OITAXTO` | SYST | MANDT | OIH4 |  | |
| `OIUMBAR` | SY | MANDT | T149D |  | |
| `OIUMBAR` | EKPO | OIUMBAR | T149D |  | |
| `PACKNO` | EKPO | MANDT | ESLH |  | |
| `PACKNO` | EKPO | PACKNO | ESLH |  | |
| `PRIO_REQ` | EKPO | PRIO_REQ | PREQ |  | |
| `PRIO_REQ` | SYST | MANDT | PREQ |  | |
| `PRIO_URG` | SYST | MANDT | PURG |  | |
| `PRIO_URG` | EKPO | PRIO_URG | PURG |  | |
| `PSTYP` | EKPO | MANDT | T163 |  | |
| `PSTYP` | EKPO | PSTYP | T163 |  | |
| `PUNEI` | EKPO | PUNEI | T006 |  | |
| `PUNEI` | EKPO | MANDT | T006 |  | |
| `RDPRF` | EKPO | RDPRF | RDPR |  | |
| `RDPRF` | * |  | RDPR |  | |
| `RDPRF` | SYST | MANDT | RDPR |  | |
| `RDPRF` | EKPO | WERKS | RDPR |  | |
| `RESLO` | SYST | MANDT | T001L |  | |
| `RESLO` | EKKO | RESWK | T001L |  | |
| `RESLO` | EKPO | RESLO | T001L |  | |
| `SAISO` | EKPO | MANDT | T6WSP |  | |
| `SAISO` | EKPO | SAISO | T6WSP |  | |
| `SATNR` | EKPO | MANDT | MARA |  | |
| `SATNR` | EKPO | SATNR | MARA |  | |
| `SIKGR` | EKPO | MANDT | TMSI2 |  | |
| `SIKGR` | EKPO | SIKGR | TMSI2 |  | |
| `SOBKZ` | EKPO | MANDT | T148 |  | |
| `SOBKZ` | EKPO | SOBKZ | T148 |  | |
| `SOURCE_ID` | SYST | MANDT | WRFT_POHF_SOURCE |  | |
| `SOURCE_ID` | EKPO | SOURCE_ID | WRFT_POHF_SOURCE |  | |
| `SSQSS` | EKPO | MANDT | TQ08 |  | |
| `SSQSS` | EKPO | SSQSS | TQ08 |  | |
| `TXJCD` | T005 | KALSM | TTXJ |  | |
| `TXJCD` | EKPO | TXJCD | TTXJ |  | |
| `TXJCD` | EKPO | MANDT | TTXJ |  | |
| `UEBPO` | EKPO | MANDT | EKPO |  | |
| `UEBPO` | EKPO | KONNR | EKPO |  | |
| `UEBPO` | EKPO | UEBPO | EKPO |  | |
| `UPTYP` | EKPO | MANDT | TMSI1 |  | |
| `UPTYP` | EKPO | UPTYP | TMSI1 |  | |
| `USEQU` | EKPO | MANDT | TMQ2 |  | |
| `USEQU` | EKPO | USEQU | TMQ2 |  | |
| `VOLEH` | EKPO | MANDT | T006 |  | |
| `VOLEH` | EKPO | VOLEH | T006 |  | |
| `WERKS` | EKPO | MANDT | T001W |  | |
| `WERKS` | EKPO | WERKS | T001W |  | |
| `ZGTYP` | EKPO | MANDT | TQ05 |  | |
| `ZGTYP` | EKPO | ZGTYP | TQ05 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AEDAT`, `ANFNR`, `ANFPS`, `BANFN`, `BNFPO`, `BPRME`, `BRTWR`, `EBELN`, `EBELP`, `KNTTP`, `KONNR`, `KTPNR`, `LGORT`, `LMEIN`, `LOEKZ`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `EBELN`, `LOEKZ`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_create_ekrs.txt`
- `zdemo.txt`
- `ziscs0120.txt`
- `zissd00031.txt`
- `zissd00041.txt`
- `zissd00079.txt`
- `zissd00081.txt`
- `zissd00086.txt`
- `zissd00096.txt`
- `zissd00097.txt`
- `zissd00098.txt`
- `zissd00099.txt`
- `zissd00103.txt`
- `zissd00108.txt`
- `zissd00111.txt`
- `zmmpri000.txt`
- `zmmpri001.txt`
- `zmmprsi01.txt`
- `zsdsodl02.txt`
- `zsdsodl06.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_