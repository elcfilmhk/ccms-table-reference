# `BSEG`

**Description:** Accounting Document Line — FI line item
**Category:** Standard SAP Table
**References:** 19 SELECT statements across 12 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/bseg/) — validated 2026-05-30, schema v1.0
**Schema fields:** 366 fields | **Data types:** ACCP(1), CHAR(205), CUKY(2), CURR(83), DATS(18), DEC(12), INT4(1), NUMC(34), QUAN(6), UNIT(4)

## Key Fields
`AUFNR` | `VBELN` | `PERNR` | `KUNNR` | `LIFNR` | `MATNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BUZID` | BUZID | — | CHAR | 1 | 0 | Identification of the Line Item |
| `AUGDT` | AUGDT | — | DATS | 8 | 0 | Clearing Date |
| `AUGCP` | AUGCP | — | DATS | 8 | 0 | Clearing Entry Date |
| `AUGBL` | AUGBL | — | CHAR | 10 | 0 | Document Number of the Clearing Document |
| `BSCHL` | BSCHL | TBSL | CHAR | 2 | 0 | Posting Key |
| `KOART` | KOART | — | CHAR | 1 | 0 | Account Type |
| `UMSKZ` | UMSKZ | T074U | CHAR | 1 | 0 | Special G/L Indicator |
| `UMSKS` | UMSKS | — | CHAR | 1 | 0 | Special G/L Transaction Type |
| `ZUMSK` | DZUMSK | T074U | CHAR | 1 | 0 | Target Special G/L Indicator |
| `SHKZG` | SHKZG | — | CHAR | 1 | 0 | Debit/Credit Indicator |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `PARGB` | PARGB | TGSB | CHAR | 4 | 0 | Trading partner&#039;s business area |
| `MWSKZ` | MWSKZ | T007A | CHAR | 2 | 0 | Tax on sales/purchases code |
| `QSSKZ` | QSSKZ | T059Q | CHAR | 2 | 0 | Withholding Tax Code |
| `DMBTR` | DMBTR | — | CURR | 13 | 2 | Amount in Local Currency |
| `WRBTR` | WRBTR | — | CURR | 13 | 2 | Amount in document currency |
| `KZBTR` | KZBTR_FI | — | CURR | 13 | 2 | Original Reduction Amount in Local Currency |
| `PSWBT` | PSWBT | — | CURR | 13 | 2 | Amount for Updating in General Ledger |
| `PSWSL` | PSWSL | TCURC | CUKY | 5 | 0 | Update Currency for General Ledger Transaction Figures |
| `TXBHW` | TXBHW | — | CURR | 13 | 2 | Original Tax Base Amount in Local Currency |
| `TXBFW` | TXBFW | — | CURR | 13 | 2 | Original Tax Base Amount in Document Currency |
| `MWSTS` | MWSTS | — | CURR | 13 | 2 | Tax Amount in Local Currency |
| `WMWST` | WMWST | — | CURR | 13 | 2 | Tax amount in document currency |
| `HWBAS` | HWBAS | — | CURR | 13 | 2 | Tax Base Amount in Local Currency |
| `FWBAS` | FWBAS | — | CURR | 13 | 2 | Tax Base Amount in Document Currency |
| `HWZUZ` | HWZUZ | — | CURR | 13 | 2 | Provision Amount in Local Currency |
| `FWZUZ` | FWZUZ | — | CURR | 13 | 2 | Additional Tax in Document Currency |
| `SHZUZ` | SHZUZ | — | CHAR | 1 | 0 | Debit/Credit Addition for Cash Discount |
| `STEKZ` | CHAR2 | — | CHAR | 2 | 0 | Version Number Component |
| `MWART` | MWART | — | CHAR | 1 | 0 | Tax Type |
| `TXGRP` | TXGRP | — | NUMC | 3 | 0 | Group Indicator for Tax Line Items |
| `KTOSL` | KTOSL | — | CHAR | 3 | 0 | Transaction Key |
| `QSSHB` | QSSHB | — | CURR | 13 | 2 | Withholding Tax Base Amount |
| `KURSR` | KURSR | — | DEC | 9 | 5 | Hedged Exchange Rate |
| `GBETR` | GBETR | — | CURR | 13 | 2 | Hedged Amount in Foreign Currency |
| `BDIFF` | BDIFF | — | CURR | 13 | 2 | Valuation Difference |
| `BDIF2` | BDIF2 | — | CURR | 13 | 2 | Valuation Difference for the Second Local Currency |
| `VALUT` | VALUT | — | DATS | 8 | 0 | Value date |
| `ZUONR` | DZUONR | — | CHAR | 18 | 0 | Assignment Number |
| `SGTXT` | SGTXT | — | CHAR | 50 | 0 | Item Text |
| `ZINKZ` | DZINKZ | — | CHAR | 2 | 0 | Exempted from interest calculation |
| `VBUND` | RASSC | T880 | CHAR | 6 | 0 | Company ID of trading partner |
| `BEWAR` | RMVCT | T856 | CHAR | 3 | 0 | Transaction Type |
| `ALTKT` | BILKT_SKA1 | — | CHAR | 10 | 0 | Group account number |
| `VORGN` | VORGN | — | CHAR | 4 | 0 | Transaction Type for General Ledger |
| `FDLEV` | FDLEV | T036 | CHAR | 2 | 0 | Planning level |
| `FDGRP` | FDGRP | T035 | CHAR | 10 | 0 | Planning Group |
| `FDWBT` | FDWBT | — | CURR | 13 | 2 | Planning amount in document currency |
| `FDTAG` | FDTAG | — | DATS | 8 | 0 | Planning date |
| `FKONT` | FIPLS | — | NUMC | 3 | 0 | Financial Budget Item |
| `KOKRS` | KOKRS | TKA01 | CHAR | 4 | 0 | Controlling Area |
| `KOSTL` | KOSTL | — | CHAR | 10 | 0 | Cost Center |
| `PROJN` | PROJN | — | CHAR | 16 | 0 | Old: Project number : No longer used --&gt; PS_POSNR |
| `AUFNR` | AUFNR | AUFK | CHAR | 12 | 0 | Order Number |
| `VBELN` | VBELN_VF | VBUK | CHAR | 10 | 0 | Billing Document |
| `VBEL2` | VBELN_VA | VBUK | CHAR | 10 | 0 | Sales Document |
| `POSN2` | POSNR_VA | VBUP | NUMC | 6 | 0 | Sales Document Item |
| `ETEN2` | ETENR | VBEP | NUMC | 4 | 0 | Delivery Schedule Line Number |
| `ANLN1` | ANLN1 | ANLH | CHAR | 12 | 0 | Main Asset Number |
| `ANLN2` | ANLN2 | ANLA | CHAR | 4 | 0 | Asset Subnumber |
| `ANBWA` | ANBWA | TABW | CHAR | 3 | 0 | Asset Transaction Type |
| `BZDAT` | BZDAT | — | DATS | 8 | 0 | Asset value date |
| `PERNR` | PERNR_D | — | NUMC | 8 | 0 | Personnel Number |
| `XUMSW` | XUMSW | — | CHAR | 1 | 0 | Indicator: Sales-related item ? |
| `XHRES` | XHRES | — | CHAR | 1 | 0 | Indicator: Resident G/L account? |
| `XKRES` | XKRES | — | CHAR | 1 | 0 | Indicator: Can Line Items Be Displayed by Account? |
| `XOPVW` | XOPVW | — | CHAR | 1 | 0 | Indicator: Open item management? |
| `XCPDD` | XCPDD | — | CHAR | 1 | 0 | Indicator: Address and bank data set individually |
| `XSKST` | XSKST | — | CHAR | 1 | 0 | Indicator: Statistical posting to cost center |
| `XSAUF` | XSAUF | — | CHAR | 1 | 0 | Indicator: Posting to order is statistical |
| `XSPRO` | XSPRO | — | CHAR | 1 | 0 | Indicator: Posting to project is statistical |
| `XSERG` | XSERG | — | CHAR | 1 | 0 | Indicator: Posting to prof.analysis is statistical |
| `XFAKT` | XFAKT | — | CHAR | 1 | 0 | Indicator: Billing document update successful ? |
| `XUMAN` | XUMAN | — | CHAR | 1 | 0 | Indicator: Transfer posting from down payment ? |
| `XANET` | XANET | — | CHAR | 1 | 0 | Indicator: Down payment in net procedure ? |
| `XSKRL` | XSKRL | — | CHAR | 1 | 0 | Indicator: Line item not liable to cash discount? |
| `XINVE` | XINVE | — | CHAR | 1 | 0 | Indicator: Capital Goods Affected? |
| `XPANZ` | XPANZ | — | CHAR | 1 | 0 | Display item |
| `XAUTO` | XAUTO | — | CHAR | 1 | 0 | Indicator: Line item automatically created |
| `XNCOP` | XNCOP | — | CHAR | 1 | 0 | Indicator: Items cannot be copied? |
| `XZAHL` | XZAHL | — | CHAR | 1 | 0 | Indicator: Is the posting key used in a payment transaction? |
| `SAKNR` | SAKNR | SKB1 | CHAR | 10 | 0 | G/L Account Number |
| `HKONT` | HKONT | SKB1 | CHAR | 10 | 0 | General Ledger Account |
| `KUNNR` | KUNNR | KNA1 | CHAR | 10 | 0 | Customer Number |
| `LIFNR` | LIFNR | LFA1 | CHAR | 10 | 0 | Account Number of Vendor or Creditor |
| `FILKD` | FILKD | — | CHAR | 10 | 0 | Account Number of the Branch |
| `XBILK` | XBILK | — | CHAR | 1 | 0 | Indicator: Account is a balance sheet account? |
| `GVTYP` | GVTYP | — | CHAR | 2 | 0 | P&amp;L statement account type |
| `HZUON` | HZUON | — | CHAR | 18 | 0 | Assignment Number for Special G/L Accounts |
| `ZFBDT` | DZFBDT | — | DATS | 8 | 0 | Baseline Date for Due Date Calculation |
| `ZTERM` | DZTERM | — | CHAR | 4 | 0 | Terms of Payment Key |
| `ZBD1T` | DZBD1T | — | DEC | 3 | 0 | Cash discount days 1 |
| `ZBD2T` | DZBD2T | — | DEC | 3 | 0 | Cash discount days 2 |
| `ZBD3T` | DZBD3T | — | DEC | 3 | 0 | Net Payment Terms Period |
| `ZBD1P` | DZBD1P | — | DEC | 5 | 3 | Cash Discount Percentage 1 |
| `ZBD2P` | DZBD2P | — | DEC | 5 | 3 | Cash Discount Percentage 2 |
| `SKFBT` | SKFBT | — | CURR | 13 | 2 | Amount Eligible for Cash Discount in Document Currency |
| `SKNTO` | SKNTO | — | CURR | 13 | 2 | Cash discount amount in local currency |
| `WSKTO` | WSKTO | — | CURR | 13 | 2 | Cash discount amount in document currency |
| `ZLSCH` | SCHZW_BSEG | T042Z | CHAR | 1 | 0 | Payment Method |
| `ZLSPR` | DZLSPR | T008 | CHAR | 1 | 0 | Payment Block Key |
| `ZBFIX` | DZBFIX | — | CHAR | 1 | 0 | Fixed Payment Terms |
| `HBKID` | HBKID | T012 | CHAR | 5 | 0 | Short Key for a House Bank |
| `BVTYP` | BVTYP | — | CHAR | 4 | 0 | Partner Bank Type |
| `NEBTR` | NEBTR | — | CURR | 13 | 2 | Net Payment Amount |
| `MWSK1` | MWSKX | T007A | CHAR | 2 | 0 | Tax Code for Distribution |
| `DMBT1` | DMBTX | — | CURR | 13 | 2 | Amount in Local Currency for Tax Distribution |
| `WRBT1` | WRBTX | — | CURR | 13 | 2 | Amount in foreign currency for tax breakdown |
| `MWSK2` | MWSKX | T007A | CHAR | 2 | 0 | Tax Code for Distribution |
| `DMBT2` | DMBTX | — | CURR | 13 | 2 | Amount in Local Currency for Tax Distribution |
| `WRBT2` | WRBTX | — | CURR | 13 | 2 | Amount in foreign currency for tax breakdown |
| `MWSK3` | MWSKX | T007A | CHAR | 2 | 0 | Tax Code for Distribution |
| `DMBT3` | DMBTX | — | CURR | 13 | 2 | Amount in Local Currency for Tax Distribution |
| `WRBT3` | WRBTX | — | CURR | 13 | 2 | Amount in foreign currency for tax breakdown |
| `REBZG` | REBZG | — | CHAR | 10 | 0 | Number of the Invoice the Transaction Belongs to |
| `REBZJ` | REBZJ | — | NUMC | 4 | 0 | Fiscal Year of the Relevant Invoice (for Credit Memo) |
| `REBZZ` | REBZZ | — | NUMC | 3 | 0 | Line Item in the Relevant Invoice |
| `REBZT` | REBZT | — | CHAR | 1 | 0 | Follow-On Document Type |
| `ZOLLT` | DZOLLT | — | CHAR | 8 | 0 | Customs Tariff Number |
| `ZOLLD` | DZOLLD | — | DATS | 8 | 0 | Customs Date |
| `LZBKZ` | LZBKZ | T015L | CHAR | 3 | 0 | State Central Bank Indicator |
| `LANDL` | LANDL | T005 | CHAR | 3 | 0 | Supplying Country |
| `DIEKZ` | DIEKZ | — | CHAR | 1 | 0 | Service Indicator (Foreign Payment) |
| `SAMNR` | SAMNR | — | NUMC | 8 | 0 | Invoice List Number |
| `ABPER` | ABPER_RF | — | ACCP | 6 | 0 | Settlement period |
| `VRSKZ` | VRSKZ | — | CHAR | 1 | 0 | Insurance indicator |
| `VRSDT` | VRSDT | — | DATS | 8 | 0 | Insurance date |
| `DISBN` | DISBN | — | CHAR | 10 | 0 | Number of Bill of Exchange Usage Document (Discount Doc.) |
| `DISBJ` | DISBJ | — | NUMC | 4 | 0 | Fiscal Year of Bill of Exchange Usage Document |
| `DISBZ` | DISBZ | — | NUMC | 3 | 0 | Line Item within the Bill of Exchange Usage Document |
| `WVERW` | WVERW | — | CHAR | 1 | 0 | Bill of exchange usage type |
| `ANFBN` | ANFBN | — | CHAR | 10 | 0 | Document Number of the Bill of Exchange Payment Request |
| `ANFBJ` | ANFBJ | — | NUMC | 4 | 0 | Fiscal Year of the Bill of Exchange Payment Request Document |
| `ANFBU` | ANFBU | T001 | CHAR | 4 | 0 | Company Code in Which Bill of Exch.Payment Request Is Posted |
| `ANFAE` | ANFAE | — | DATS | 8 | 0 | Bill of Exchange Payment Request Due Date |
| `BLNBT` | BLNBT | — | CURR | 13 | 2 | Base Amount for Determining the Preference Amount |
| `BLNKZ` | BLNKZ | — | CHAR | 2 | 0 | Subsidy indicator for determining the reduction rates |
| `BLNPZ` | BLNPZ | — | DEC | 7 | 2 | Preference Percentage Rate |
| `MSCHL` | MSCHL | T040 | CHAR | 1 | 0 | Dunning key |
| `MANSP` | MANSP | T040S | CHAR | 1 | 0 | Dunning block |
| `MADAT` | MADAT | — | DATS | 8 | 0 | Last dunned on |
| `MANST` | MAHNS_D | — | NUMC | 1 | 0 | Dunning level |
| `MABER` | MABER | T047M | CHAR | 2 | 0 | Dunning Area |
| `ESRNR` | ESRNR | — | CHAR | 11 | 0 | ISR Subscriber Number |
| `ESRRE` | ESRRE | — | CHAR | 27 | 0 | ISR Reference Number |
| `ESRPZ` | ESRPZ | — | CHAR | 2 | 0 | ISR Check Digit |
| `KLIBT` | KLIBT | — | CURR | 13 | 2 | Credit Control Amount |
| `QSZNR` | QSZNR | — | CHAR | 10 | 0 | Certificate Number of the Withholding Tax Exemption |
| `QBSHB` | QBSHB | — | CURR | 13 | 2 | Withholding Tax Amount (in Document Currency) |
| `QSFBT` | QSFBT | — | CURR | 13 | 2 | Withholding Tax-Exempt Amount (in Document Currency) |
| `NAVHW` | NAVHW | — | CURR | 13 | 2 | Non-Deductible Input Tax (in Local Currency) |
| `NAVFW` | NAVFW | — | CURR | 13 | 2 | Non-Deductible Input Tax (in Document Currency) |
| `MATNR` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `WERKS` | WERKS_D | T001W | CHAR | 4 | 0 | Plant |
| `MENGE` | MENGE_D | — | QUAN | 13 | 3 | Quantity |
| `MEINS` | MEINS | T006 | UNIT | 3 | 0 | Base Unit of Measure |
| `ERFMG` | ERFMG | — | QUAN | 13 | 3 | Quantity in Unit of Entry |
| `ERFME` | ERFME | T006 | UNIT | 3 | 0 | Unit of Entry |
| `BPMNG` | BPMNG | — | QUAN | 13 | 3 | Quantity in Purchase Order Price Unit |
| `BPRME` | BPRME | T006 | UNIT | 3 | 0 | Order Price Unit (Purchasing) |
| `EBELN` | EBELN | EKKO | CHAR | 10 | 0 | Purchasing Document Number |
| `EBELP` | EBELP | EKPO | NUMC | 5 | 0 | Item Number of Purchasing Document |
| `ZEKKN` | DZEKKN | — | NUMC | 2 | 0 | Sequential Number of Account Assignment |
| `ELIKZ` | ELIKZ | — | CHAR | 1 | 0 | &quot;Delivery Completed&quot; Indicator |
| `VPRSV` | VPRSV | — | CHAR | 1 | 0 | Price control indicator |
| `PEINH` | PEINH | — | DEC | 5 | 0 | Price Unit |
| `BWKEY` | BWKEY | T001K | CHAR | 4 | 0 | Valuation Area |
| `BWTAR` | BWTAR_D | T149D | CHAR | 10 | 0 | Valuation Type |
| `BUSTW` | BUSTW | — | CHAR | 4 | 0 | Posting string for values |
| `REWRT` | REEWR | — | CURR | 13 | 2 | Invoice Value Entered (in Local Currency) |
| `REWWR` | REFWR | — | CURR | 13 | 2 | Invoice value in foreign currency |
| `BONFB` | BONFB | — | CURR | 13 | 2 | Amount Qualifying for Bonus in Local Currency |
| `BUALT` | BUALT | — | CURR | 13 | 2 | Amount posted in alternative price control |
| `PSALT` | PSALT | — | CHAR | 1 | 0 | Alternative Price Control |
| `NPREI` | NPREI | — | CURR | 11 | 2 | New price |
| `TBTKZ` | TBTKZ | — | CHAR | 1 | 0 | Indicator: subsequent debit/credit |
| `SPGRP` | SPGRP | — | CHAR | 1 | 0 | Blocking reason: price |
| `SPGRM` | SPGRM | — | CHAR | 1 | 0 | Blocking reason: quantity |
| `SPGRT` | SPGRT | — | CHAR | 1 | 0 | Blocking Reason: Date |
| `SPGRG` | SPGRG | — | CHAR | 1 | 0 | Blocking reason: order price quantity |
| `SPGRV` | SPGRV | — | CHAR | 1 | 0 | Blocking reason: project budget |
| `SPGRQ` | SPGRQ | — | CHAR | 1 | 0 | Manual Blocking Reason |
| `STCEG` | STCEG | — | CHAR | 20 | 0 | VAT Registration Number |
| `EGBLD` | EGBLD | T005 | CHAR | 3 | 0 | Country of Destination for Delivery of Goods |
| `EGLLD` | EGLLD | T005 | CHAR | 3 | 0 | Supplying Country for Delivery of Goods |
| `RSTGR` | RSTGR | T053R | CHAR | 3 | 0 | Reason Code for Payments |
| `RYACQ` | RYACQ | — | CHAR | 4 | 0 | Year of acquisition |
| `RPACQ` | RPACQ | — | NUMC | 3 | 0 | Period of Acquisition |
| `RDIFF` | RDIFF | — | CURR | 13 | 2 | Exchange Rate Gain/Loss Realized |
| `RDIF2` | RDIF2 | — | CURR | 13 | 2 | Exchange Rate Difference Realized for Second Local Currency |
| `PRCTR` | PRCTR | — | CHAR | 10 | 0 | Profit Center |
| `XHKOM` | XHKOM | — | CHAR | 1 | 0 | Indicator: G/L account assigned manually ? |
| `VNAME` | JV_NAME | T8JV | CHAR | 6 | 0 | Joint Venture |
| `RECID` | JV_RECIND | T8JJ | CHAR | 2 | 0 | Recovery Indicator |
| `EGRUP` | JV_EGROUP | T8JF | CHAR | 3 | 0 | Equity group |
| `VPTNR` | JV_PART | KNA1 | CHAR | 10 | 0 | Partner account number |
| `VERTT` | RANTYP | — | CHAR | 1 | 0 | Contract Type |
| `VERTN` | RANL | — | CHAR | 13 | 0 | Contract Number |
| `VBEWA` | SBEWART | — | CHAR | 4 | 0 | Flow Type |
| `DEPOT` | RLDEPO | — | CHAR | 10 | 0 | Securities Account |
| `TXJCD` | TXJCD | TTXJ | CHAR | 15 | 0 | Tax Jurisdiction |
| `IMKEY` | IMKEY | — | CHAR | 8 | 0 | Internal Key for Real Estate Object |
| `DABRZ` | DABRBEZ | — | DATS | 8 | 0 | Reference Date for Settlement |
| `POPTS` | POPTSATZ | — | DEC | 9 | 6 | Real estate option rate |
| `FIPOS` | FIPOS | — | CHAR | 14 | 0 | Commitment Item |
| `KSTRG` | KSTRG | — | CHAR | 12 | 0 | Cost Object |
| `NPLNR` | NPLNR | — | CHAR | 12 | 0 | Network Number for Account Assignment |
| `AUFPL` | AUFPL_CH | — | NUMC | 10 | 0 | Task list number for operations in order |
| `APLZL` | APLZL_CH | — | NUMC | 8 | 0 | General counter for order |
| `PROJK` | PS_PSP_PNR | — | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `PAOBJNR` | RKEOBJNR | — | NUMC | 10 | 0 | Profitability Segment Number (CO-PA) |
| `PASUBNR` | RKESUBNR | — | NUMC | 4 | 0 | Profitability segment changes (CO-PA) |
| `SPGRS` | SPGRS | — | CHAR | 1 | 0 | Blocking Reason: Item Amount |
| `SPGRC` | SPGRC | — | CHAR | 1 | 0 | Block.reason: quality |
| `BTYPE` | JV_BILIND | T8JA | CHAR | 2 | 0 | Payroll Type |
| `ETYPE` | JV_ETYPE | T8JE | CHAR | 3 | 0 | Equity type |
| `XEGDR` | XEGDR | — | CHAR | 1 | 0 | Indicator: Triangular deal within the EU ? |
| `LNRAN` | LNRAN | — | NUMC | 5 | 0 | Sequence number of asset line items in fiscal year |
| `HRKFT` | HRKFT | — | CHAR | 4 | 0 | Origin Group as Subdivision of Cost Element |
| `DMBE2` | DMBE2 | — | CURR | 13 | 2 | Amount in Second Local Currency |
| `DMBE3` | DMBE3 | — | CURR | 13 | 2 | Amount in Third Local Currency |
| `DMB21` | DMB2X | — | CURR | 13 | 2 | Amount in Second Local Currency for Tax Breakdown |
| `DMB22` | DMB2X | — | CURR | 13 | 2 | Amount in Second Local Currency for Tax Breakdown |
| `DMB23` | DMB2X | — | CURR | 13 | 2 | Amount in Second Local Currency for Tax Breakdown |
| `DMB31` | DMB3X | — | CURR | 13 | 2 | Amount in Third Local Currency for Tax Breakdown |
| `DMB32` | DMB3X | — | CURR | 13 | 2 | Amount in Third Local Currency for Tax Breakdown |
| `DMB33` | DMB3X | — | CURR | 13 | 2 | Amount in Third Local Currency for Tax Breakdown |
| `MWST2` | MWST2 | — | CURR | 13 | 2 | Tax Amount in Second Local Currency |
| `MWST3` | MWST3 | — | CURR | 13 | 2 | Tax Amount in Third Local Currency |
| `NAVH2` | NAVH2 | — | CURR | 13 | 2 | Non-Deductible Input Tax in Second Local Currency |
| `NAVH3` | NAVH3 | — | CURR | 13 | 2 | Non-Deductible Input Tax in Third Local Currency |
| `SKNT2` | SKNT2 | — | CURR | 13 | 2 | Cash Discount Amount in Second Local Currency |
| `SKNT3` | SKNT3 | — | CURR | 13 | 2 | Cash Discount Amount in Third Local Currency |
| `BDIF3` | BDIF3 | — | CURR | 13 | 2 | Valuation Difference for the Third Local Currency |
| `RDIF3` | RDIF3 | — | CURR | 13 | 2 | Exchange Rate Difference Realized for Third Local Currency |
| `HWMET` | HWMET | — | CHAR | 1 | 0 | Method with Which the Local Currency Amount Was Determined |
| `GLUPM` | GLUPM | — | CHAR | 1 | 0 | Update Method for FM - FI-CA Integration |
| `XRAGL` | XRAGL | — | CHAR | 1 | 0 | Indicator: Clearing was Reversed |
| `UZAWE` | UZAWE | T042F | CHAR | 2 | 0 | Payment Method Supplement |
| `LOKKT` | ALTKT_SKB1 | — | CHAR | 10 | 0 | Alternative account number in company code |
| `FISTL` | FISTL | — | CHAR | 16 | 0 | Funds Center |
| `GEBER` | BP_GEBER | — | CHAR | 10 | 0 | Fund |
| `STBUK` | STBUK | — | CHAR | 4 | 0 | Tax Company Code |
| `TXBH2` | TXBH2 | — | CURR | 13 | 2 | Tax Base/Original Tax Base in Second Local Currency |
| `TXBH3` | TXBH3 | — | CURR | 13 | 2 | Tax Base/Original Tax Base in Third Local Currency |
| `PPRCT` | PPRCTR | CEPC | CHAR | 10 | 0 | Partner Profit Center |
| `XREF1` | XREF1 | — | CHAR | 12 | 0 | Business partner reference key |
| `XREF2` | XREF2 | — | CHAR | 12 | 0 | Business partner reference key |
| `KBLNR` | KBLNR_FI | KBLK | CHAR | 10 | 0 | Document Number for Earmarked Funds |
| `KBLPOS` | KBLPOS | KBLP | NUMC | 3 | 0 | Earmarked Funds: Document Item |
| `STTAX` | STTAX | — | CURR | 13 | 2 | Tax amount as statistical information in document currency |
| `FKBER` | FKBER_SHORT | — | CHAR | 4 | 0 | Functional Area |
| `OBZEI` | OBZEI | — | NUMC | 3 | 0 | Number of Line Item in Original Document |
| `XNEGP` | XNEGP | — | CHAR | 1 | 0 | Indicator: Negative posting |
| `RFZEI` | RFZEI_CC | — | NUMC | 3 | 0 | Payment Card Item |
| `CCBTC` | CCBTC | — | CHAR | 10 | 0 | Payment cards: Settlement run |
| `KKBER` | KKBER | T014 | CHAR | 4 | 0 | Credit control area |
| `EMPFB` | EMPFB | — | CHAR | 10 | 0 | Payee/Payer |
| `XREF3` | XREF3 | — | CHAR | 20 | 0 | Reference key for line item |
| `DTWS1` | DTAT16 | — | NUMC | 2 | 0 | Instruction key 1 |
| `DTWS2` | DTAT17 | — | NUMC | 2 | 0 | Instruction key 2 |
| `DTWS3` | DTAT18 | — | NUMC | 2 | 0 | Instruction key 3 |
| `DTWS4` | DTAT19 | — | NUMC | 2 | 0 | Instruction key 4 |
| `GRICD` | J_1AGICD_D | J_1AGICD | CHAR | 2 | 0 | Activity Code for Gross Income Tax |
| `GRIRG` | REGIO | T005S | CHAR | 3 | 0 | Region (State, Province, County) |
| `GITYP` | J_1ADTYP_D | J_1ADTYP | CHAR | 2 | 0 | Distribution Type for Employment Tax |
| `XPYPR` | XPYPR | — | CHAR | 1 | 0 | Indicator: Items from Payment Program Blocked |
| `KIDNO` | KIDNO | — | CHAR | 30 | 0 | Payment Reference |
| `ABSBT` | ABSBT | — | CURR | 13 | 2 | Credit management: Hedged amount |
| `IDXSP` | J_1AINDXSP | J_1AINFT20 | CHAR | 5 | 0 | Inflation Index |
| `LINFV` | J_1ALINFVL | — | DATS | 8 | 0 | Last Adjustment Date |
| `KONTT` | KONTT_FI | — | CHAR | 2 | 0 | Account Assignment Category for Industry Solution |
| `KONTL` | KONTL_FI | — | CHAR | 50 | 0 | Acct assignment string for industry-specific acct assignmnts |
| `TXDAT` | TXDAT | — | DATS | 8 | 0 | Date for defining tax rates |
| `AGZEI` | AGZEI | — | DEC | 5 | 0 | Clearing Item |
| `PYCUR` | PYCUR | TCURC | CUKY | 5 | 0 | Currency for Automatic Payment |
| `PYAMT` | PYAMT | — | CURR | 13 | 2 | Amount in Payment Currency |
| `BUPLA` | BUPLA | J_1BBRANCH | CHAR | 4 | 0 | Business Place |
| `SECCO` | SECCO | SECCODE | CHAR | 4 | 0 | Section Code |
| `LSTAR` | LSTAR | — | CHAR | 6 | 0 | Activity Type |
| `CESSION_KZ` | CESSION_KZ | TCESSION | CHAR | 2 | 0 | Accounts Receivable Pledging Indicator |
| `PRZNR` | CO_PRZNR | — | CHAR | 12 | 0 | Business Process |
| `PPDIFF` | PPDIFF | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 1.Loc.Curr.(Part Payments) |
| `PPDIF2` | PPDIF2 | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 2.Loc. Curr.(Part Payments) |
| `PPDIF3` | PPDIF3 | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 3.Loc.Curr.(Part Payments) |
| `PENLC1` | PENALTY1 | — | CURR | 13 | 2 | Penalty charge amount in first local currency |
| `PENLC2` | PENALTY2 | — | CURR | 13 | 2 | Penalty charge amount in second local currency |
| `PENLC3` | PENALTY3 | — | CURR | 13 | 2 | Penalty Charge Amount in Third Local Currency |
| `PENFC` | PENALTY | — | CURR | 13 | 2 | Penalty charge amount in document currency |
| `PENDAYS` | PDAYS | — | INT4 | 10 | 0 | Number of days for penalty charge calculation |
| `PENRC` | PENRC | — | CHAR | 2 | 0 | Reason for late payment |
| `GRANT_NBR` | GM_GRANT_NBR | — | CHAR | 20 | 0 | Grant |
| `SCTAX` | SCTAX | — | CURR | 13 | 2 | Tax portion FI-CA local currency |
| `FKBER_LONG` | FKBER | — | CHAR | 16 | 0 | Functional Area |
| `GMVKZ` | FM_GMVKZ | — | CHAR | 1 | 0 | Item is in Execution |
| `SRTYPE` | FM_SRTYPE | — | CHAR | 2 | 0 | Type of Additional Receivable |
| `INTRENO` | VVINTRENO | — | CHAR | 13 | 0 | Internal Real Estate Master Data Code |
| `MEASURE` | FM_MEASURE | — | CHAR | 24 | 0 | Funded Program |
| `AUGGJ` | AUGGJ | — | NUMC | 4 | 0 | Fiscal Year of Clearing Document |
| `PPA_EX_IND` | EXCLUDE_FLG | — | CHAR | 1 | 0 | PPA Exclude Indicator |
| `DOCLN` | DOCLN6 | — | CHAR | 6 | 0 | Six-Character Posting Item for Ledger |
| `SEGMENT` | FB_SEGMENT | — | CHAR | 10 | 0 | Segment for Segmental Reporting |
| `PSEGMENT` | FB_PSEGMENT | — | CHAR | 10 | 0 | Partner Segment for Segmental Reporting |
| `PFKBER` | SFKBER | — | CHAR | 16 | 0 | Partner Functional Area |
| `HKTID` | HKTID | T012K | CHAR | 5 | 0 | ID for account details |
| `KSTAR` | KSTAR | — | CHAR | 10 | 0 | Cost Element |
| `XLGCLR` | XLGCLR | — | CHAR | 1 | 0 | Clearing Specific to Ledger Groups |
| `TAXPS` | TAX_POSNR | — | NUMC | 6 | 0 | Tax document item number |
| `PAYS_PROV` | COM_WEC_PAYMENT_SRV_PROVIDER | — | CHAR | 4 | 0 | Payment Service Provider |
| `PAYS_TRAN` | FPS_TRANSACTION | — | CHAR | 35 | 0 | Payment Reference of Payment Service Provider |
| `MNDID` | SEPA_MNDID | — | CHAR | 35 | 0 | Unique Referene to Mandate per Payment Recipient |
| `XFRGE_BSEG` | XFRGE_BSEG | — | CHAR | 1 | 0 | Payment Is Released |
| `RE_BUKRS` | FAGL_RE_BUKRS | — | CHAR | 4 | 0 | Cash Ledger: Company Code for Expense/Revenue |
| `RE_ACCOUNT` | FAGL_RE_ACCOUNT | — | CHAR | 10 | 0 | Cash Ledger: Expense or Revenue Account |
| `PGEBER` | FM_PFUND | — | CHAR | 10 | 0 | Partner Fund |
| `PGRANT_NBR` | GM_GRANT_PARTNER | — | CHAR | 20 | 0 | Partner Grant |
| `BUDGET_PD` | FM_BUDGET_PERIOD | — | CHAR | 10 | 0 | FM: Budget Period |
| `PBUDGET_PD` | FM_PBUDGET_PERIOD | — | CHAR | 10 | 0 | FM: Partner Budget Period |
| `PEROP_BEG` | FM_PEROP_FI_LOW | — | DATS | 8 | 0 | Billing Period of Performance Start Date |
| `PEROP_END` | FM_PEROP_FI_HIGH | — | DATS | 8 | 0 | Billing Period of Performance End Date |
| `FASTPAY` | FMFG_FASTPAY_FLG | — | CHAR | 1 | 0 | PPA Fast Pay Indicator |
| `IGNR_IVREF` | FMFG_IGNORE_INV_REF | — | CHAR | 1 | 0 | FMFG: Ignore the invoice reference during FI doc splitting |
| `FMXDOCNR` | FM_XDOCNR | — | CHAR | 10 | 0 | FM Reference Document Number |
| `FMXYEAR` | FM_XYEAR | — | NUMC | 4 | 0 | FM Reference Year |
| `FMXDOCLN` | FM_XDOCLN | — | NUMC | 6 | 0 | FM Reference Line Item |
| `FMXZEKKN` | FM_XZEKKN | — | NUMC | 5 | 0 | FM Reference Sequence Account Assignment |
| `PRODPER` | JV_PRODPER | — | DATS | 8 | 0 | Production Month (Date to find period and year) |
| `OITAXFROM` | OIH_TAXFRO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;from&#039; location |
| `OITAXTO` | OIH_TAXTO | OIH4 | CHAR | 2 | 0 | Excise duty tax key for &#039;to&#039; location |
| `OIFULTAX` | OIH_FULTAX | — | CURR | 13 | 2 | Excise duty tax value at the full rate |
| `OIHANTYPE` | OIH_HANTYP | OIH5 | CHAR | 2 | 0 | Excise Duty Handling Type |
| `OITAXGRP` | OIH_TAXGRP | OIH2 | CHAR | 2 | 0 | Excise Duty Group |
| `OIPRICIE` | OIH_PRICIE | — | CHAR | 1 | 0 | ED pricing: external (indicator) |
| `OIINVREC` | OIH_INVREC | — | CHAR | 1 | 0 | Indicator whether ED pricing is external (not used?) |
| `OITXVAL0` | OIH_TXVAL0 | — | CURR | 13 | 2 | Excise duty tax value 0 |
| `OITXVAL1` | OIH_TXVAL1 | — | CURR | 13 | 2 | Excise duty tax value 1 |
| `OITXVAL2` | OIH_TXVAL2 | — | CURR | 13 | 2 | Excise duty tax value 2 |
| `OITXVAL3` | OIH_TXVAL3 | — | CURR | 13 | 2 | Excise duty tax value 3 |
| `OITXVAL4` | OIH_TXVAL4 | — | CURR | 13 | 2 | Excise duty tax value 4 |
| `OITXVAL5` | OIH_TXVAL5 | — | CURR | 13 | 2 | Excise duty tax value 5 |
| `OITXVAL6` | OIH_TXVAL6 | — | CURR | 13 | 2 | Excise duty tax value 6 |
| `OIOILCON` | OIH_OILCON | — | DEC | 5 | 2 | Oil content in a material as a percentage |
| `OITAXCON` | OIH_TAXCON | — | CURR | 13 | 2 | Excise duty tax from pricing conditions |
| `OITAXVAL` | OIH_TAXVAL | — | CURR | 13 | 2 | Excise duty value in material inventory account |
| `OIOILCON2` | OIH_OILCN2 | — | DEC | 5 | 2 | Oil content of a material as a percentage (2) |
| `OIUOMQT` | OIH_UOMQT | T006 | UNIT | 3 | 0 | Base quantity for excise duty rate (e.g.per 1 or 100 UoM) |
| `OITAXQT` | OIH_TAXQT | — | QUAN | 13 | 3 | Excise duty tax quantity in STBME |
| `OIFUTQT` | OIH_FUTQT | — | QUAN | 13 | 3 | Future tax quantity |
| `OIFUTTX` | OIH_FUTTX | — | CURR | 13 | 2 | Future tax value |
| `OIFUTDT` | OIH_FUTDT | — | DATS | 8 | 0 | Future tax date |
| `OIFUTQT2` | OIH_FUTQT2 | — | QUAN | 13 | 3 | Future tax quantity 2 |
| `OIFUTTX2` | OIH_FUTTX2 | — | CURR | 13 | 2 | Future tax value 2 |
| `OIFUTDT2` | OIH_FUTDT2 | — | DATS | 8 | 0 | Future tax date 2 |
| `OITAXGRP2` | OIH_TAXGRP | OIH2 | CHAR | 2 | 0 | Excise Duty Group |
| `OICIMAP` | OIA_CIMAP | — | CHAR | 1 | 0 | Change internal moving average price |
| `OIHANTYP` | OIH_HANTYP | OIH5 | CHAR | 2 | 0 | Excise Duty Handling Type |
| `OIVATH` | DMBTR | — | CURR | 13 | 2 | Amount in Local Currency |
| `OIVATF` | WRBTR | — | CURR | 13 | 2 | Amount in document currency |
| `OINETCYC` | OIA_NETCYC | — | CHAR | 1 | 0 | Netting cycle (FI blocking indicator) |
| `OIA_IPMVAT` | OIA_IPMVAT | — | CHAR | 1 | 0 | VAT on internally-posted material |
| `OIEXGNUM` | OIA_EXGNUM | — | CHAR | 10 | 0 | Exchange agreement number |
| `OIEXGTYP` | OIA_EXGTYP | — | CHAR | 4 | 0 | Exchange type |
| `OINEGPSTG` | OIA_NGPSTL | — | CHAR | 1 | 0 | Negative posting line (exchange fees) |
| `RECID_MAN` | — | — | CHAR | 1 | 0 | RECID_MAN |
| `OIPOSTZERO` | OIH_PSTZRO | — | CHAR | 1 | 0 | Post zero amounts |
| `OIINVCYC` | OIA_INVCYC | TOIA10 | NUMC | 1 | 0 | Invoice cycle |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ANBWA` | BSEG | MANDT | TABW |  | |
| `ANBWA` | BSEG | ANBWA | TABW |  | |
| `ANFBU` | BSEG | MANDT | T001 |  | |
| `ANFBU` | BSEG | ANFBU | T001 |  | |
| `ANLN1` | BSEG | ANLN1 | ANLH |  | |
| `ANLN1` | BSEG | MANDT | ANLH |  | |
| `ANLN1` | BKPF | BUKRS | ANLH |  | |
| `ANLN2` | BSEG | MANDT | ANLA |  | |
| `ANLN2` | BSEG | BUKRS | ANLA |  | |
| `ANLN2` | BSEG | ANLN1 | ANLA |  | |
| `ANLN2` | BSEG | ANLN2 | ANLA |  | |
| `AUFNR` | BSEG | MANDT | AUFK |  | |
| `AUFNR` | BSEG | AUFNR | AUFK |  | |
| `BEWAR` | BSEG | MANDT | T856 |  | |
| `BEWAR` | BSEG | BEWAR | T856 |  | |
| `BPRME` | BSEG | MANDT | T006 |  | |
| `BPRME` | BSEG | BPRME | T006 |  | |
| `BSCHL` | BSEG | MANDT | TBSL |  | |
| `BSCHL` | BSEG | BSCHL | TBSL |  | |
| `BTYPE` | BSEG | MANDT | T8JA |  | |
| `BTYPE` | BSEG | BTYPE | T8JA |  | |
| `BUKRS` | BSEG | MANDT | T001 |  | |
| `BUKRS` | BSEG | BUKRS | T001 |  | |
| `BUPLA` | BSEG | BUKRS | J_1BBRANCH |  | |
| `BUPLA` | BSEG | BUPLA | J_1BBRANCH |  | |
| `BUPLA` | BSEG | MANDT | J_1BBRANCH |  | |
| `BWKEY` | BSEG | MANDT | T001K |  | |
| `BWKEY` | BSEG | BWKEY | T001K |  | |
| `BWTAR` | BSEG | MANDT | T149D |  | |
| `BWTAR` | BSEG | BWTAR | T149D |  | |
| `CESSION_KZ` | BSEG | BUKRS | TCESSION |  | |
| `CESSION_KZ` | BSEG | CESSION_KZ | TCESSION |  | |
| `CESSION_KZ` | BSEG | MANDT | TCESSION |  | |
| `EBELN` | BSEG | MANDT | EKKO |  | |
| `EBELN` | BSEG | EBELN | EKKO |  | |
| `EBELP` | BSEG | EBELN | EKPO |  | |
| `EBELP` | BSEG | EBELP | EKPO |  | |
| `EBELP` | BSEG | MANDT | EKPO |  | |
| `EGBLD` | BSEG | MANDT | T005 |  | |
| `EGBLD` | BSEG | EGBLD | T005 |  | |
| `EGLLD` | BSEG | EGLLD | T005 |  | |
| `EGLLD` | BSEG | MANDT | T005 |  | |
| `EGRUP` | BSEG | MANDT | T8JF |  | |
| `EGRUP` | BSEG | BUKRS | T8JF |  | |
| `EGRUP` | BSEG | VNAME | T8JF |  | |
| `EGRUP` | BSEG | EGRUP | T8JF |  | |
| `ERFME` | BSEG | MANDT | T006 |  | |
| `ERFME` | BSEG | ERFME | T006 |  | |
| `ETEN2` | BSEG | MANDT | VBEP |  | |
| `ETEN2` | BSEG | VBEL2 | VBEP |  | |
| `ETEN2` | BSEG | POSN2 | VBEP |  | |
| `ETEN2` | BSEG | ETEN2 | VBEP |  | |
| `ETYPE` | BSEG | ETYPE | T8JE |  | |
| `ETYPE` | BSEG | MANDT | T8JE |  | |
| `ETYPE` | BKPF | BUKRS | T8JE |  | |
| `FDGRP` | BSEG | FDGRP | T035 |  | |
| `FDGRP` | BSEG | MANDT | T035 |  | |
| `FDLEV` | BSEG | MANDT | T036 |  | |
| `FDLEV` | BSEG | FDLEV | T036 |  | |
| `GITYP` | BSEG | MANDT | J_1ADTYP |  | |
| `GITYP` | BSEG | BUKRS | J_1ADTYP |  | |
| `GITYP` | BSEG | GITYP | J_1ADTYP |  | |
| `GRICD` | T001 | LAND1 | J_1AGICD |  | |
| `GRICD` | BSEG | GRICD | J_1AGICD |  | |
| `GRICD` | BSEG | MANDT | J_1AGICD |  | |
| `GRIRG` | BSEG | GRIRG | T005S |  | |
| `GRIRG` | BSEG | MANDT | T005S |  | |
| `GRIRG` | T001 | LAND1 | T005S |  | |
| `GSBER` | BSEG | MANDT | TGSB |  | |
| `GSBER` | BSEG | GSBER | TGSB |  | |
| `HBKID` | T042 | ZBUKR | T012 |  | |
| `HBKID` | BSEG | HBKID | T012 |  | |
| `HBKID` | BSEG | MANDT | T012 |  | |
| `HKONT` | BSEG | HKONT | SKB1 |  | |
| `HKONT` | BSEG | MANDT | SKB1 |  | |
| `HKONT` | BSEG | BUKRS | SKB1 |  | |
| `HKTID` | BSEG | HKTID | T012K |  | |
| `HKTID` | BSEG | MANDT | T012K |  | |
| `HKTID` | T042 | ZBUKR | T012K |  | |
| `HKTID` | BSEG | HBKID | T012K |  | |
| `IDXSP` | BSEG | MANDT | J_1AINFT20 |  | |
| `IDXSP` | BSEG | IDXSP | J_1AINFT20 |  | |
| `KBLNR` | BSEG | MANDT | KBLK |  | |
| `KBLNR` | BSEG | KBLNR | KBLK |  | |
| `KBLPOS` | BSEG | KBLNR | KBLP |  | |
| `KBLPOS` | BSEG | KBLPOS | KBLP |  | |
| `KBLPOS` | BSEG | MANDT | KBLP |  | |
| `KKBER` | BSEG | MANDT | T014 |  | |
| `KKBER` | BSEG | KKBER | T014 |  | |
| `KOKRS` | BSEG | KOKRS | TKA01 |  | |
| `KOKRS` | BSEG | MANDT | TKA01 |  | |
| `KUNNR` | BSEG | MANDT | KNA1 |  | |
| `KUNNR` | BSEG | KUNNR | KNA1 |  | |
| `LANDL` | BSEG | MANDT | T005 |  | |
| `LANDL` | BSEG | LANDL | T005 |  | |
| `LIFNR` | BSEG | MANDT | LFA1 |  | |
| `LIFNR` | BSEG | LIFNR | LFA1 |  | |
| `LZBKZ` | BSEG | MANDT | T015L |  | |
| `LZBKZ` | BSEG | LZBKZ | T015L |  | |
| `MABER` | BSEG | MANDT | T047M |  | |
| `MABER` | BKPF | BUKRS | T047M |  | |
| `MABER` | BSEG | MABER | T047M |  | |
| `MANDT` | BSEG | MANDT | T000 |  | |
| `MANSP` | BSEG | MANDT | T040S |  | |
| `MANSP` | BSEG | MANSP | T040S |  | |
| `MATNR` | BSEG | MANDT | MARA |  | |
| `MATNR` | BSEG | MATNR | MARA |  | |
| `MEINS` | BSEG | MANDT | T006 |  | |
| `MEINS` | BSEG | MEINS | T006 |  | |
| `MSCHL` | BSEG | MANDT | T040 |  | |
| `MSCHL` | BSEG | MSCHL | T040 |  | |
| `MWSK1` | BSEG | MANDT | T007A |  | |
| `MWSK1` | T005 | KALSM | T007A |  | |
| `MWSK1` | BSEG | MWSK1 | T007A |  | |
| `MWSK2` | T005 | KALSM | T007A |  | |
| `MWSK2` | BSEG | MWSK2 | T007A |  | |
| `MWSK2` | BSEG | MANDT | T007A |  | |
| `MWSK3` | BSEG | MANDT | T007A |  | |
| `MWSK3` | T005 | KALSM | T007A |  | |
| `MWSK3` | BSEG | MWSK3 | T007A |  | |
| `MWSKZ` | T005 | KALSM | T007A |  | |
| `MWSKZ` | BSEG | MWSKZ | T007A |  | |
| `MWSKZ` | BSEG | MANDT | T007A |  | |
| `OIHANTYP` | BSEG | MANDT | OIH5 |  | |
| `OIHANTYP` | BSEG | OIHANTYP | OIH5 |  | |
| `OIHANTYPE` | BSEG | MANDT | OIH5 |  | |
| `OIHANTYPE` | BSEG | OIHANTYPE | OIH5 |  | |
| `OIINVCYC` | BSEG | MANDT | TOIA10 |  | |
| `OIINVCYC` | BSEG | OIINVCYC | TOIA10 |  | |
| `OITAXFROM` | BSEG | MANDT | OIH4 |  | |
| `OITAXFROM` | BSEG | OITAXFROM | OIH4 |  | |
| `OITAXGRP` | BSEG | OITAXGRP | OIH2 |  | |
| `OITAXGRP` | BSEG | MANDT | OIH2 |  | |
| `OITAXGRP2` | BSEG | MANDT | OIH2 |  | |
| `OITAXGRP2` | BSEG | OITAXGRP2 | OIH2 |  | |
| `OITAXTO` | BSEG | MANDT | OIH4 |  | |
| `OITAXTO` | BSEG | OITAXTO | OIH4 |  | |
| `OIUOMQT` | BSEG | OIUOMQT | T006 |  | |
| `OIUOMQT` | BSEG | MANDT | T006 |  | |
| `PARGB` | BSEG | MANDT | TGSB |  | |
| `PARGB` | BSEG | PARGB | TGSB |  | |
| `POSN2` | BSEG | POSN2 | VBUP |  | |
| `POSN2` | BSEG | MANDT | VBUP |  | |
| `POSN2` | BSEG | VBEL2 | VBUP |  | |
| `PPRCT` | BKPF | BUDAT | CEPC |  | |
| `PPRCT` | * |  | CEPC |  | |
| `PPRCT` | BSEG | MANDT | CEPC |  | |
| `PPRCT` | BSEG | PPRCT | CEPC |  | |
| `PSWSL` | BSEG | MANDT | TCURC |  | |
| `PSWSL` | BSEG | PSWSL | TCURC |  | |
| `PYCUR` | BSEG | PYCUR | TCURC |  | |
| `PYCUR` | BSEG | MANDT | TCURC |  | |
| `QSSKZ` | BSEG | MANDT | T059Q |  | |
| `QSSKZ` | T001 | LAND1 | T059Q |  | |
| `QSSKZ` | BSEG | QSSKZ | T059Q |  | |
| `RECID` | BSEG | MANDT | T8JJ |  | |
| `RECID` | BSEG | BUKRS | T8JJ |  | |
| `RECID` | BSEG | RECID | T8JJ |  | |
| `RSTGR` | BSEG | BUKRS | T053R |  | |
| `RSTGR` | BSEG | RSTGR | T053R |  | |
| `RSTGR` | BSEG | MANDT | T053R |  | |
| `SAKNR` | BSEG | MANDT | SKB1 |  | |
| `SAKNR` | BSEG | BUKRS | SKB1 |  | |
| `SAKNR` | BSEG | SAKNR | SKB1 |  | |
| `SECCO` | BSEG | MANDT | SECCODE |  | |
| `SECCO` | BSEG | BUKRS | SECCODE |  | |
| `SECCO` | BSEG | SECCO | SECCODE |  | |
| `TXJCD` | BSEG | TXJCD | TTXJ |  | |
| `TXJCD` | BSEG | MANDT | TTXJ |  | |
| `TXJCD` | T005 | KALSM | TTXJ |  | |
| `UMSKZ` | BSEG | MANDT | T074U |  | |
| `UMSKZ` | BSEG | KOART | T074U |  | |
| `UMSKZ` | BSEG | UMSKZ | T074U |  | |
| `UZAWE` | BSEG | MANDT | T042F |  | |
| `UZAWE` | BSEG | UZAWE | T042F |  | |
| `VBEL2` | BSEG | MANDT | VBUK |  | |
| `VBEL2` | BSEG | VBEL2 | VBUK |  | |
| `VBELN` | BSEG | MANDT | VBUK |  | |
| `VBELN` | BSEG | VBELN | VBUK |  | |
| `VBUND` | BSEG | VBUND | T880 |  | |
| `VBUND` | BSEG | MANDT | T880 |  | |
| `VNAME` | BSEG | MANDT | T8JV |  | |
| `VNAME` | BSEG | BUKRS | T8JV |  | |
| `VNAME` | BSEG | VNAME | T8JV |  | |
| `VPTNR` | BSEG | MANDT | KNA1 |  | |
| `VPTNR` | BSEG | VPTNR | KNA1 |  | |
| `WERKS` | BSEG | MANDT | T001W |  | |
| `WERKS` | BSEG | WERKS | T001W |  | |
| `ZLSCH` | T001 | LAND1 | T042Z |  | |
| `ZLSCH` | BSEG | ZLSCH | T042Z |  | |
| `ZLSCH` | BSEG | MANDT | T042Z |  | |
| `ZLSPR` | BSEG | MANDT | T008 |  | |
| `ZLSPR` | BSEG | ZLSPR | T008 |  | |
| `ZUMSK` | BSEG | ZUMSK | T074U |  | |
| `ZUMSK` | BSEG | MANDT | T074U |  | |
| `ZUMSK` | BSEG | KOART | T074U |  | |
| `ZZREGION` | BSEG | MANDT | ZREG |  | |
| `ZZREGION` | BSEG | ZZREGION | ZREG |  | |
| `ZZSTATE` | BSEG | MANDT | T005S |  | |
| `ZZSTATE` | BSEG | LANDL | T005S |  | |
| `ZZSTATE` | BSEG | ZZSTATE | T005S |  | |
| `ZZUSERFLD1` | BSEG | MANDT | ZFU1 |  | |
| `ZZUSERFLD1` | BSEG | ZZUSERFLD1 | ZFU1 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zbacbe034.txt`
- `zfchzuord_2.txt`
- `zggbs000.txt`
- `zisfi0029.txt`
- `zisfi0043.txt`
- `zisfi0083.txt`
- `zisfi0083_1.txt`
- `zisfi0083_1t.txt`
- `zisfi0083_2.txt`
- `zisfi0090.txt`
- `zisfi0238_bw.txt`
- `zissd00031.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_