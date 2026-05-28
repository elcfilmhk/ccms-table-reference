# ZISDMREHIL
**Description:** Custom table for report IV51/ IV05/06 Hi-Lo
**Total Fields:** 22
**Key Fields:** MANDT, GERNR, ZWNUMMER

## Programs Using This Table
- `zisdm0035`
- `zisdm0072`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 4 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 5 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 6 | `PREV_CONSUMPTION` | DEC | 13 |  | Consumption - Device Level |
| 7 | `CONSUMPTION` | DEC | 13 |  | Consumption - Device Level |
| 8 | `TEMP_VARIANCE` | CHAR | 32 |  | Variance |
| 9 | `CONS_VARIANCE` | CHAR | 32 |  | Variance |
| 10 | `UPPER1` | CHAR | 32 |  | Upper Limit 1 |
| 11 | `LOWER1` | CHAR | 32 |  | Lower Limit 1 |
| 12 | `UPPER2` | CHAR | 32 |  | Upper Limit 2 |
| 13 | `LOWER2` | CHAR | 32 |  | Lower Limit 2 |
| 14 | `FLAG` | CHAR | 1 |  | Single-Character Flag |
| 15 | `DEVLOC` | CHAR | 30 |  | Device Location |
| 16 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 17 | `KTOKL` | CHAR | 4 |  | Account class |
| 18 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 19 | `LASTYR_RESULT` | DEC | 10 |  | Last year result |
| 20 | `PRUEFPKT` | CHAR | 2 |  | Independent validation |
| 21 | `ZZDAYS` | NUMC | 5 |  | 5 Character Numeric NUMC |
| 22 | `STAGRUVER` | CHAR | 2 |  | Statistics group for contract |
