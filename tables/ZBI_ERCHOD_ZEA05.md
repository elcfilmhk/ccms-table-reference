# ZBI_ERCHOD_ZEA05
**Description:** Outsort Billing doc for BW
**Total Fields:** 37
**Key Fields:** MANDT, BELNR

## Programs Using This Table
- `zbi_unbill`
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
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
| 17 | `DEVIATION` | DEC | 13 |  | Deviation |
| 18 | `IND` | CHAR | 2 |  | ZEA05 Indicator |
| 19 | `ADC` | DEC | 16 |  | Current ADC |
| 20 | `ADC_AVG` | DEC | 16 |  | Average ADC |
| 21 | `PER1` | DEC | 16 |  | % Change |
| 22 | `ADC1` | DEC | 16 |  | ADC (current bill -1) |
| 23 | `PER2` | DEC | 16 |  | % Change |
| 24 | `ADC2` | DEC | 16 |  | ADC (current bill - 2) |
| 25 | `PER3` | DEC | 16 |  | % Change |
| 26 | `ADC_LASTYR` | DEC | 16 |  | ADC for same period last year |
| 27 | `PER4` | DEC | 16 |  | % Change |
| 28 | `REMARKS` | CHAR | 100 |  | Remarks |
| 29 | `FREI_AM` | DATS | 8 |  | Document Release Date |
| 30 | `FREI_VON` | CHAR | 12 |  | Name of user who released the document |
| 31 | `STORNODAT` | DATS | 8 |  | Reversal date |
| 32 | `REVNAM` | CHAR | 12 |  | Reversed by |
| 33 | `RPT_TYPE` | CHAR | 8 |  | Unbill report type |
| 34 | `BCREASON` | CHAR | 2 |  | Reason for Reversal |
| 35 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 36 | `AETIM` | TIMS | 6 |  | Time |
| 37 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
