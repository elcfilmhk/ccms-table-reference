# `BSID`

**Description:** Accounting Document (Open) — open customer doc
**Category:** Standard SAP Table
**References:** 3 SELECT statements across 1 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/bsid/) — validated 2026-05-30, schema v1.0
**Schema fields:** 171 fields | **Data types:** CHAR(101), CUKY(3), CURR(34), DATS(8), DEC(5), NUMC(20)

## Key Fields
`AUFNR` | `VBELN`

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
| `ANFBN` | ANFBN | — | CHAR | 10 | 0 | Document Number of the Bill of Exchange Payment Request |
| `ANFBJ` | ANFBJ | — | NUMC | 4 | 0 | Fiscal Year of the Bill of Exchange Payment Request Document |
| `ANFBU` | ANFBU | T001 | CHAR | 4 | 0 | Company Code in Which Bill of Exch.Payment Request Is Posted |
| `ANFAE` | ANFAE | — | DATS | 8 | 0 | Bill of Exchange Payment Request Due Date |
| `MANSP` | MANSP | T040S | CHAR | 1 | 0 | Dunning block |
| `MSCHL` | MSCHL | T040 | CHAR | 1 | 0 | Dunning key |
| `MADAT` | MADAT | — | DATS | 8 | 0 | Last dunned on |
| `MANST` | MAHNS_D | — | NUMC | 1 | 0 | Dunning level |
| `MABER` | MABER | — | CHAR | 2 | 0 | Dunning Area |
| `XNETB` | XNETB | — | CHAR | 1 | 0 | Indicator: Document posted net ? |
| `XANET` | XANET | — | CHAR | 1 | 0 | Indicator: Down payment in net procedure ? |
| `XCPDD` | XCPDD | — | CHAR | 1 | 0 | Indicator: Address and bank data set individually |
| `XINVE` | XINVE | — | CHAR | 1 | 0 | Indicator: Capital Goods Affected? |
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
| `BSTAT` | BSTAT_D | — | CHAR | 1 | 0 | Document Status |
| `VBUND` | RASSC | T880 | CHAR | 6 | 0 | Company ID of trading partner |
| `VBELN` | VBELN_VF | — | CHAR | 10 | 0 | Billing Document |
| `REBZT` | REBZT | — | CHAR | 1 | 0 | Follow-On Document Type |
| `INFAE` | INFAE | — | CHAR | 8 | 0 | Inverted Date for Net Due Date |
| `STCEG` | STCEG | — | CHAR | 20 | 0 | VAT Registration Number |
| `EGBLD` | EGBLD | T005 | CHAR | 3 | 0 | Country of Destination for Delivery of Goods |
| `EGLLD` | EGLLD | T005 | CHAR | 3 | 0 | Supplying Country for Delivery of Goods |
| `RSTGR` | RSTGR | T053R | CHAR | 3 | 0 | Reason Code for Payments |
| `XNOZA` | XNOZA | — | CHAR | 1 | 0 | Indicator: Account is not counted |
| `VERTT` | RANTYP | — | CHAR | 1 | 0 | Contract Type |
| `VERTN` | RANL | — | CHAR | 13 | 0 | Contract Number |
| `VBEWA` | SBEWART | — | CHAR | 4 | 0 | Flow Type |
| `WVERW` | WVERW | — | CHAR | 1 | 0 | Bill of exchange usage type |
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
| `BDIF3` | BDIF3 | — | CURR | 13 | 2 | Valuation Difference for the Third Local Currency |
| `XRAGL` | XRAGL | — | CHAR | 1 | 0 | Indicator: Clearing was Reversed |
| `UZAWE` | UZAWE | T042F | CHAR | 2 | 0 | Payment Method Supplement |
| `XSTOV` | XSTOV | — | CHAR | 1 | 0 | Indicator: Document is flagged for reversal |
| `MWST2` | MWST2 | — | CURR | 13 | 2 | Tax Amount in Second Local Currency |
| `MWST3` | MWST3 | — | CURR | 13 | 2 | Tax Amount in Third Local Currency |
| `SKNT2` | SKNT2 | — | CURR | 13 | 2 | Cash Discount Amount in Second Local Currency |
| `SKNT3` | SKNT3 | — | CURR | 13 | 2 | Cash Discount Amount in Third Local Currency |
| `XREF1` | XREF1 | — | CHAR | 12 | 0 | Business partner reference key |
| `XREF2` | XREF2 | — | CHAR | 12 | 0 | Business partner reference key |
| `XARCH` | XARCH | — | CHAR | 1 | 0 | Indicator: Document already archived ? |
| `PSWSL` | PSWSL | TCURC | CUKY | 5 | 0 | Update Currency for General Ledger Transaction Figures |
| `PSWBT` | PSWBT | — | CURR | 13 | 2 | Amount for Updating in General Ledger |
| `LZBKZ` | LZBKZ | T015L | CHAR | 3 | 0 | State Central Bank Indicator |
| `LANDL` | LANDL | T005 | CHAR | 3 | 0 | Supplying Country |
| `IMKEY` | IMKEY | — | CHAR | 8 | 0 | Internal Key for Real Estate Object |
| `VBEL2` | VBELN_VA | — | CHAR | 10 | 0 | Sales Document |
| `VPOS2` | NUM06 | — | NUMC | 6 | 0 | Numeric field: Length 6 |
| `POSN2` | POSNR_VA | — | NUMC | 6 | 0 | Sales Document Item |
| `ETEN2` | ETENR | — | NUMC | 4 | 0 | Delivery Schedule Line Number |
| `FISTL` | FISTL | — | CHAR | 16 | 0 | Funds Center |
| `GEBER` | BP_GEBER | — | CHAR | 10 | 0 | Fund |
| `DABRZ` | DABRBEZ | — | DATS | 8 | 0 | Reference Date for Settlement |
| `XNEGP` | XNEGP | — | CHAR | 1 | 0 | Indicator: Negative posting |
| `KOSTL` | KOSTL | — | CHAR | 10 | 0 | Cost Center |
| `RFZEI` | RFZEI_CC | — | NUMC | 3 | 0 | Payment Card Item |
| `KKBER` | KKBER | T014 | CHAR | 4 | 0 | Credit control area |
| `EMPFB` | EMPFB | — | CHAR | 10 | 0 | Payee/Payer |
| `PRCTR` | PRCTR | — | CHAR | 10 | 0 | Profit Center |
| `XREF3` | XREF3 | — | CHAR | 20 | 0 | Reference key for line item |
| `QSSKZ` | QSSKZ | T059Q | CHAR | 2 | 0 | Withholding Tax Code |
| `ZINKZ` | DZINKZ | — | CHAR | 2 | 0 | Exempted from interest calculation |
| `DTWS1` | DTAT16 | — | NUMC | 2 | 0 | Instruction key 1 |
| `DTWS2` | DTAT17 | — | NUMC | 2 | 0 | Instruction key 2 |
| `DTWS3` | DTAT18 | — | NUMC | 2 | 0 | Instruction key 3 |
| `DTWS4` | DTAT19 | — | NUMC | 2 | 0 | Instruction key 4 |
| `XPYPR` | XPYPR | — | CHAR | 1 | 0 | Indicator: Items from Payment Program Blocked |
| `KIDNO` | KIDNO | — | CHAR | 30 | 0 | Payment Reference |
| `ABSBT` | ABSBT | — | CURR | 13 | 2 | Credit management: Hedged amount |
| `CCBTC` | CCBTC | — | CHAR | 10 | 0 | Payment cards: Settlement run |
| `PYCUR` | PYCUR | TCURC | CUKY | 5 | 0 | Currency for Automatic Payment |
| `PYAMT` | PYAMT | — | CURR | 13 | 2 | Amount in Payment Currency |
| `BUPLA` | BUPLA | J_1BBRANCH | CHAR | 4 | 0 | Business Place |
| `SECCO` | SECCO | SECCODE | CHAR | 4 | 0 | Section Code |
| `CESSION_KZ` | CESSION_KZ | TCESSION | CHAR | 2 | 0 | Accounts Receivable Pledging Indicator |
| `PPDIFF` | PPDIFF | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 1.Loc.Curr.(Part Payments) |
| `PPDIF2` | PPDIF2 | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 2.Loc. Curr.(Part Payments) |
| `PPDIF3` | PPDIF3 | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 3.Loc.Curr.(Part Payments) |
| `KBLNR` | KBLNR_FI | — | CHAR | 10 | 0 | Document Number for Earmarked Funds |
| `KBLPOS` | KBLPOS | — | NUMC | 3 | 0 | Earmarked Funds: Document Item |
| `GRANT_NBR` | GM_GRANT_NBR | — | CHAR | 20 | 0 | Grant |
| `GMVKZ` | FM_GMVKZ | — | CHAR | 1 | 0 | Item is in Execution |
| `SRTYPE` | FM_SRTYPE | — | CHAR | 2 | 0 | Type of Additional Receivable |
| `LOTKZ` | PSO_LOTKZ | — | CHAR | 10 | 0 | Lot Number for Requests |
| `FKBER` | FKBER | — | CHAR | 16 | 0 | Functional Area |
| `INTRENO` | VVINTRENO | — | CHAR | 13 | 0 | Internal Real Estate Master Data Code |
| `PPRCT` | PPRCTR | — | CHAR | 10 | 0 | Partner Profit Center |
| `BUZID` | BUZID | — | CHAR | 1 | 0 | Identification of the Line Item |
| `AUGGJ` | AUGGJ | — | NUMC | 4 | 0 | Fiscal Year of Clearing Document |
| `HKTID` | HKTID | — | CHAR | 5 | 0 | ID for account details |
| `BUDGET_PD` | FM_BUDGET_PERIOD | — | CHAR | 10 | 0 | FM: Budget Period |
| `PAYS_PROV` | COM_WEC_PAYMENT_SRV_PROVIDER | — | CHAR | 4 | 0 | Payment Service Provider |
| `PAYS_TRAN` | FPS_TRANSACTION | — | CHAR | 35 | 0 | Payment Reference of Payment Service Provider |
| `MNDID` | SEPA_MNDID | — | CHAR | 35 | 0 | Unique Referene to Mandate per Payment Recipient |
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
| `ANFBU` | BSID | MANDT | T001 |  | |
| `ANFBU` | BSID | ANFBU | T001 |  | |
| `AUFNR` | BSID | MANDT | AUFK |  | |
| `AUFNR` | BSID | AUFNR | AUFK |  | |
| `BLART` | BSID | BLART | T003 |  | |
| `BLART` | BSID | MANDT | T003 |  | |
| `BSCHL` | BSID | MANDT | TBSL |  | |
| `BSCHL` | BSID | BSCHL | TBSL |  | |
| `BTYPE` | BSID | MANDT | T8JA |  | |
| `BTYPE` | BSID | BTYPE | T8JA |  | |
| `BUKRS` | BSID | MANDT | KNB1 |  | |
| `BUKRS` | BSID | KUNNR | KNB1 |  | |
| `BUKRS` | BSID | BUKRS | KNB1 |  | |
| `BUPLA` | BSID | MANDT | J_1BBRANCH |  | |
| `BUPLA` | * |  | J_1BBRANCH |  | |
| `BUPLA` | BSID | BUPLA | J_1BBRANCH |  | |
| `CESSION_KZ` | BSID | MANDT | TCESSION |  | |
| `CESSION_KZ` | BSID | BUKRS | TCESSION |  | |
| `CESSION_KZ` | BSID | CESSION_KZ | TCESSION |  | |
| `EGBLD` | BSID | MANDT | T005 |  | |
| `EGBLD` | BSID | EGBLD | T005 |  | |
| `EGLLD` | BSID | MANDT | T005 |  | |
| `EGLLD` | BSID | EGLLD | T005 |  | |
| `EGRUP` | BSID | VNAME | T8JF |  | |
| `EGRUP` | BSID | EGRUP | T8JF |  | |
| `EGRUP` | BSID | MANDT | T8JF |  | |
| `EGRUP` | BSID | BUKRS | T8JF |  | |
| `GSBER` | BSID | MANDT | TGSB |  | |
| `GSBER` | BSID | GSBER | TGSB |  | |
| `HBKID` | BSID | MANDT | T012 |  | |
| `HBKID` | * |  | T012 |  | |
| `HBKID` | BSID | HBKID | T012 |  | |
| `KKBER` | BSID | KKBER | T014 |  | |
| `KKBER` | BSID | MANDT | T014 |  | |
| `KUNNR` | BSID | KUNNR | KNA1 |  | |
| `KUNNR` | BSID | MANDT | KNA1 |  | |
| `LANDL` | BSID | LANDL | T005 |  | |
| `LANDL` | BSID | MANDT | T005 |  | |
| `LZBKZ` | BSID | MANDT | T015L |  | |
| `LZBKZ` | BSID | LZBKZ | T015L |  | |
| `MANSP` | BSID | MANSP | T040S |  | |
| `MANSP` | BSID | MANDT | T040S |  | |
| `MSCHL` | BSID | MANDT | T040 |  | |
| `MSCHL` | BSID | MSCHL | T040 |  | |
| `MWSKZ` | BSID | MANDT | T007A |  | |
| `MWSKZ` | * |  | T007A |  | |
| `MWSKZ` | BSID | MWSKZ | T007A |  | |
| `PSWSL` | BSID | PSWSL | TCURC |  | |
| `PSWSL` | BSID | MANDT | TCURC |  | |
| `PYCUR` | BSID | MANDT | TCURC |  | |
| `PYCUR` | BSID | PYCUR | TCURC |  | |
| `QSSKZ` | * |  | T059Q |  | |
| `QSSKZ` | BSID | QSSKZ | T059Q |  | |
| `QSSKZ` | BSID | MANDT | T059Q |  | |
| `RSTGR` | BSID | MANDT | T053R |  | |
| `RSTGR` | * |  | T053R |  | |
| `RSTGR` | BSID | RSTGR | T053R |  | |
| `SECCO` | * |  | SECCODE |  | |
| `SECCO` | BSID | SECCO | SECCODE |  | |
| `SECCO` | BSID | MANDT | SECCODE |  | |
| `UMSKZ` | BSID | MANDT | T074U |  | |
| `UMSKZ` | * |  | T074U |  | |
| `UMSKZ` | BSID | UMSKZ | T074U |  | |
| `UZAWE` | BSID | MANDT | T042F |  | |
| `UZAWE` | BSID | UZAWE | T042F |  | |
| `VBUND` | BSID | VBUND | T880 |  | |
| `VBUND` | BSID | MANDT | T880 |  | |
| `VNAME` | BSID | MANDT | T8JV |  | |
| `VNAME` | BSID | BUKRS | T8JV |  | |
| `VNAME` | BSID | VNAME | T8JV |  | |
| `WAERS` | BSID | MANDT | TCURC |  | |
| `WAERS` | BSID | WAERS | TCURC |  | |
| `ZLSCH` | BSID | ZLSCH | T042Z |  | |
| `ZLSCH` | BSID | MANDT | T042Z |  | |
| `ZLSCH` | * |  | T042Z |  | |
| `ZLSPR` | BSID | ZLSPR | T008 |  | |
| `ZLSPR` | BSID | MANDT | T008 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zfchzuord_2.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_