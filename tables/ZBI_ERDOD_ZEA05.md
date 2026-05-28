# ZBI_ERDOD_ZEA05
**Description:** Outsort Print doc for BW
**Total Fields:** 39
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 3 | `GPARTNER` | CHAR | 10 |  | Business Partner Number |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `VERTRAG` | CHAR | 10 |  | Contract |
| 6 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 7 | `ANLAGE` | CHAR | 10 |  | Installation |
| 8 | `PORTION` | CHAR | 8 |  | Portion |
| 9 | `ABLEINH` | CHAR | 8 |  | Meter Reading Unit |
| 10 | `VALIDATION` | CHAR | 10 |  | Name of billing validation |
| 11 | `CHILD` | CHAR | 1 |  | Child |
| 12 | `MANOUTSORT` | CHAR | 8 |  | Reason for manual outsorting in billing |
| 13 | `OSNAM` | CHAR | 12 |  | Outsort By |
| 14 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 15 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
| 16 | `ZUORDDAA` | DATS | 8 |  | Allocation date for billing |
| 17 | `BLDAT` | DATS | 8 |  | Document Date in Document |
| 18 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 19 | `DEVIATION` | DEC | 13 |  | Deviation |
| 20 | `IND` | CHAR | 2 |  | ZEA05 Indicator |
| 21 | `ADC` | DEC | 16 |  | Current ADC |
| 22 | `ADC_AVG` | DEC | 16 |  | Average ADC |
| 23 | `PER1` | DEC | 16 |  | % Change |
| 24 | `ADC1` | DEC | 16 |  | ADC (current bill -1) |
| 25 | `PER2` | DEC | 16 |  | % Change |
| 26 | `ADC2` | DEC | 16 |  | ADC (current bill - 2) |
| 27 | `PER3` | DEC | 16 |  | % Change |
| 28 | `ADC_LASTYR` | DEC | 16 |  | ADC for same period last year |
| 29 | `PER4` | DEC | 16 |  | % Change |
| 30 | `REMARKS` | CHAR | 100 |  | Remarks |
| 31 | `FREI_AM` | DATS | 8 |  | Document Release Date |
| 32 | `FREI_VON` | CHAR | 12 |  | Name of user who released the document |
| 33 | `STORNODAT` | DATS | 8 |  | Reversal date |
| 34 | `REVNAM` | CHAR | 12 |  | Name of person who changed object |
| 35 | `RPT_TYPE` | CHAR | 8 |  | Unbill report type |
| 36 | `ICREASON` | CHAR | 2 |  | Reason for Reversal |
| 37 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 38 | `AETIM` | TIMS | 6 |  | Time |
| 39 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
