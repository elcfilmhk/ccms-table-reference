# ZISDMRELTL
**Description:** Custom table for report IV 05/06 Released Tolerance List
**Total Fields:** 22
**Key Fields:** MANDT, GERNR, ZWNUMMER, VKONT, PRUEFPKT

## Programs Using This Table
- `zisdm0035`
- `zisdm0072`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `PRUEFPKT` | CHAR | 2 | 🔑 | Independent validation |
| 6 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 7 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 8 | `ZZDAYS` | NUMC | 5 |  | 5 Character Numeric NUMC |
| 9 | `PREV_CONSUMPTION` | DEC | 13 |  | Consumption - Device Level |
| 10 | `CONSUMPTION` | DEC | 13 |  | Consumption - Device Level |
| 11 | `TEMP_VARIANCE` | CHAR | 32 |  | Variance |
| 12 | `CONS_VARIANCE` | CHAR | 32 |  | Variance |
| 13 | `UPPER1` | CHAR | 32 |  | Upper Limit 1 |
| 14 | `LOWER1` | CHAR | 32 |  | Lower Limit 1 |
| 15 | `UPPER2` | CHAR | 32 |  | Upper Limit 2 |
| 16 | `LOWER2` | CHAR | 32 |  | Lower Limit 2 |
| 17 | `FLAG` | CHAR | 1 |  | Single-Character Flag |
| 18 | `DEVLOC` | CHAR | 30 |  | Device Location |
| 19 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 20 | `KTOKL` | CHAR | 4 |  | Account class |
| 21 | `LASTYR_RESULT` | DEC | 10 |  | Last year result |
| 22 | `STAGRUVER` | CHAR | 2 |  | Statistics group for contract |
