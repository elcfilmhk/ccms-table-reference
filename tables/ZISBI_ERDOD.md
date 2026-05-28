# ZISBI_ERDOD
**Description:** Outsorting in Invoicing Header
**Total Fields:** 48
**Key Fields:** MANDT, ERDAT, OPBEL

## Programs Using This Table
- `zisbi0139`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERDAT` | DATS | 8 | 🔑 | Run Date |
| 3 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 4 | `GPARTNER` | CHAR | 10 |  | Business Partner Number |
| 5 | `BPINFO` | CHAR | 132 |  | Text for business partner |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `VERTRAG` | CHAR | 10 |  | Contract |
| 8 | `PORTION` | CHAR | 8 |  | Portion |
| 9 | `.INCLUDE` | &nbsp; | 0 |  | Structure for Outsorting in Invoicing |
| 10 | `VALIDAT_IN` | CHAR | 10 |  | Name of Invoicing Validation |
| 11 | `MANOUTS_IN` | CHAR | 8 |  | Reason for manual outsorting in invoicing |
| 12 | `FREI_AM` | DATS | 8 |  | Document Release Date |
| 13 | `FREI_VON` | CHAR | 12 |  | Name of user who released the document |
| 14 | `DEVIATION` | DEC | 13 |  | Deviation |
| 15 | `SIMULATION` | CHAR | 2 |  | Indicator: billing simulation |
| 16 | `OUTCOUNT` | NUMC | 2 |  | Number of manual outsortings to be carried out yet |
| 17 | `SIMULATED` | CHAR | 1 |  | Indicator: simulated documents in outsorting |
| 18 | `BUKRS` | CHAR | 4 |  | Company Code |
| 19 | `SPARTE` | CHAR | 2 |  | Division |
| 20 | `ANLAGE` | CHAR | 10 |  | Installation |
| 21 | `ANLART` | CHAR | 4 |  | Installation type |
| 22 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 23 | `BILLDOCLINE` | NUMC | 6 |  | Billing line item for billing documents |
| 24 | `KTOKLASSE` | CHAR | 4 |  | Account class |
| 25 | `ABWVK` | CHAR | 12 |  | Alternative contract account for collective bills |
| 26 | `KOFIZ` | CHAR | 2 |  | Account determination ID for IS-U contracts |
| 27 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 28 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 29 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
| 30 | `ZUORDDAA` | DATS | 8 |  | Allocation date for billing |
| 31 | `VALUE1` | DEC | 15 |  | Validation Parameter(s) |
| 32 | `VALUETEXT1` | CHAR | 20 |  | Text (20 Characters) |
| 33 | `VALUE2` | DEC | 15 |  | Validation Parameter(s) |
| 34 | `VALUETEXT2` | CHAR | 20 |  | Text (20 Characters) |
| 35 | `VALUE3` | DEC | 15 |  | Validation Parameter(s) |
| 36 | `VALUETEXT3` | CHAR | 20 |  | Text (20 Characters) |
| 37 | `VALUE4` | DEC | 15 |  | Validation Parameter(s) |
| 38 | `VALUETEXT4` | CHAR | 20 |  | Text (20 Characters) |
| 39 | `VALUE5` | CHAR | 10 |  | Validation Parameter(s) |
| 40 | `VALUETEXT5` | CHAR | 20 |  | Text (20 Characters) |
| 41 | `TOTAL_AMNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 42 | `TOTAL_WAER` | CUKY | 5 |  | Transaction Currency |
| 43 | `OUTCNSO` | NUMC | 4 |  | Consecutive number of outsorting |
| 44 | `STOKZ` | CHAR | 1 |  | Document Has Been Reversed |
| 45 | `BLDAT` | DATS | 8 |  | Document Date in Document |
| 46 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 47 | `AUSGRUP` | CHAR | 8 |  | Outsorting check group for billing |
| 48 | `AUSGRUPTXT` | CHAR | 30 |  | Outsorting Check Group |
