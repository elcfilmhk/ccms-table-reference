# ZISDMREPT
**Description:** Report for RMTM (HKVA and Low Consumption)
**Total Fields:** 17
**Key Fields:** MANDT, RPT_TYPE, VKONT, GERNR, DEVLOC, ADAT, AUFNR

## Programs Using This Table
- `zisdm0035`
- `zisdm0065`
- `zisdm0067`
- `zisdm0068`
- `zisdm0072`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RPT_TYPE` | CHAR | 4 | 🔑 | Not More Closely Defined Area, Possibly Used for Patchlevels |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `GERNR` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `DEVLOC` | CHAR | 30 | 🔑 | Device Location |
| 6 | `ADAT` | DATS | 8 | 🔑 | Meter reading date relevant to billing |
| 7 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 8 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 9 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 10 | `ON_VZWSTAND` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 11 | `OFF_VZWSTAND` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 12 | `SEMI_VZWSTAND` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 13 | `HIGH_VZWSTAND` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 14 | `REGIOGROUP` | CHAR | 8 |  | Regional structure grouping |
| 15 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 16 | `STAGRUVER` | CHAR | 2 |  | Statistics group for contract |
| 17 | `ZZLASTMTRCHK` | DATS | 8 |  | Last Meter Checked Date |
