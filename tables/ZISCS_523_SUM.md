# ZISCS_523_SUM
**Description:** Summary Table for ZCS523
**Total Fields:** 34
**Key Fields:** MANDT, OPBEL, OPUPW, OPUPK, OPUPZ, VBELN, POSNR

## Programs Using This Table
- `ziscs0523`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 3 | `OPUPW` | NUMC | 3 | 🔑 | Repetition Item in Contract Account Document |
| 4 | `OPUPK` | NUMC | 4 | 🔑 | Item number in contract account document |
| 5 | `OPUPZ` | NUMC | 3 | 🔑 | Subitem for a Partial Clearing in Document |
| 6 | `VBELN` | CHAR | 10 | 🔑 | Sales Document |
| 7 | `POSNR` | NUMC | 6 | 🔑 | Sales Document Item |
| 8 | `CPUDT` | DATS | 8 |  | Day On Which Accounting Document Was Entered |
| 9 | `MAIN_SUB` | CHAR | 9 |  | Character field of 9 digits |
| 10 | `BLDAT` | DATS | 8 |  | Document Date in Document |
| 11 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 12 | `NETWR` | CURR | 15 |  | Net value of the order item in document currency |
| 13 | `AUGBL` | CHAR | 12 |  | Clearing Document or Printed Document |
| 14 | `AUGBD` | DATS | 8 |  | Clearing document posting date |
| 15 | `SUB_ITM` | INT1 | 3 |  | &nbsp; |
| 16 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 17 | `AUGBT` | CURR | 13 |  | Clearing amount in clearing currency |
| 18 | `REVERSE` | CHAR | 12 |  | Clearing Document or Printed Document |
| 19 | `PAY_METHOD` | CHAR | 2 |  | Payment Method |
| 20 | `PYMET` | CHAR | 1 |  | Payment Method |
| 21 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 22 | `FIKEY` | CHAR | 12 |  | Reconciliation Key for General Ledger |
| 23 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 24 | `OPBEL_PRINT` | CHAR | 12 |  | Number of print document |
| 25 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 26 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 27 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 28 | `TOTAL_AMNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 29 | `EEUS_APPLN` | CHAR | 10 |  | EEUS Application Number |
| 30 | `AUGWA` | CUKY | 5 |  | Clearing currency |
| 31 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 32 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 33 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 34 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
