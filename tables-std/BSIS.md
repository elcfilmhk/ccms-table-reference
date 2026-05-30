# `BSIS`

**Description:** Accounting Document (Open) — open G/L doc
**Category:** Standard SAP Table
**References:** 9 SELECT statements across 1 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/bsis/) — validated 2026-05-30, schema v1.0
**Schema fields:** 76 fields | **Data types:** ACCP(1), CHAR(47), CUKY(2), CURR(16), DATS(5), NUMC(5)

## Key Fields
`AUFNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BUDAT` | BUDAT | — | DATS | 8 | 0 | Posting Date in the Document |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `XBLNR` | XBLNR1 | — | CHAR | 16 | 0 | Reference Document Number |
| `BLART` | BLART | T003 | CHAR | 2 | 0 | Document Type |
| `MONAT` | MONAT | — | NUMC | 2 | 0 | Fiscal Period |
| `BSCHL` | BSCHL | TBSL | CHAR | 2 | 0 | Posting Key |
| `SHKZG` | SHKZG | — | CHAR | 1 | 0 | Debit/Credit Indicator |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `MWSKZ` | MWSKZ | T007A | CHAR | 2 | 0 | Tax on sales/purchases code |
| `FKONT` | FIPLS | — | NUMC | 3 | 0 | Financial Budget Item |
| `DMBTR` | DMBTR | — | CURR | 13 | 2 | Amount in Local Currency |
| `WRBTR` | WRBTR | — | CURR | 13 | 2 | Amount in document currency |
| `MWSTS` | MWSTS | — | CURR | 13 | 2 | Tax Amount in Local Currency |
| `WMWST` | WMWST | — | CURR | 13 | 2 | Tax amount in document currency |
| `SGTXT` | SGTXT | — | CHAR | 50 | 0 | Item Text |
| `PROJN` | PROJN | — | CHAR | 16 | 0 | Old: Project number : No longer used --&gt; PS_POSNR |
| `AUFNR` | AUFNR_NEU | AUFK | CHAR | 12 | 0 | Order Number |
| `WERKS` | WERKS_D | T001W | CHAR | 4 | 0 | Plant |
| `KOSTL` | KOSTL | — | CHAR | 10 | 0 | Cost Center |
| `ZFBDT` | DZFBDT | — | DATS | 8 | 0 | Baseline Date for Due Date Calculation |
| `XOPVW` | XOPVW | — | CHAR | 1 | 0 | Indicator: Open item management? |
| `VALUT` | VALUT | — | DATS | 8 | 0 | Value date |
| `BSTAT` | BSTAT_D | — | CHAR | 1 | 0 | Document Status |
| `BDIFF` | BDIFF | — | CURR | 13 | 2 | Valuation Difference |
| `BDIF2` | BDIF2 | — | CURR | 13 | 2 | Valuation Difference for the Second Local Currency |
| `VBUND` | RASSC | T880 | CHAR | 6 | 0 | Company ID of trading partner |
| `PSWSL` | PSWSL | TCURC | CUKY | 5 | 0 | Update Currency for General Ledger Transaction Figures |
| `WVERW` | WVERW | — | CHAR | 1 | 0 | Bill of exchange usage type |
| `DMBE2` | DMBE2 | — | CURR | 13 | 2 | Amount in Second Local Currency |
| `DMBE3` | DMBE3 | — | CURR | 13 | 2 | Amount in Third Local Currency |
| `MWST2` | MWST2 | — | CURR | 13 | 2 | Tax Amount in Second Local Currency |
| `MWST3` | MWST3 | — | CURR | 13 | 2 | Tax Amount in Third Local Currency |
| `BDIF3` | BDIF3 | — | CURR | 13 | 2 | Valuation Difference for the Third Local Currency |
| `RDIF3` | RDIF3 | — | CURR | 13 | 2 | Exchange Rate Difference Realized for Third Local Currency |
| `XRAGL` | XRAGL | — | CHAR | 1 | 0 | Indicator: Clearing was Reversed |
| `PROJK` | PS_PSP_PNR | PRPS | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `PRCTR` | PRCTR | — | CHAR | 10 | 0 | Profit Center |
| `XSTOV` | XSTOV | — | CHAR | 1 | 0 | Indicator: Document is flagged for reversal |
| `XARCH` | XARCH | — | CHAR | 1 | 0 | Indicator: Document already archived ? |
| `PSWBT` | PSWBT | — | CURR | 13 | 2 | Amount for Updating in General Ledger |
| `XNEGP` | XNEGP | — | CHAR | 1 | 0 | Indicator: Negative posting |
| `RFZEI` | RFZEI_CC | — | NUMC | 3 | 0 | Payment Card Item |
| `CCBTC` | CCBTC | — | CHAR | 10 | 0 | Payment cards: Settlement run |
| `XREF3` | XREF3 | — | CHAR | 20 | 0 | Reference key for line item |
| `BUPLA` | BUPLA | J_1BBRANCH | CHAR | 4 | 0 | Business Place |
| `PPDIFF` | PPDIFF | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 1.Loc.Curr.(Part Payments) |
| `PPDIF2` | PPDIF2 | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 2.Loc. Curr.(Part Payments) |
| `PPDIF3` | PPDIF3 | — | CURR | 13 | 2 | Realized Exchange Rate Gain/Loss 3.Loc.Curr.(Part Payments) |
| `BEWAR` | RMVCT | T856 | CHAR | 3 | 0 | Transaction Type |
| `IMKEY` | IMKEY | — | CHAR | 8 | 0 | Internal Key for Real Estate Object |
| `DABRZ` | DABRBEZ | — | DATS | 8 | 0 | Reference Date for Settlement |
| `INTRENO` | VVINTRENO | — | CHAR | 13 | 0 | Internal Real Estate Master Data Code |
| `GRANT_NBR` | GM_GRANT_NBR | — | CHAR | 20 | 0 | Grant |
| `FKBER` | FKBER | — | CHAR | 16 | 0 | Functional Area |
| `FIPOS` | FIPOS | — | CHAR | 14 | 0 | Commitment Item |
| `FISTL` | FISTL | — | CHAR | 16 | 0 | Funds Center |
| `GEBER` | BP_GEBER | — | CHAR | 10 | 0 | Fund |
| `PPRCT` | PPRCTR | — | CHAR | 10 | 0 | Partner Profit Center |
| `BUZID` | BUZID | — | CHAR | 1 | 0 | Identification of the Line Item |
| `AUGGJ` | AUGGJ | — | NUMC | 4 | 0 | Fiscal Year of Clearing Document |
| `UZAWE` | UZAWE | — | CHAR | 2 | 0 | Payment Method Supplement |
| `SEGMENT` | FB_SEGMENT | — | CHAR | 10 | 0 | Segment for Segmental Reporting |
| `PSEGMENT` | FB_PSEGMENT | — | CHAR | 10 | 0 | Partner Segment for Segmental Reporting |
| `PGEBER` | FM_PFUND | — | CHAR | 10 | 0 | Partner Fund |
| `PGRANT_NBR` | GM_GRANT_PARTNER | — | CHAR | 20 | 0 | Partner Grant |
| `MEASURE` | FM_MEASURE | — | CHAR | 24 | 0 | Funded Program |
| `BUDGET_PD` | FM_BUDGET_PERIOD | — | CHAR | 10 | 0 | FM: Budget Period |
| `PBUDGET_PD` | FM_PBUDGET_PERIOD | — | CHAR | 10 | 0 | FM: Partner Budget Period |
| `FIPEX` | FM_FIPEX_DONT_USE | — | CHAR | 24 | 0 | Commitment item - Do not use field - see note 447805 |
| `PRODPER` | JVA_PROD_MONTH | — | ACCP | 6 | 0 | PRODPER |
| `QSSKZ` | QSSKZ | — | CHAR | 2 | 0 | Withholding Tax Code |
| `OIEXGNUM` | OIA_EXGNUM | — | CHAR | 10 | 0 | Exchange agreement number |
| `OIEXGTYP` | OIA_EXGTYP | — | CHAR | 4 | 0 | Exchange type |
| `OINEGPSTG` | OIA_NGPSTL | — | CHAR | 1 | 0 | Negative posting line (exchange fees) |
| `PROPMANO` | REHORECNNRM | — | CHAR | 13 | 0 | Mandate, Mandate-Opening Contract |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `AUFNR` | BSIS | MANDT | AUFK |  | |
| `AUFNR` | BSIS | AUFNR | AUFK |  | |
| `BEWAR` | BSIS | MANDT | T856 |  | |
| `BEWAR` | BSIS | BEWAR | T856 |  | |
| `BLART` | BSIS | MANDT | T003 |  | |
| `BLART` | BSIS | BLART | T003 |  | |
| `BSCHL` | BSIS | MANDT | TBSL |  | |
| `BSCHL` | BSIS | BSCHL | TBSL |  | |
| `BUPLA` | BSIS | MANDT | J_1BBRANCH |  | |
| `BUPLA` | * |  | J_1BBRANCH |  | |
| `BUPLA` | BSIS | BUPLA | J_1BBRANCH |  | |
| `GSBER` | SYST | MANDT | TGSB |  | |
| `GSBER` | BSIS | GSBER | TGSB |  | |
| `MWSKZ` | BSIS | MANDT | T007A |  | |
| `MWSKZ` | * |  | T007A |  | |
| `MWSKZ` | BSIS | MWSKZ | T007A |  | |
| `PROJK` | BSIS | PROJK | PRPS |  | |
| `PROJK` | BSIS | MANDT | PRPS |  | |
| `PSWSL` | BSIS | MANDT | TCURC |  | |
| `PSWSL` | BSIS | PSWSL | TCURC |  | |
| `VBUND` | BSIS | MANDT | T880 |  | |
| `VBUND` | BSIS | VBUND | T880 |  | |
| `WAERS` | BSIS | MANDT | TCURC |  | |
| `WAERS` | BSIS | WAERS | TCURC |  | |
| `WERKS` | BSIS | MANDT | T001W |  | |
| `WERKS` | BSIS | WERKS | T001W |  | |

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