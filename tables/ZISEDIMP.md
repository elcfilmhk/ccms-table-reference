# ZISEDIMP
**Description:** Temporary Import table for EDM
**Total Fields:** 13
**Key Fields:** MANDT, POINTOFDELIVERY, UNIT, AUTOKEY

## Programs Using This Table
- `zised0012`
- `zised0013`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `POINTOFDELIVERY` | CHAR | 50 | 🔑 | Point of delivery ID |
| 3 | `UNIT` | CHAR | 3 | 🔑 | Unit of measurement of profile value in general interface |
| 4 | `AUTOKEY` | NUMC | 10 | 🔑 | Numeric Character Field, Length 10 |
| 5 | `REFERENCENUMBER` | CHAR | 15 |  | Code for Identifying a Register |
| 6 | `DATEFROM` | DATS | 8 |  | From-Date |
| 7 | `TIMEFROM` | TIMS | 6 |  | From-time |
| 8 | `FROMOFFSET` | CHAR | 3 |  | Offset for time difference |
| 9 | `DATETO` | DATS | 8 |  | To-Date |
| 10 | `TIMETO` | TIMS | 6 |  | To-Time |
| 11 | `TOOFFSET` | CHAR | 3 |  | Offset for time difference |
| 12 | `VALUE` | CHAR | 31 |  | Profile value in interface |
| 13 | `STATUS` | CHAR | 4 |  | Status of profile value in interface |
