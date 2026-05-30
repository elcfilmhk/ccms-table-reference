# `DFKKKO`

**Description:** CA Document Header — FI-CA document header
**Category:** Standard SAP Table
**References:** 174 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkko/) — validated 2026-05-30, schema v1.0
**Schema fields:** 37 fields | **Data types:** CHAR(29), CUKY(1), DATS(5), NUMC(1), TIMS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `FIKEY` | FIKEY_KK | — | CHAR | 12 | 0 | Reconciliation Key for General Ledger |
| `APPLK` | APPLK_KK | — | CHAR | 1 | 0 | Application area |
| `BLART` | BLART_KK | TFK003 | CHAR | 2 | 0 | Document Type |
| `HERKF` | HERKF_KK | — | CHAR | 2 | 0 | Document Origin Key |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `CPUDT` | CPUDT | — | DATS | 8 | 0 | Day On Which Accounting Document Was Entered |
| `CPUTM` | CPUTM | — | TIMS | 6 | 0 | Time of Entry |
| `WAERS` | BLWAE_KK | — | CUKY | 5 | 0 | Transaction Currency |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `BUDAT` | BUDAT_KK | — | DATS | 8 | 0 | Posting Date in the Document |
| `WWERT` | WWERT_D | — | DATS | 8 | 0 | Translation Date |
| `XBLNR` | XBLNR_KK | — | CHAR | 16 | 0 | Reference document number |
| `RLGRD` | RLGRD_KK | — | CHAR | 3 | 0 | Return reason |
| `ABGRD` | BUGRD_KK | — | CHAR | 2 | 0 | Posting Reason (For Write-Offs And Transfer Postings) |
| `XEIBH` | XEIBH_KK | — | CHAR | 1 | 0 | Create Separate Document in General Ledger |
| `XBWER` | XBWER_KK | — | CHAR | 1 | 0 | Document Created by Foreign Currency Valuation or Reclass. |
| `AWTYP` | AWTYP | — | CHAR | 5 | 0 | Reference Transaction |
| `AWKEY` | AWKEY | — | CHAR | 20 | 0 | Reference Key |
| `STBEL` | STBEL_KK | — | CHAR | 12 | 0 | Number of Reversed Document |
| `STMET` | STMET_INT_KK | — | CHAR | 1 | 0 | Reversal Method Selected Internally |
| `BLTYP` | BLTYP_KK | — | CHAR | 1 | 0 | Document Class |
| `AGINF` | AGINF_KK | — | CHAR | 1 | 0 | Clearing Information |
| `STBUK` | STBUK_KK | — | CHAR | 4 | 0 | Tax Company Code |
| `STORB` | STORB_KK | — | CHAR | 12 | 0 | Number of Reversal Document |
| `APPDX` | APPDX_KK | — | CHAR | 1 | 0 | Existing document supplements |
| `AWSYS` | AWSYS | — | CHAR | 10 | 0 | Logical system of source document |
| `VERSN` | VERSN_KK | — | CHAR | 3 | 0 | Version Number |
| `C4EYE` | C4EYE_KK | — | CHAR | 2 | 0 | Check Reason for Workflows Acc. to Dual Control Principle |
| `C4EYP` | C4EYP_KK | — | CHAR | 1 | 0 | Editing Process To Be Confirmed |
| `TATYP` | TATYP_KK | — | CHAR | 1 | 0 | Transaction Class of Document |
| `HBBLA` | HBBLA_KK | — | CHAR | 2 | 0 | Document Type for Transfer to General Ledger |
| `XCSHA` | XCSHA_KK | — | CHAR | 1 | 0 | Document Contains Assignments from Cash Flows |
| `UTLOC` | UTLOC_UT_KK | — | CHAR | 2 | 0 | Storage Location of Tax Supplement for Telco Tax (U.S.A) |
| `XTXCH` | XTXCH_KK | — | CHAR | 1 | 0 | Tax Codes Were Exchanged |
| `VATDATE` | VATDATE_KK | — | DATS | 8 | 0 | Tax Reporting Date |
| `WNPER` | WNPER_KK | — | NUMC | 2 | 0 | Requested Special Period for Transfer to General Ledger |
| `XSING` | XSING_KK | — | CHAR | 1 | 0 | Individual Posting |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `BLART` | DFKKKO | MANDT | TFK003 |  | |
| `BLART` | DFKKKO | APPLK | TFK003 |  | |
| `BLART` | DFKKKO | BLART | TFK003 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `BLART`, `BUDAT`, `CPUDT`, `ERNAM`, `HERKF`, `OPBEL`, `STBEL`, `STORB`, `XBLNR`, `blart`, `budat`, `cpudt`, `ernam`, `fikey`, `herkf`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `BLART`, `STORB`, `XBLNR`, `blart`, `budat`, `cpudt`, `opbel`, `stbel`, `xblnr`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_isbi_reverseclr_rebill.txt`
- `zisbi0032.txt`
- `zisbi0225f01.txt`
- `ziscs0088.txt`
- `ziscs0517forms.txt`
- `ziscs1118.txt`
- `ziscs_migration_adjustment.txt`
- `ziscs_migration_financial_tran.txt`
- `zisfi0036.txt`
- `zisfi0069.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test3.txt`
- `zisfi0131.txt`
- `zisfi0139.txt`
- `zisfi0238_bw.txt`
- `zisfi0300.txt`
- `zisfi0351.txt`
- `zissd00063.txt`
- `zprintdoc.txt`
- `zzrepair.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_