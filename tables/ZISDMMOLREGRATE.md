# ZISDMMOLREGRATE
**Description:** Register Rate for Device Installation
**Total Fields:** 11
**Key Fields:** MANDT, CASE_NO, ZWNUMMER

## Programs Using This Table
- `zisdm0216`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CASE_NO` | NUMC | 18 | 🔑 | Case No. |
| 3 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 4 | `TARIFART` | CHAR | 8 |  | Rate Type |
| 5 | `KONDIGR` | CHAR | 10 |  | Rate fact group |
| 6 | `ZWNABR` | CHAR | 1 |  | Register not relevant to billing |
| 7 | `KENNZIFF` | CHAR | 15 |  | Code for Identifying a Register |
| 8 | `READING_IND` | CHAR | 1 |  | Indicator for reading exist in register |
| 9 | `READING` | CHAR | 36 |  | Meter reading recorded |
| 10 | `V_ZWSTAND` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 11 | `N_ZWSTAND` | DEC | 14 |  | Places After Decimal Point in the Meter Reading |
