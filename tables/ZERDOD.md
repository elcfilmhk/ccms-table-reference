# ZERDOD
**Description:** Screen fields for ZEA05 (New invoice outsorting)
**Total Fields:** 65
**Key Fields:** _none_

## Programs Using This Table
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 2 | `OPBEL_OLD` | CHAR | 12 |  | Released print document |
| 3 | `REMARKS` | CHAR | 100 |  | Remarks |
| 4 | `AEDAT` | DATS | 8 |  | Remarks date |
| 5 | `AETIM` | TIMS | 6 |  | Remarks time |
| 6 | `AENAM` | CHAR | 12 |  | Remarks by |
| 7 | `GPARTNER` | CHAR | 10 |  | Business Partner Number |
| 8 | `BPINFO` | CHAR | 132 |  | Text for business partner |
| 9 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 10 | `VERTRAG` | CHAR | 10 |  | Contract |
| 11 | `PORTION` | CHAR | 8 |  | Portion |
| 12 | `.INCLUDE` | &nbsp; | 0 |  | Structure for Outsorting in Invoicing |
| 13 | `VALIDAT_IN` | CHAR | 10 |  | Name of Invoicing Validation |
| 14 | `MANOUTS_IN` | CHAR | 8 |  | Reason for manual outsorting in invoicing |
| 15 | `FREI_AM` | DATS | 8 |  | Document Release Date |
| 16 | `FREI_VON` | CHAR | 12 |  | Name of user who released the document |
| 17 | `DEVIATION` | DEC | 13 |  | Deviation |
| 18 | `SIMULATION` | CHAR | 2 |  | Indicator: billing simulation |
| 19 | `OUTCOUNT` | NUMC | 2 |  | Number of manual outsortings to be carried out yet |
| 20 | `SIMULATED` | CHAR | 1 |  | Indicator: simulated documents in outsorting |
| 21 | `BUKRS` | CHAR | 4 |  | Company Code |
| 22 | `SPARTE` | CHAR | 2 |  | Division |
| 23 | `ANLAGE` | CHAR | 10 |  | Installation |
| 24 | `ANLART` | CHAR | 4 |  | Installation type |
| 25 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 26 | `BILLDOCLINE` | NUMC | 6 |  | Billing line item for billing documents |
| 27 | `KTOKLASSE` | CHAR | 4 |  | Account class |
| 28 | `ABWVK` | CHAR | 12 |  | Alternative contract account for collective bills |
| 29 | `KOFIZ` | CHAR | 2 |  | Account determination ID for IS-U contracts |
| 30 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 31 | `CHILD` | CHAR | 1 |  | Child |
| 32 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 33 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
| 34 | `ZUORDDAA` | DATS | 8 |  | Allocation date for billing |
| 35 | `VALUE1` | DEC | 15 |  | Validation Parameter(s) |
| 36 | `VALUETEXT1` | CHAR | 20 |  | Text (20 Characters) |
| 37 | `VALUE2` | DEC | 15 |  | Validation Parameter(s) |
| 38 | `VALUETEXT2` | CHAR | 20 |  | Text (20 Characters) |
| 39 | `VALUE3` | DEC | 15 |  | Validation Parameter(s) |
| 40 | `VALUETEXT3` | CHAR | 20 |  | Text (20 Characters) |
| 41 | `VALUE4` | DEC | 15 |  | Validation Parameter(s) |
| 42 | `VALUETEXT4` | CHAR | 20 |  | Text (20 Characters) |
| 43 | `VALUE5` | CHAR | 10 |  | Validation Parameter(s) |
| 44 | `VALUETEXT5` | CHAR | 20 |  | Text (20 Characters) |
| 45 | `TOTAL_AMNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 46 | `TOTAL_WAER` | CUKY | 5 |  | Transaction Currency |
| 47 | `OUTCNSO` | NUMC | 4 |  | Consecutive number of outsorting |
| 48 | `STOKZ` | CHAR | 1 |  | Document Has Been Reversed |
| 49 | `STORNODAT` | DATS | 8 |  | Reversal date |
| 50 | `REVNAM` | CHAR | 12 |  | Reversed by |
| 51 | `BLDAT` | DATS | 8 |  | Document Date in Document |
| 52 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 53 | `AUSGRUP` | CHAR | 8 |  | Outsorting check group for billing |
| 54 | `AUSGRUPTXT` | CHAR | 30 |  | Outsorting Check Group |
| 55 | `%_COLOR` | CHAR | 3 |  | &nbsp; |
| 56 | `BOX` | CHAR | 1 |  | Single-Character Flag |
| 57 | `OSNAM` | CHAR | 12 |  | Outsort By |
| 58 | `FIT_IND` | CHAR | 1 |  | FiT Indicator |
| 59 | `NEWMI` | CHAR | 1 |  | New Move-In |
| 60 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 61 | `CONS_EST` | CHAR | 1 |  | Consecutive Estimate |
| 62 | `MTH_CONS_EST` | CHAR | 5 |  | Month with Consecutive Estimate |
| 63 | `EST_ACT` | CHAR | 1 |  | Estimated/Actual |
| 64 | `DUNLOCK` | CHAR | 1 |  | Dunning Lock |
| 65 | `APPR_STATUS` | CHAR | 1 |  | Approval Status |
