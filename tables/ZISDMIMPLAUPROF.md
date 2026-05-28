# ZISDMIMPLAUPROF
**Description:** Record for the reporting
**Total Fields:** 12
**Key Fields:** RUNDATE, SERNR, MASSREAD, BILLABLE, DATEFROM, TIMEFROM

## Programs Using This Table
- `zised0013`
- `zised0048`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `RUNDATE` | DATS | 8 | 🔑 | Field of type DATS |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `MASSREAD` | UNIT | 3 | 🔑 | Unit of measurement for meter reading |
| 4 | `BILLABLE` | CHAR | 1 | 🔑 | Single-Character Flag |
| 5 | `DATEFROM` | DATS | 8 | 🔑 | From-Date |
| 6 | `TIMEFROM` | TIMS | 6 | 🔑 | From-time |
| 7 | `VALUE` | CHAR | 31 |  | Profile value in interface |
| 8 | `ZCURRENT` | NUMC | 8 |  | Current |
| 9 | `VOLTAGE` | NUMC | 8 |  | Voltage |
| 10 | `THRESHOLD` | DEC | 9 |  | Threshold |
| 11 | `UPLOADDATE` | DATS | 8 |  | Field of type DATS |
| 12 | `UPLOADTIME` | TIMS | 6 |  | Field of type TIMS |
