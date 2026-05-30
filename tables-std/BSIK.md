# `BSIK`

**Description:** Accounting Document (Open) — open vendor doc
**Category:** Standard SAP Table
**References:** 5 SELECT statements across 2 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/bsik/) — validated 2026-05-30, schema v1.0
**Schema fields:** 173 fields | **Data types:** CHAR(96), CUKY(3), CURR(41), DATS(8), DEC(5), INT4(1), NUMC(19)

## Key Fields
`AUFNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BUDAT` | BUDAT | — | DATS | 8 | 0 | Posting Date in the Document |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `CPUDT` | CPUDT | — | DATS | 8 | 0 | Day On Which Accounting Document Was Entered |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `XBLNR` | XBLNR1 | — | CHAR | 16 | 0 | Reference Document Number |
| `BLART` | BLART | T003 | CHAR | 2 | 0 | Document Type |
| `MONAT` | MONAT | — | NUMC | 2 | 0 | Fiscal Period |
| `BSCHL` | BSCHL | TBSL | CHAR | 2 | 0 | Posting Key |
| `ZUMSK` | DZUMSK | — | CHAR | 1 | 0 | Target Special G/L Indicator |
| `SHKZG` | SHKZG | — | CHAR | 1 | 0 | Debit/Credit Indicator |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `MWSKZ` | MWSKZ | T007A | CHAR | 2 | 0 | Tax on sales/purchases code |
| `DMBTR` | DMBTR | — | CURR | 13 | 2 | Amount in Local Currency |
| `WRBTR` | WRBTR | — | CURR | 13 | 2 | Amount in document currency |
| `MWSTS` | MWSTS | — | CURR | 13 | 2 | Tax Amount in Local Currency |
| `WMWST` | WMWST | — | CURR | 13 | 2 | Tax amount in document currency |
| `BDIFF` | BDIFF | — | CURR | 13 | 2 | Valuation Difference |
| `BDIF2` | BDIF2 | — | CURR | 13 | 2 | Valuation Difference for the Second Local Currency |
| `SGTXT` | SGTXT | — | CHAR | 50 | 0 | Item Text |
| `PROJN` | PROJN | — | CHAR | 16 | 0 | Old: Project number : No longer used --&gt; PS_POSNR |
| `AUFNR` | AUFNR | AUFK | CHAR | 12 | 0 | Order Number |
| `ANLN1` | ANLN1 | — | CHAR | 12 | 0 | Main Asset Number |
| `ANLN2` | ANLN2 | — | CHAR | 4 | 0 | Asset Subnumber |
| `EBELN` | EBELN | — | CHAR | 10 | 0 | Purchasing Document Number |
| `EBELP` | EBELP | — | NUMC | 5 | 0 | Item Number of Purchasing Document |
| `SAKNR` | SAKNR | — | CHAR | 10 | 0 | G/L Account Number |
| `HKONT` | HKONT | — | CHAR | 10 | 0 | General Ledger Account |
| `FKONT` | FIPLS | — | NUMC | 3 | 0 | Financial Budget Item |
| `FILKD` | FILKD | — | CHAR | 10 | 0 | Account Number of the Branch |
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
| `ZLSCH` | DZLSCH | T042Z | CHAR | 1 | 0 | Payment Method |
| `ZLSPR` | DZLSPR | T008 | CHAR | 1 | 0 | Payment Block Key |
| `ZBFIX` | DZBFIX | — | CHAR | 1 | 0 | Fixed Payment Terms |
| `HBKID` | HBKID | T012 | CHAR | 5 | 0 | Short Key for a House Bank |
| `BVTYP` | BVTYP | — | CHAR | 4 | 0 | Partner Bank Type |
| `REBZG` | REBZG | — | CHAR | 10 | 0 | Number of the Invoice the Transaction Belongs to |
| `REBZJ` | REBZJ | — | NUMC | 4 | 0 | Fiscal Year of the Relevant Invoice (for Credit Memo) |
| `REBZZ` | REBZZ | — | NUMC | 3 | 0 | Line Item in the Relevant Invoice |
| `SAMNR` | SAMNR | — | NUMC | 8 | 0 | Invoice List Number |
| `ZOLLT` | DZOLLT | — | CHAR | 8 | 0 | Customs Tariff Number |
| `ZOLLD` | DZOLLD | — | DATS | 8 | 0 | Customs Date |
| `LZBKZ` | LZBKZ | T015L | CHAR | 3 | 0 | State Central Bank Indicator |
| `LANDL` | LANDL | T005 | CHAR | 3 | 0 | Supplying Country |
| `DIEKZ` | DIEKZ | — | CHAR | 1 | 0 | Service Indicator (Foreign Payment) |
| `MANSP` | MANSP | T040S | CHAR | 1 | 0 | Dunning block |
| `MSCHL` | MSCHL | T040 | CHAR | 1 | 0 | Dunning key |
| `MADAT` | MADAT | — | DATS | 8 | 0 | Last dunned on |
| `MANST` | MAHNS_D | — | NUMC | 1 | 0 | Dunning level |
| `MABER` | MABER | — | CHAR | 2 | 0 | Dunning Area |
| `XNETB` | XNETB | — | CHAR | 1 | 0 | Indicator: Document posted net ? |
| `XANET` | XANET | — | CHAR | 1 | 0 | Indicator: Down payment in net procedure ? |
| `XCPDD` | XCPDD | — | CHAR | 1 | 0 | Indicator: Address and bank data set individually |
| `XESRD` | XESRD | — | CHAR | 1 | 0 | Indicator: Is any ISR data set in the document ? |
| `XZAHL` | XZAHL | — | CHAR | 1 | 0 | Indicator: Is the posting key used in a payment transaction? |
| `MWSK1` | MWSKX | — | CHAR | 2 | 0 | Tax Code for Distribution |
| `DMBT1` | DMBTX | — | CURR | 13 | 2 | Amount in Local Currency for Tax Distribution |
| `WRBT1` | WRBTX | — | CURR | 13 | 2 | Amount in foreign currency for tax breakdown |
| `MWSK2` | MWSKX | — | CHAR | 2 | 0 | Tax Code for Distribution |
| `DMBT2` | DMBTX | — | CURR | 13 | 2 | Amount in Local Currency for Tax Distribution |
| `WRBT2` | WRBTX | — | CURR | 13 | 2 | Amount in foreign currency for tax breakdown |
| `MWSK3` | MWSKX | — | CHAR | 2 | 0 | Tax Code for Distribution |
| `DMBT3` | DMBTX | — | CURR | 13 | 2 | Amount in Local Currency for Tax Distribution |
| `WRBT3` | WRBTX | — | CURR | 13 | 2 | Amount in foreign currency for tax breakdown |
| `QSSKZ` | QSSKZ | T059Q | CHAR | 2 | 0 | Withholding Tax Code |
| `QSSHB` | QSSHB | — | CURR | 13 | 2 | Withholding Tax Base Amount |
| `QBSHB` | QBSHB | — | CURR | 13 | 2 | Withholding Tax Amount (in Document Currency) |
| `BSTAT` | BSTAT_D | — | CHAR | 1 | 0 | Document Status |
| `ANFBN` | ANFBN | — | CHAR | 10 | 0 | Document Number of the Bill of Exchange Payment Request |
| `ANFBJ` | ANFBJ | — | NUMC | 4 | 0 | Fiscal Year of the Bill of Exchange Payment Request Document |
| `ANFBU` | ANFBU | T001 | CHAR | 4 | 0 | Company Code in Which Bill of Exch.Payment Request Is Posted |
| `VBUND` | RASSC | T880 | CHAR | 6 | 0 | Company ID of trading partner |
| `REBZT` | REBZT | — | CHAR | 1 | 0 | Follow-On Document Type |
| `STCEG` | STCEG | — | CHAR | 20 | 0 | VAT Registration Number |
| `EGBLD` | EGBLD | T005 | CHAR | 3 | 0 | Country of Destination for Delivery of Goods |
| `EGLLD` | EGLLD | T005 | CHAR | 3 | 0 | Supplying Country for Delivery of Goods |
| `QSZNR` | QSZNR | — | CHAR | 10 | 0 | Certificate Number of the Withholding Tax Exemption |
| `QSFBT` | QSFBT | — | CURR | 13 | 2 | Withholding Tax-Exempt Amount (in Document Currency) |
| `XINVE` | XINVE | — | CHAR | 1 | 0 | Indicator: Capital Goods Affected? |
| `PROJK` | PS_PSP_PNR | — | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `FIPOS` | FIPOS | — | CHAR | 14 | 0 | Commitment Item |
| `NPLNR` | NPLNR | — | CHAR | 12 | 0 | Network Number for Account Assignment |
| `AUFPL` | CO_AUFPL | — | NUMC | 10 | 0 | Routing number of operations in the order |
| `APLZL` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `XEGDR` | XEGDR | — | CHAR | 1 | 0 | Indicator: Triangular deal within the EU ? |
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
| `SKNT2` | SKNT2 | — | CURR | 13 | 2 | Cash Discount Amount in Second Local Currency |
| `SKNT3` | SKNT3 | — | CURR | 13 | 2 | Cash Discount Amount in Third Local Currency |
| `BDIF3` | BDIF3 | — | CURR | 13 | 2 | Valuation Difference for the Third Local Currency |
| `XRAGL` | XRAGL | — | CHAR | 1 | 0 | Indicator: Clearing was Reversed |
| `RSTGR` | RSTGR | T053R | CHAR | 3 | 0 | Reason Code for Payments |
| `UZAWE` | UZAWE | T042F | CHAR | 2 | 0 | Payment Method Supplement |
| `KOSTL` | KOSTL | — | CHAR | 10 | 0 | Cost Center |
| `LNRAN` | LNRAN | ANEK | NUMC | 5 | 0 | Sequence number of asset line items in fiscal year |
| `XSTOV` | XSTOV | — | CHAR | 1 | 0 | Indicator: Document is flagged for reversal |
| `KZBTR` | KZBTR_FI | — | CURR | 13 | 2 | Original Reduction Amount in Local Currency |
| `XREF1` | XREF1 | — | CHAR | 12 | 0 | Business partner reference key |
| `XREF2` | XREF2 | — | CHAR | 12 | 0 | Business partner reference key |
| `XARCH` | XARCH | — | CHAR | 1 | 0 | Indicator: Document already archived ? |
| `PSWSL` | PSWSL | TCURC | CUKY | 5 | 0 | Update Currency for General Ledger Transaction Figures |
| `PSWBT` | PSWBT | — | CURR | 13 | 2 | Amount for Updating in General Ledger |
| `IMKEY` | IMKEY | — | CHAR | 8 | 0 | Internal Key for Real Estate Object |
| `ZEKKN` | DZEKKN | — | NUMC | 2 | 0 | Sequential Number of Account Assignment |
| `FISTL` | FISTL | — | CHAR | 16 | 0 | Funds Center |
| `GEBER` | BP_GEBER | — | CHAR | 10 | 0 | Fund |
| `DABRZ` | DABRBEZ | — | DATS | 8 | 0 | Reference Date for Settlement |
| `XNEGP` | XNEGP | — | CHAR | 1 | 0 | Indicator: Negative posting |
| `EMPFB` | EMPFB | — | CHAR | 10 | 0 | Payee/Payer |
| `PRCTR` | PRCTR | — | CHAR | 10 | 0 | Profit Center |
| `XREF3` | XREF3 | — | CHAR | 20 | 0 | Reference key for line item |
| `DTWS1` | DTAT16 | — | NUMC | 2 | 0 | Instruction key 1 |
| `DTWS2` | DTAT17 | — | NUMC | 2 | 0 | Instruction key 2 |
| `DTWS3` | DTAT18 | — | NUMC | 2 | 0 | Instruction key 3 |
| `DTWS4` | DTAT19 | — | NUMC | 2 | 0 | Instruction key 4 |
| `XPYPR` | XPYPR | — | CHAR | 1 | 0 | Indicator: Items from Payment Program Blocked |
| `KIDNO` | KIDNO | — | CHAR | 30 | 0 | Payment Reference |
| `PYCUR` | PYCUR | TCURC | CUKY | 5 | 0 | Currency for Automatic Payment |
| `PYAMT` | PYAMT | — | CURR | 13 | 2 | Amount in Payment Currency |
| `BUPLA` | BUPLA | J_1BBRANCH | CHAR | 4 | 0 | Business Place |
| `SECCO` | SECCO | SECCODE | CHAR | 4 | 0 | Section Code |
| `PPDIFF` | PPDIFF | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 1.Loc.Curr.(Part Payments) |
| `PPDIF2` | PPDIF2 | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 2.Loc. Curr.(Part Payments) |
| `PPDIF3` | PPDIF3 | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 3.Loc.Curr.(Part Payments) |
| `PENLC1` | PENALTY1 | — | CURR | 13 | 2 | Penalty charge amount in first local currency |
| `PENLC2` | PENALTY2 | — | CURR | 13 | 2 | Penalty charge amount in second local currency |
| `PENLC3` | PENALTY3 | — | CURR | 13 | 2 | Penalty Charge Amount in Third Local Currency |
| `PENFC` | PENALTY | — | CURR | 13 | 2 | Penalty charge amount in document currency |
| `PENDAYS` | PDAYS | — | INT4 | 10 | 0 | Number of days for penalty charge calculation |
| `PENRC` | PENRC | — | CHAR | 2 | 0 | Reason for late payment |
| `VERTT` | RANTYP | — | CHAR | 1 | 0 | Contract Type |
| `VERTN` | RANL | — | CHAR | 13 | 0 | Contract Number |
| `VBEWA` | SBEWART | — | CHAR | 4 | 0 | Flow Type |
| `KBLNR` | KBLNR_FI | — | CHAR | 10 | 0 | Document Number for Earmarked Funds |
| `KBLPOS` | KBLPOS | — | NUMC | 3 | 0 | Earmarked Funds: Document Item |
| `GRANT_NBR` | GM_GRANT_NBR | — | CHAR | 20 | 0 | Grant |
| `GMVKZ` | FM_GMVKZ | — | CHAR | 1 | 0 | Item is in Execution |
| `SRTYPE` | FM_SRTYPE | — | CHAR | 2 | 0 | Type of Additional Receivable |
| `LOTKZ` | PSO_LOTKZ | — | CHAR | 10 | 0 | Lot Number for Requests |
| `ZINKZ` | DZINKZ | — | CHAR | 2 | 0 | Exempted from interest calculation |
| `FKBER` | FKBER | — | CHAR | 16 | 0 | Functional Area |
| `INTRENO` | VVINTRENO | — | CHAR | 13 | 0 | Internal Real Estate Master Data Code |
| `PPRCT` | PPRCTR | — | CHAR | 10 | 0 | Partner Profit Center |
| `BUZID` | BUZID | — | CHAR | 1 | 0 | Identification of the Line Item |
| `AUGGJ` | AUGGJ | — | NUMC | 4 | 0 | Fiscal Year of Clearing Document |
| `HKTID` | HKTID | — | CHAR | 5 | 0 | ID for account details |
| `BUDGET_PD` | FM_BUDGET_PERIOD | — | CHAR | 10 | 0 | FM: Budget Period |
| `KONTT` | KONTT_FI | — | CHAR | 2 | 0 | Account Assignment Category for Industry Solution |
| `KONTL` | KONTL_FI | — | CHAR | 50 | 0 | Acct assignment string for industry-specific acct assignmnts |
| `UEBGDAT` | UEBGDAT | — | DATS | 8 | 0 | Transfer date of an item to legal dunning proceeding |
| `VNAME` | JV_NAME | T8JV | CHAR | 6 | 0 | Joint Venture |
| `EGRUP` | JV_EGROUP | T8JF | CHAR | 3 | 0 | Equity group |
| `BTYPE` | JV_BILIND | T8JA | CHAR | 2 | 0 | Payroll Type |
| `OIEXGNUM` | OIA_EXGNUM | — | CHAR | 10 | 0 | Exchange agreement number |
| `OINETCYC` | OIA_NETCYC | — | CHAR | 1 | 0 | Netting cycle (FI blocking indicator) |
| `OIEXGTYP` | OIA_EXGTYP | — | CHAR | 4 | 0 | Exchange type |
| `PROPMANO` | REHORECNNRM | — | CHAR | 13 | 0 | Mandate, Mandate-Opening Contract |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ANFBU` | BSIK | MANDT | T001 |  | |
| `ANFBU` | BSIK | ANFBU | T001 |  | |
| `AUFNR` | BSIK | MANDT | AUFK |  | |
| `AUFNR` | BSIK | AUFNR | AUFK |  | |
| `BLART` | BSIK | BLART | T003 |  | |
| `BLART` | BSIK | MANDT | T003 |  | |
| `BSCHL` | BSIK | MANDT | TBSL |  | |
| `BSCHL` | BSIK | BSCHL | TBSL |  | |
| `BTYPE` | BSIK | MANDT | T8JA |  | |
| `BTYPE` | BSIK | BTYPE | T8JA |  | |
| `BUKRS` | BSIK | MANDT | LFB1 |  | |
| `BUKRS` | BSIK | LIFNR | LFB1 |  | |
| `BUKRS` | BSIK | BUKRS | LFB1 |  | |
| `BUPLA` | BSIK | MANDT | J_1BBRANCH |  | |
| `BUPLA` | * |  | J_1BBRANCH |  | |
| `BUPLA` | BSIK | BUPLA | J_1BBRANCH |  | |
| `EGBLD` | BSIK | MANDT | T005 |  | |
| `EGBLD` | BSIK | EGBLD | T005 |  | |
| `EGLLD` | BSIK | MANDT | T005 |  | |
| `EGLLD` | BSIK | EGLLD | T005 |  | |
| `EGRUP` | BSIK | EGRUP | T8JF |  | |
| `EGRUP` | BSIK | MANDT | T8JF |  | |
| `EGRUP` | BSIK | BUKRS | T8JF |  | |
| `EGRUP` | BSIK | VNAME | T8JF |  | |
| `GSBER` | BSIK | MANDT | TGSB |  | |
| `GSBER` | BSIK | GSBER | TGSB |  | |
| `HBKID` | BSIK | MANDT | T012 |  | |
| `HBKID` | * |  | T012 |  | |
| `HBKID` | BSIK | HBKID | T012 |  | |
| `LANDL` | BSIK | MANDT | T005 |  | |
| `LANDL` | BSIK | LANDL | T005 |  | |
| `LIFNR` | BSIK | MANDT | LFA1 |  | |
| `LIFNR` | BSIK | LIFNR | LFA1 |  | |
| `LNRAN` | BSIK | MANDT | ANEK |  | |
| `LNRAN` | BSIK | BUKRS | ANEK |  | |
| `LNRAN` | BSIK | ANLN1 | ANEK |  | |
| `LNRAN` | BSIK | ANLN2 | ANEK |  | |
| `LNRAN` | BSIK | ANFBJ | ANEK |  | |
| `LNRAN` | BSIK | LNRAN | ANEK |  | |
| `LZBKZ` | BSIK | LZBKZ | T015L |  | |
| `LZBKZ` | BSIK | MANDT | T015L |  | |
| `MANSP` | BSIK | MANDT | T040S |  | |
| `MANSP` | BSIK | MANSP | T040S |  | |
| `MSCHL` | BSIK | MANDT | T040 |  | |
| `MSCHL` | BSIK | MSCHL | T040 |  | |
| `MWSKZ` | BSIK | MANDT | T007A |  | |
| `MWSKZ` | * |  | T007A |  | |
| `MWSKZ` | BSIK | MWSKZ | T007A |  | |
| `PSWSL` | BSIK | MANDT | TCURC |  | |
| `PSWSL` | BSIK | PSWSL | TCURC |  | |
| `PYCUR` | BSIK | MANDT | TCURC |  | |
| `PYCUR` | BSIK | PYCUR | TCURC |  | |
| `QSSKZ` | BSIK | MANDT | T059Q |  | |
| `QSSKZ` | * |  | T059Q |  | |
| `QSSKZ` | BSIK | QSSKZ | T059Q |  | |
| `RSTGR` | BSIK | MANDT | T053R |  | |
| `RSTGR` | * |  | T053R |  | |
| `RSTGR` | BSIK | RSTGR | T053R |  | |
| `SECCO` | BSIK | MANDT | SECCODE |  | |
| `SECCO` | * |  | SECCODE |  | |
| `SECCO` | BSIK | SECCO | SECCODE |  | |
| `UMSKZ` | BSIK | MANDT | T074U |  | |
| `UMSKZ` | * |  | T074U |  | |
| `UMSKZ` | BSIK | UMSKZ | T074U |  | |
| `UZAWE` | BSIK | MANDT | T042F |  | |
| `UZAWE` | BSIK | UZAWE | T042F |  | |
| `VBUND` | BSIK | MANDT | T880 |  | |
| `VBUND` | BSIK | VBUND | T880 |  | |
| `VNAME` | BSIK | MANDT | T8JV |  | |
| `VNAME` | BSIK | BUKRS | T8JV |  | |
| `VNAME` | BSIK | VNAME | T8JV |  | |
| `WAERS` | BSIK | WAERS | TCURC |  | |
| `WAERS` | BSIK | MANDT | TCURC |  | |
| `ZLSCH` | BSIK | MANDT | T042Z |  | |
| `ZLSCH` | * |  | T042Z |  | |
| `ZLSCH` | BSIK | ZLSCH | T042Z |  | |
| `ZLSPR` | BSIK | MANDT | T008 |  | |
| `ZLSPR` | BSIK | ZLSPR | T008 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `LIFNR`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zbacbe034.txt`
- `zfchzuord_2.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_