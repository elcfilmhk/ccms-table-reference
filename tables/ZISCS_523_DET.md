# ZISCS_523_DET
**Description:** Detail Table for ZCS523
**Total Fields:** 43
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
| 12 | `MATNR` | CHAR | 18 |  | Material Number |
| 13 | `NETWR` | CURR | 15 |  | Net value of the order item in document currency |
| 14 | `AUGBL` | CHAR | 12 |  | Clearing Document or Printed Document |
| 15 | `AUGBD` | DATS | 8 |  | Clearing document posting date |
| 16 | `SUB_ITM` | INT1 | 3 |  | &nbsp; |
| 17 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 18 | `AUGBT` | CURR | 13 |  | Clearing amount in clearing currency |
| 19 | `REVERSE` | CHAR | 12 |  | Clearing Document or Printed Document |
| 20 | `PAY_METHOD` | CHAR | 2 |  | Payment Method |
| 21 | `PYMET` | CHAR | 1 |  | Payment Method |
| 22 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 23 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 24 | `FIKEY` | CHAR | 12 |  | Reconciliation Key for General Ledger |
| 25 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 26 | `OPBEL_PRINT` | CHAR | 12 |  | Number of print document |
| 27 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 28 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 29 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 30 | `TOTAL_AMNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 31 | `PRE_INST_RESLT` | CHAR | 1 |  | Pre Installation Result |
| 32 | `POST_INST_RESLT` | CHAR | 1 |  | Post Installation Result |
| 33 | `FINAL_APP_DAT` | DATS | 8 |  | Field of type DATS |
| 34 | `EST_ANN_ENE_SAVE` | QUAN | 17 |  | Estimated Annual Energy Saving |
| 35 | `KWMENG` | QUAN | 15 |  | Cumulative Order Quantity in Sales Units |
| 36 | `EEUS_APPLN` | CHAR | 10 |  | EEUS Application Number |
| 37 | `ERDAT_EEUS` | DATS | 8 |  | Date on Which Record Was Created |
| 38 | `AUGWA` | CUKY | 5 |  | Clearing currency |
| 39 | `VRKME` | UNIT | 3 |  | Sales Unit |
| 40 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 41 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 42 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 43 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
