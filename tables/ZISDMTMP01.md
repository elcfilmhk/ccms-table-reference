# ZISDMTMP01
**Description:** Temporary table for batch verifaction of mr data.
**Total Fields:** 38
**Key Fields:** MANDT, RUNDATE, RUNTIME, BATCHDATE, GERNR, GROES, INVNR, ZWNUMMER, ADAT

## Programs Using This Table
- `zisdm0052`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | System Date |
| 3 | `RUNTIME` | TIMS | 6 | 🔑 | System Time |
| 4 | `BATCHDATE` | DATS | 8 | 🔑 | System Date |
| 5 | `GERNR` | CHAR | 18 | 🔑 | Device |
| 6 | `GROES` | CHAR | 18 | 🔑 | Size/dimension |
| 7 | `INVNR` | CHAR | 25 | 🔑 | Inventory number |
| 8 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 9 | `ADAT` | DATS | 8 | 🔑 | Meter reading date relevant to billing |
| 10 | `ZWFAKT` | DEC | 12 |  | Register factor |
| 11 | `PERVERBR` | DEC | 11 |  | Period Consumption |
| 12 | `PER_CONS_DAYS` | INT4 | 10 |  | Number of days |
| 13 | `MRDATE_06` | DATS | 8 |  | System Date |
| 14 | `MR_06` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 15 | `MRDATE_17` | DATS | 8 |  | System Date |
| 16 | `MR_17` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 17 | `MRDATE_01` | DATS | 8 |  | System Date |
| 18 | `MR_01` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 19 | `ACTUAL_CONS` | DEC | 31 |  | Billing quantity for internal billing format |
| 20 | `EXPEC_MR` | DEC | 31 |  | Expected meter reading: internal format |
| 21 | `EXPEC_CONS` | DEC | 31 |  | Expected consumption: internal format |
| 22 | `HIGH1PERC` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 23 | `HIGH2PERC` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 24 | `LOW1PERC` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 25 | `LOW2PERC` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 26 | `CALC_PER_CONS` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 27 | `DAYS_DIFF_01_17` | INT4 | 10 |  | Number of days |
| 28 | `DAYS_DIFF_01_06` | INT4 | 10 |  | Number of days |
| 29 | `CALC_MR` | DEC | 31 |  | Expected meter reading: internal format |
| 30 | `CALC_CONS` | DEC | 31 |  | Expected consumption: internal format |
| 31 | `HIGH1PERC2` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 32 | `HIGH2PERC2` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 33 | `LOW1PERC2` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 34 | `LOW2PERC2` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 35 | `HIGH1LIMIT2` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 36 | `HIGH2LIMIT2` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 37 | `LOW1LIMIT2` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
| 38 | `LOW2LIMIT2` | DEC | 24 |  | Decimal number, 24 digits, 3 decimal places |
