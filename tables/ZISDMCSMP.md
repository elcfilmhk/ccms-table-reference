# ZISDMCSMP
**Description:** Consumption Input
**Total Fields:** 17
**Key Fields:** MANDT, ANLAGE, SERNR

## Programs Using This Table
- `zisdm0209`
- `zisdm0209_ev`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Meter number |
| 4 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 5 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 6 | `MASSREAD` | UNIT | 3 |  | Unit of measurement for meter reading |
| 7 | `INTSIZEID` | CHAR | 4 |  | Interval Length ID |
| 8 | `TARIFART` | CHAR | 8 |  | Rate Type |
| 9 | `STARTDATE` | DATS | 8 |  | Date |
| 10 | `ENDDATE` | DATS | 8 |  | Date |
| 11 | `ONPEAKCSMP` | DEC | 13 |  | Consumption limit |
| 12 | `OFFPEAKCSMP` | DEC | 13 |  | Consumption limit |
| 13 | `SHOULDERCSMP` | DEC | 13 |  | Consumption limit |
| 14 | `ONPEAKDATE` | DATS | 8 |  | Date |
| 15 | `ONPEAKTIME` | TIMS | 6 |  | Time |
| 16 | `OFFPEAKDATE` | DATS | 8 |  | Date |
| 17 | `OFFPEAKTIME` | TIMS | 6 |  | Time |
