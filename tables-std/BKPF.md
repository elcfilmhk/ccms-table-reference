# `BKPF`

**Description:** Accounting Document Header — FI doc header
**Category:** Standard SAP Table
**References:** 29 SELECT statements across 11 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/bkpf/) — validated 2026-05-30, schema v1.0
**Schema fields:** 111 fields | **Data types:** CHAR(78), CUKY(5), CURR(1), DATS(13), DEC(8), NUMC(4), TIMS(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BLART` | BLART | T003 | CHAR | 2 | 0 | Document Type |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `BUDAT` | BUDAT | — | DATS | 8 | 0 | Posting Date in the Document |
| `MONAT` | MONAT | — | NUMC | 2 | 0 | Fiscal Period |
| `CPUDT` | CPUDT | — | DATS | 8 | 0 | Day On Which Accounting Document Was Entered |
| `CPUTM` | CPUTM | — | TIMS | 6 | 0 | Time of Entry |
| `AEDAT` | AEDAT_BKPF | — | DATS | 8 | 0 | Date of the Last Document Change by Transaction |
| `UPDDT` | UPDDT | — | DATS | 8 | 0 | Date of the Last Document Update |
| `WWERT` | WWERT_D | — | DATS | 8 | 0 | Translation Date |
| `USNAM` | USNAM | — | CHAR | 12 | 0 | User name |
| `TCODE` | TCODE | — | CHAR | 20 | 0 | Transaction Code |
| `BVORG` | BVORG | — | CHAR | 16 | 0 | Number of Cross-Company Code Posting Transaction |
| `XBLNR` | XBLNR1 | — | CHAR | 16 | 0 | Reference Document Number |
| `DBBLG` | DBBLG | — | CHAR | 10 | 0 | Recurring Entry Document Number |
| `STBLG` | STBLG | — | CHAR | 10 | 0 | Reverse Document Number |
| `STJAH` | STJAH | — | NUMC | 4 | 0 | Reverse document fiscal year |
| `BKTXT` | BKTXT | — | CHAR | 25 | 0 | Document Header Text |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `KURSF` | KURSF | — | DEC | 9 | 5 | Exchange rate |
| `KZWRS` | KZWRS | TCURC | CUKY | 5 | 0 | Currency Key for the Group Currency |
| `KZKRS` | KZKRS | — | DEC | 9 | 5 | Group Currency Exchange Rate |
| `BSTAT` | BSTAT_D | — | CHAR | 1 | 0 | Document Status |
| `XNETB` | XNETB | — | CHAR | 1 | 0 | Indicator: Document posted net ? |
| `FRATH` | FRATH | — | CURR | 13 | 2 | Unplanned delivery costs |
| `XRUEB` | XRUEB | — | CHAR | 1 | 0 | Indicator: Document is posted to a previous period |
| `GLVOR` | GLVOR | — | CHAR | 4 | 0 | Business Transaction |
| `GRPID` | GRPID_BKPF | — | CHAR | 12 | 0 | Batch Input Session Name |
| `DOKID` | DOKID_BKPF | — | CHAR | 40 | 0 | Document Name in the Archive System |
| `ARCID` | EXTID_BKPF | — | CHAR | 10 | 0 | Extract ID Document Header |
| `IBLAR` | IBLAR | — | CHAR | 2 | 0 | Internal Document Type for Document Control |
| `AWTYP` | AWTYP | — | CHAR | 5 | 0 | Reference Transaction |
| `AWKEY` | AWKEY | — | CHAR | 20 | 0 | Reference Key |
| `FIKRS` | FIKRS | — | CHAR | 4 | 0 | Financial Management Area |
| `HWAER` | HWAER | — | CUKY | 5 | 0 | Local Currency |
| `HWAE2` | HWAE2 | — | CUKY | 5 | 0 | Currency Key of Second Local Currency |
| `HWAE3` | HWAE3 | — | CUKY | 5 | 0 | Currency Key of Third Local Currency |
| `KURS2` | KURS2 | — | DEC | 9 | 5 | Exchange Rate for the Second Local Currency |
| `KURS3` | KURS3 | — | DEC | 9 | 5 | Exchange Rate for the Third Local Currency |
| `BASW2` | CURSR | — | CHAR | 1 | 0 | Source Currency for Currency Translation |
| `BASW3` | CURSR | — | CHAR | 1 | 0 | Source Currency for Currency Translation |
| `UMRD2` | UMRD2 | — | CHAR | 1 | 0 | Translation Date Type for Second Local Currency |
| `UMRD3` | UMRD3 | — | CHAR | 1 | 0 | Translation Date Type for Third Local Currency |
| `XSTOV` | XSTOV | — | CHAR | 1 | 0 | Indicator: Document is flagged for reversal |
| `STODT` | STODT | — | DATS | 8 | 0 | Planned Date for the Reverse Posting |
| `XMWST` | XMWST | — | CHAR | 1 | 0 | Calculate tax automatically |
| `CURT2` | CURT2 | — | CHAR | 2 | 0 | Currency Type of Second Local Currency |
| `CURT3` | CURT3 | — | CHAR | 2 | 0 | Currency Type of Third Local Currency |
| `KUTY2` | KURST | TCURV | CHAR | 4 | 0 | Exchange Rate Type |
| `KUTY3` | KURST | TCURV | CHAR | 4 | 0 | Exchange Rate Type |
| `XSNET` | XSNET | — | CHAR | 1 | 0 | G/L account amounts entered exclude tax |
| `AUSBK` | AUSBK | T001 | CHAR | 4 | 0 | Source Company Code |
| `XUSVR` | XUSVR_BKPF | — | CHAR | 1 | 0 | Indicator: US taxes changed at detail level ? |
| `DUEFL` | DUEFL_BKPF | — | CHAR | 1 | 0 | Status of Data Transfer into Subsequent Release |
| `AWSYS` | LOGSYSTEM | — | CHAR | 10 | 0 | Logical System |
| `TXKRS` | TXKRS_BKPF | — | DEC | 9 | 5 | Exchange Rate for Taxes |
| `LOTKZ` | PSO_LOTKZ | — | CHAR | 10 | 0 | Lot Number for Requests |
| `XWVOF` | XWVOF | — | CHAR | 1 | 0 | Indicator: Customer bill of exchange payment before due date |
| `STGRD` | STGRD | T041C | CHAR | 2 | 0 | Reason for Reversal |
| `PPNAM` | PPNAM | — | CHAR | 12 | 0 | Name of User Who Parked this Document |
| `BRNCH` | J_1ABRNCH | J_1BBRANCH | CHAR | 4 | 0 | Branch Number |
| `NUMPG` | J_1ANOPG | — | NUMC | 3 | 0 | Number of pages of invoice |
| `ADISC` | J_1ADISC | — | CHAR | 1 | 0 | Indicator: entry represents a discount document |
| `XREF1_HD` | XREF1_HD | — | CHAR | 20 | 0 | Reference Key 1 Internal for Document Header |
| `XREF2_HD` | XREF2_HD | — | CHAR | 20 | 0 | Reference Key 2 Internal for Document Header |
| `XREVERSAL` | XREVERSAL | — | CHAR | 1 | 0 | Specifies whether doc. is reversal doc. or reversed doc. |
| `REINDAT` | REINDAT | — | DATS | 8 | 0 | Invoice Receipt Date |
| `RLDNR` | FAGL_RLDNR | T882G | CHAR | 2 | 0 | Ledger in General Ledger Accounting |
| `LDGRP` | FAGL_LDGRP | FAGL_TLDGRP | CHAR | 4 | 0 | Ledger Group |
| `PROPMANO` | RE_MANDAT | — | CHAR | 13 | 0 | Real Estate Management Mandate |
| `XBLNR_ALT` | XBLNR_ALT | — | CHAR | 26 | 0 | Alternative Reference Number |
| `VATDATE` | VATDATE | — | DATS | 8 | 0 | Tax Reporting Date |
| `DOCCAT` | DOCUMENT_CATEGORY | — | CHAR | 6 | 0 | Classification of an FI Document |
| `XSPLIT` | SPLIT_POSTING | — | CHAR | 1 | 0 | FI Document Originates from Split Posting (Indicator) |
| `CASH_ALLOC` | FAGL_CASH_ALLOC | — | CHAR | 1 | 0 | Cash-Relevant Document |
| `FOLLOW_ON` | FAGL_FOLLOW_ON | — | CHAR | 1 | 0 | Follow-on document indicator |
| `XREORG` | FAGL_R_XDOC_REORG | — | CHAR | 1 | 0 | Doc. Contains Open Item that Was Transferred During Reorg. |
| `SUBSET` | ACC_SUBSET | — | CHAR | 4 | 0 | Defines subset of components for the FI/CO interface |
| `KURST` | KURST | TCURV | CHAR | 4 | 0 | Exchange Rate Type |
| `KURSX` | GLE_FXR_DTE_RATEX28 | — | DEC | 28 | 14 | Market Data Exchange Rate |
| `KUR2X` | GLE_FXR_DTE_RATE2X28 | — | DEC | 28 | 14 | Market Data Exchange Rate 2 |
| `KUR3X` | GLE_FXR_DTE_RATE3X28 | — | DEC | 28 | 14 | Market Data Exchange Rate 3 |
| `XMCA` | GLE_DTE_MCA_XMCA | — | CHAR | 1 | 0 | Document Originates from Multi Currency Accounting |
| `/SAPF15/STATUS` | /SAPF15/STATUS | — | CHAR | 1 | 0 | /SAPF15/STATUS |
| `PSOTY` | PSOTY_D | PSOTP | CHAR | 2 | 0 | Document category payment requests |
| `PSOAK` | PSOAK | PSO12 | CHAR | 10 | 0 | Reason |
| `PSOKS` | PSOKS | — | CHAR | 10 | 0 | Region |
| `PSOSG` | PSOSG | — | CHAR | 1 | 0 | Reason for reversal - IS-PS requests |
| `PSOFN` | PSOFN | — | CHAR | 30 | 0 | IS-PS: File number |
| `INTFORM` | FM_INTFORM | — | CHAR | 4 | 0 | Interest Formula |
| `INTDATE` | FM_INTDATE | — | DATS | 8 | 0 | Interest Calc. Date |
| `PSOBT` | PSOBT | — | DATS | 8 | 0 | Posting Day |
| `PSOZL` | PSOZL | — | CHAR | 1 | 0 | Actual posting |
| `PSODT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `PSOTM` | PSOTM | — | TIMS | 6 | 0 | Last changed at |
| `FM_UMART` | FM_UMART | — | CHAR | 1 | 0 | Type of Payment Transfer |
| `CCINS` | CCINS_30F | TCRIN | CHAR | 4 | 0 | Payment cards: Card type |
| `CCNUM` | CCNUM_30F | — | CHAR | 25 | 0 | Payment cards: Card number |
| `SSBLK` | SSBLK | — | CHAR | 1 | 0 | Payment Statistical Sampling Block |
| `BATCH` | LOTKZ | — | CHAR | 10 | 0 | Lot Number for Documents |
| `SNAME` | UNAME | — | CHAR | 12 | 0 | User Name |
| `SAMPLED` | SAMPLED | — | CHAR | 1 | 0 | Sampled Invoice by Payment Certification |
| `EXCLUDE_FLAG` | EXCLUDE_FLG | — | CHAR | 1 | 0 | PPA Exclude Indicator |
| `BLIND` | FM_BLIND | — | CHAR | 1 | 0 | Budgetary Ledger Indicator |
| `OFFSET_STATUS` | FMFG_OFFSET_STATUS | — | CHAR | 2 | 0 | Treasury Offset Status |
| `OFFSET_REFER_DAT` | FMFG_REFERRED_OFFSET_DAT | — | DATS | 8 | 0 | Date Record Referred to Treasury |
| `PENRC` | PENRC | — | CHAR | 2 | 0 | Reason for late payment |
| `KNUMV` | KNUMV | — | CHAR | 10 | 0 | Number of the document condition |
| `OINETNUM` | OIA_NETNUM | — | CHAR | 10 | 0 | Exchange - netting document number |
| `OINJAHR` | GJAHR | — | NUMC | 4 | 0 | Fiscal Year |
| `OININD` | OIA_NET | — | CHAR | 1 | 0 | Movement-based netting indicator |
| `RECHN` | XRECH | — | CHAR | 1 | 0 | Indicator: post invoice |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `AUSBK` | BKPF | MANDT | T001 |  | |
| `AUSBK` | BKPF | AUSBK | T001 |  | |
| `BLART` | BKPF | MANDT | T003 |  | |
| `BLART` | BKPF | BLART | T003 |  | |
| `BRNCH` | BKPF | MANDT | J_1BBRANCH |  | |
| `BRNCH` | BKPF | BUKRS | J_1BBRANCH |  | |
| `BRNCH` | BKPF | BRNCH | J_1BBRANCH |  | |
| `BUKRS` | BKPF | MANDT | T001 |  | |
| `BUKRS` | BKPF | BUKRS | T001 |  | |
| `CCINS` | SYST | MANDT | TCRIN |  | |
| `CCINS` | BKPF | CCINS | TCRIN |  | |
| `KURST` | BKPF | KURST | TCURV |  | |
| `KURST` | BKPF | MANDT | TCURV |  | |
| `KUTY2` | BKPF | MANDT | TCURV |  | |
| `KUTY2` | BKPF | KUTY2 | TCURV |  | |
| `KUTY3` | BKPF | MANDT | TCURV |  | |
| `KUTY3` | BKPF | KUTY3 | TCURV |  | |
| `KZWRS` | BKPF | MANDT | TCURC |  | |
| `KZWRS` | BKPF | KZWRS | TCURC |  | |
| `LDGRP` | BKPF | MANDT | FAGL_TLDGRP |  | |
| `LDGRP` | BKPF | LDGRP | FAGL_TLDGRP |  | |
| `MANDT` | BKPF | MANDT | T000 |  | |
| `PSOAK` | BKPF | PSOAK | PSO12 |  | |
| `PSOAK` | T000 | MANDT | PSO12 |  | |
| `PSOTY` | BKPF | PSOTY | PSOTP |  | |
| `RLDNR` | BKPF | MANDT | T882G |  | |
| `RLDNR` | BKPF | BUKRS | T882G |  | |
| `RLDNR` | BKPF | RLDNR | T882G |  | |
| `STGRD` | BKPF | STGRD | T041C |  | |
| `STGRD` | BKPF | MANDT | T041C |  | |
| `WAERS` | BKPF | MANDT | TCURC |  | |
| `WAERS` | BKPF | WAERS | TCURC |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
- `BKPF.BELNR` → `BSEG.BELNR` — FI Header → FI Line Item

## Programs Using This Table
- `zbacbe034.txt`
- `zfchzuord_2.txt`
- `zisfi0029.txt`
- `zisfi0043.txt`
- `zisfi0083.txt`
- `zisfi0083_1.txt`
- `zisfi0083_1t.txt`
- `zisfi0083_2.txt`
- `zisfi0090.txt`
- `zisfi0238_bw.txt`
- `zrepmir7.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_