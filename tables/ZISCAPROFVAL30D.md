# ZISCAPROFVAL30D
**Description:** CA Load Profile (30 min) Delta
**Total Fields:** 10
**Key Fields:** MANDT, VKONT, .INCLUDE, DATEFROM, TIMEFROM, MASS

## Programs Using This Table
- `zisdm0380`
- `zisdm0381`
- `zisdm0382`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `.INCLUDE` | &nbsp; | 0 | 🔑 | Structure for From-Date |
| 4 | `DATEFROM` | DATS | 8 | 🔑 | From-Date |
| 5 | `TIMEFROM` | TIMS | 6 | 🔑 | From-time |
| 6 | `MASS` | UNIT | 3 | 🔑 | Unit of Measurement |
| 7 | `VALUE` | DEC | 22 |  | Profile Value 22(6) |
| 8 | `STATUS` | CHAR | 5 |  | Object status |
| 9 | `TOU` | CHAR | 1 |  | Time of Use |
| 10 | `TIMESTAMP` | DEC | 15 |  | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
