# ZDFKKKO
**Description:** Header Data in Open Item Accounting Document
**Total Fields:** 47
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0225`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 3 | `FIKEY` | CHAR | 12 |  | Reconciliation Key for General Ledger |
| 4 | `APPLK` | CHAR | 1 |  | Application area |
| 5 | `BLART` | CHAR | 2 |  | Document Type |
| 6 | `HERKF` | CHAR | 2 |  | Document Origin Key |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `CPUDT` | DATS | 8 |  | Day On Which Accounting Document Was Entered |
| 9 | `CPUTM` | TIMS | 6 |  | Time of Entry |
| 10 | `WAERS` | CUKY | 5 |  | Transaction Currency |
| 11 | `BLDAT` | DATS | 8 |  | Document Date in Document |
| 12 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 13 | `WWERT` | DATS | 8 |  | Translation date |
| 14 | `XBLNR` | CHAR | 16 |  | Reference Document Number |
| 15 | `RLGRD` | CHAR | 3 |  | Return Reason |
| 16 | `ABGRD` | CHAR | 2 |  | Posting Reason (For Write-Offs And Transfer Postings) |
| 17 | `XEIBH` | CHAR | 1 |  | Create Separate Document in General Ledger |
| 18 | `XBWER` | CHAR | 1 |  | Document Created by Foreign Currency Valuation or Reclass. |
| 19 | `AWTYP` | CHAR | 5 |  | Reference procedure |
| 20 | `AWKEY` | CHAR | 20 |  | Object key |
| 21 | `STBEL` | CHAR | 12 |  | Number of Reversed Document |
| 22 | `STMET` | CHAR | 1 |  | Reversal Method Selected Internally |
| 23 | `BLTYP` | CHAR | 1 |  | Document Class |
| 24 | `AGINF` | CHAR | 1 |  | Clearing Information |
| 25 | `STBUK` | CHAR | 4 |  | Tax Company Code |
| 26 | `STORB` | CHAR | 12 |  | Number of Reversal Document |
| 27 | `APPDX` | CHAR | 1 |  | Existing document supplements |
| 28 | `AWSYS` | CHAR | 10 |  | Logical system of source document |
| 29 | `VERSN` | CHAR | 3 |  | Version Number |
| 30 | `C4EYE` | CHAR | 2 |  | Check Reason for Workflows Acc. to Dual Control Principle |
| 31 | `C4EYP` | CHAR | 1 |  | Editing Process To Be Confirmed |
| 32 | `TATYP` | CHAR | 1 |  | Transaction Class of Document |
| 33 | `HBBLA` | CHAR | 2 |  | Document Type for Transfer to General Ledger |
| 34 | `XCSHA` | CHAR | 1 |  | Document Contains Assignments from Cash Flows |
| 35 | `UTLOC` | CHAR | 2 |  | Storage Location of Tax Supplement for Telco Tax (U.S.A) |
| 36 | `XTXCH` | CHAR | 1 |  | Tax Codes Were Exchanged |
| 37 | `VATDATE` | DATS | 8 |  | Tax Reporting Date |
| 38 | `WNPER` | NUMC | 2 |  | Requested Special Period for Transfer to General Ledger |
| 39 | `XSING` | CHAR | 1 |  | Individual Posting |
| 40 | `KEYPP` | NUMC | 3 |  | Subarea for Parallelization in Mass Processing |
| 41 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 42 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 43 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 44 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 45 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 46 | `.INCLUDE` | &nbsp; | 0 |  | Addition fields |
| 47 | `ZZSMISTXT` | CHAR | 50 |  | Indicator: updated by SMIS |
