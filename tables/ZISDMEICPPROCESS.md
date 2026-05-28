# ZISDMEICPPROCESS
**Description:** Installation for expected consumption preview
**Total Fields:** 15
**Key Fields:** MANDT, ANLAGE, FROM_DATE, SERNR, ZWNUMMER, ADAT

## Programs Using This Table
- `zisdm0257`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `FROM_DATE` | DATS | 8 | 🔑 | From Date |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Device |
| 5 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 6 | `ADAT` | DATS | 8 | 🔑 | Meter reading date relevant to billing |
| 7 | `TO_DATE` | DATS | 8 |  | To Date |
| 8 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 9 | `CSMP_PREV_YR` | DEC | 31 |  | Expected consumption: internal format |
| 10 | `CSMP_PREV_PER` | DEC | 31 |  | Expected consumption: internal format |
| 11 | `BILL_RELV` | CHAR | 1 |  | Billing Relevant |
| 12 | `MODULE_NAME` | CHAR | 100 |  | Module Name |
| 13 | `PID` | NUMC | 5 |  | Process ID |
| 14 | `PROCESSED` | CHAR | 1 |  | Processed |
| 15 | `ERROR_MSG` | CHAR | 100 |  | Error Message |
