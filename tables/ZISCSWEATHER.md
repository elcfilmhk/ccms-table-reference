# ZISCSWEATHER
**Description:** Normal day/Severe weather control table
**Total Fields:** 7
**Key Fields:** MANDT, BIS, BISTIME

## Programs Using This Table
- `ziscs0139`
- `ziscs0140`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BIS` | DATS | 8 | 🔑 | Date at Which a Time Slice Expires |
| 3 | `BISTIME` | TIMS | 6 | 🔑 | Field of type TIMS |
| 4 | `CSWEATHER` | CHAR | 1 |  | Normal day/Severe Weather flag |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERZEIT` | TIMS | 6 |  | Time, at Which Record Was Added |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
