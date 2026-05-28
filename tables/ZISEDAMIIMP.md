# ZISEDAMIIMP
**Description:** Temporary Import table for SMP Contingency Profile Import
**Total Fields:** 12
**Key Fields:** MANDT, SERNR, UNIT, AUTOKEY

## Programs Using This Table
- `zised0057`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `UNIT` | CHAR | 10 | 🔑 | Unit of measurement of profile value in general interface |
| 4 | `AUTOKEY` | NUMC | 10 | 🔑 | Numeric Character Field, Length 10 |
| 5 | `DATEFROM` | DATS | 8 |  | From-Date |
| 6 | `TIMEFROM` | TIMS | 6 |  | From-time |
| 7 | `FROMOFFSET` | CHAR | 3 |  | Offset for time difference |
| 8 | `DATETO` | DATS | 8 |  | To-Date |
| 9 | `TIMETO` | TIMS | 6 |  | To-Time |
| 10 | `TOOFFSET` | CHAR | 3 |  | Offset for time difference |
| 11 | `VALUE` | CHAR | 31 |  | Profile value in interface |
| 12 | `STATUS` | CHAR | 4 |  | Status of profile value in interface |
