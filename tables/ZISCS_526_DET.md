# ZISCS_526_DET
**Description:** Detail Table for ZCS526
**Total Fields:** 47
**Key Fields:** MANDT, FICA_DOC, OPUPW, OPUPK, OPUPZ, STOKZ, PRINTDOC, BELNR, RE_SYS_LOC, GERAET, FIT_START_DATE, FIT_END_DATE

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
| 9 | `RE_SYS_LOC` | CHAR | 10 | 🔑 | RE System Location |
| 10 | `GERAET` | CHAR | 18 | 🔑 | Device |
| 11 | `FIT_START_DATE` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 12 | `FIT_END_DATE` | DATS | 8 | 🔑 | Date at Which a Time Slice Expires |
| 13 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 14 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 15 | `FIKEY` | CHAR | 12 |  | Reconciliation Key for General Ledger |
| 16 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 17 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 18 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 19 | `BLDAT` | DATS | 8 |  | Document Date in Document |
| 20 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 21 | `CPUDT` | DATS | 8 |  | Day On Which Accounting Document Was Entered |
| 22 | `BETRH` | CURR | 13 |  | Amount In Local Currency With +/- Signs |
| 23 | `HKONT` | CHAR | 10 |  | General ledger account |
| 24 | `PYMET` | CHAR | 2 |  | FiT Payment Option |
| 25 | `AUGBL` | CHAR | 12 |  | Clearing Document or Printed Document |
| 26 | `AUGST` | CHAR | 1 |  | Clearing status |
| 27 | `AUGBT` | CURR | 13 |  | Clearing amount in clearing currency |
| 28 | `AUGVD` | DATS | 8 |  | Value date for clearing |
| 29 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 30 | `AUGBD` | DATS | 8 |  | Clearing document posting date |
| 31 | `PRINTDOC_REV` | CHAR | 12 |  | Number of Print Document Used to Reverse Document |
| 32 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 33 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 34 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 35 | `TOTAL_AMNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 36 | `RE_SOURCE` | CHAR | 2 |  | RE Source |
| 37 | `FIT_CAPACITY` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 38 | `FIT_GENERATION` | DEC | 31 |  | Profile value at application level |
| 39 | `FIT_RATE` | DEC | 4 |  | FiT Rate |
| 40 | `NO_OF_DAYS` | DEC | 17 |  | Predecimal place of a time portion |
| 41 | `FIT_REBATE_AMT` | CURR | 13 |  | &nbsp; |
| 42 | `TOTAL_WAER` | CUKY | 5 |  | Transaction Currency |
| 43 | `VRKME` | UNIT | 3 |  | Sales Unit |
| 44 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 45 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 46 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 47 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
