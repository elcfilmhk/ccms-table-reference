# ZISDMCUSTCONT
**Description:** Customer Contract for force check read
**Total Fields:** 6
**Key Fields:** MANDT, RUNDATE, ANLAGE, SERNR, ADATSOLL, ABLESGR

## Programs Using This Table
- `zisdm0050`
- `zisdm0300`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | Field of type DATS |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Device |
| 5 | `ADATSOLL` | DATS | 8 | 🔑 | Field of type DATS |
| 6 | `ABLESGR` | CHAR | 2 | 🔑 | Meter reading reason |
