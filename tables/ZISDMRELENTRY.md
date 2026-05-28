# ZISDMRELENTRY
**Description:** JAP Release entry
**Total Fields:** 22
**Key Fields:** MANDT, SERNR, ZWNUMMER, EQUNR, ABLESGR, ADAT

## Programs Using This Table
- `zisdm0035`
- `zisdm0072`
- `zisdm0251`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 4 | `EQUNR` | CHAR | 18 | 🔑 | Equipment Number |
| 5 | `ABLESGR` | CHAR | 2 | 🔑 | Meter reading reason |
| 6 | `ADAT` | DATS | 8 | 🔑 | Meter reading date relevant to billing |
| 7 | `V_ZWSTAND` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 8 | `N_ZWSTAND` | DEC | 14 |  | Places After Decimal Point in the Meter Reading |
| 9 | `ABLBELNR` | CHAR | 20 |  | Internal ID for meter reading document |
| 10 | `ISTABLART` | CHAR | 2 |  | Meter reading type |
| 11 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 12 | `ANLAGE` | CHAR | 10 |  | Installation |
| 13 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 14 | `VKONTO` | CHAR | 12 |  | Contract Account Number |
| 15 | `STAGRUVER` | CHAR | 2 |  | Statistics group for contract |
| 16 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 17 | `KTOKL` | CHAR | 4 |  | Account class |
| 18 | `PRUEFPKT` | CHAR | 2 |  | Independent validation |
| 19 | `DURATION` | NUMC | 5 |  | 5 Character Numeric NUMC |
| 20 | `CONSUMPTION` | DEC | 13 |  | Consumption - Device Level |
| 21 | `PREV_CONSUMPTION` | DEC | 13 |  | Consumption - Device Level |
| 22 | `LASTYR_RESULT` | DEC | 10 |  | Last year result |
