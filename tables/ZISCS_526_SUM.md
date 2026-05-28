# ZISCS_526_SUM
**Description:** Summary Table for ZCS526
**Total Fields:** 36
**Key Fields:** MANDT, FICA_DOC, OPUPW, OPUPK, OPUPZ, STOKZ, PRINTDOC, BELNR

## Programs Using This Table
- `ziscs0517`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FICA_DOC` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 3 | `OPUPW` | NUMC | 3 | 🔑 | Repetition Item in Contract Account Document |
| 4 | `OPUPK` | NUMC | 4 | 🔑 | Item number in contract account document |
| 5 | `OPUPZ` | NUMC | 3 | 🔑 | Subitem for a Partial Clearing in Document |
| 6 | `STOKZ` | CHAR | 1 | 🔑 | Document Has Been Reversed |
| 7 | `PRINTDOC` | CHAR | 12 | 🔑 | Number of print document |
| 8 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 9 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 10 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 11 | `FIKEY` | CHAR | 12 |  | Reconciliation Key for General Ledger |
| 12 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 13 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 14 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 15 | `BLDAT` | DATS | 8 |  | Document Date in Document |
| 16 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 17 | `CPUDT` | DATS | 8 |  | Day On Which Accounting Document Was Entered |
| 18 | `BETRH` | CURR | 13 |  | Amount In Local Currency With +/- Signs |
| 19 | `HKONT` | CHAR | 10 |  | General ledger account |
| 20 | `PYMET` | CHAR | 2 |  | FiT Payment Option |
| 21 | `AUGBL` | CHAR | 12 |  | Clearing Document or Printed Document |
| 22 | `AUGST` | CHAR | 1 |  | Clearing status |
| 23 | `AUGBT` | CURR | 13 |  | Clearing amount in clearing currency |
| 24 | `AUGVD` | DATS | 8 |  | Value date for clearing |
| 25 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 26 | `AUGBD` | DATS | 8 |  | Clearing document posting date |
| 27 | `PRINTDOC_REV` | CHAR | 12 |  | Number of Print Document Used to Reverse Document |
| 28 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 29 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 30 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 31 | `TOTAL_AMNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 32 | `TOTAL_WAER` | CUKY | 5 |  | Transaction Currency |
| 33 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 34 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 35 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 36 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
