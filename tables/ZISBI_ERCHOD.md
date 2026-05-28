# ZISBI_ERCHOD
**Description:** Outsorting in Billing Header
**Total Fields:** 37
**Key Fields:** MANDT, ERDAT, BELNR

## Programs Using This Table
- `zisbi0139`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERDAT` | DATS | 8 | 🔑 | Run Date |
| 3 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 4 | `GPARTNER` | CHAR | 10 |  | Business Partner Number |
| 5 | `BPINFO` | CHAR | 132 |  | Text for business partner |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `VERTRAG` | CHAR | 10 |  | Contract |
| 8 | `PORTION` | CHAR | 8 |  | Portion |
| 9 | `VALIDATION` | CHAR | 10 |  | Name of billing validation |
| 10 | `MANOUTSORT` | CHAR | 8 |  | Reason for manual outsorting in billing |
| 11 | `FREI_AM` | DATS | 8 |  | Document Release Date |
| 12 | `FREI_VON` | CHAR | 12 |  | Name of user who released the document |
| 13 | `DEVIATION` | DEC | 13 |  | Deviation |
| 14 | `SIMULATION` | CHAR | 2 |  | Indicator: billing simulation |
| 15 | `OUTCOUNT` | NUMC | 2 |  | Number of manual outsortings to be carried out yet |
| 16 | `STORNODAT` | DATS | 8 |  | Reversal date |
| 17 | `SIMULATED` | CHAR | 1 |  | Indicator: simulated documents in outsorting |
| 18 | `BUKRS` | CHAR | 4 |  | Company Code |
| 19 | `SPARTE` | CHAR | 2 |  | Division |
| 20 | `ANLAGE` | CHAR | 10 |  | Installation |
| 21 | `ANLART` | CHAR | 4 |  | Installation type |
| 22 | `KTOKLASSE` | CHAR | 4 |  | Account class |
| 23 | `ABWVK` | CHAR | 12 |  | Alternative contract account for collective bills |
| 24 | `KOFIZ` | CHAR | 2 |  | Account determination ID for IS-U contracts |
| 25 | `ABLEINH` | CHAR | 8 |  | Meter Reading Unit |
| 26 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 27 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
| 28 | `ZUORDDAA` | DATS | 8 |  | Allocation date for billing |
| 29 | `BILLINGRUNNO` | CHAR | 12 |  | Number of Billing Run |
| 30 | `AUSGRUP` | CHAR | 8 |  | Outsorting check group for billing |
| 31 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 32 | `VALUE1` | DEC | 15 |  | Validation Parameter(s) |
| 33 | `VALUE2` | DEC | 15 |  | Validation Parameter(s) |
| 34 | `VALUE3` | DEC | 15 |  | Validation Parameter(s) |
| 35 | `VALUE4` | DEC | 15 |  | Validation Parameter(s) |
| 36 | `VALUE5` | CHAR | 10 |  | Validation Parameter(s) |
| 37 | `TOBRELEASD` | CHAR | 1 |  | Indicator: document not released yet |
