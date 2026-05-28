# ZTABPROFVAL
**Description:** Profile Values in 30-Minute Intervals
**Total Fields:** 54
**Key Fields:** .INCLUDE, .INCLUDE, MANDT, PROFILE, VALUEDAY

## Programs Using This Table
- `zprof_upload`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 | 🔑 | Structure for Profile Value Key |
| 2 | `.INCLUDE` | &nbsp; | 0 | 🔑 | Profile Key |
| 3 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 4 | `PROFILE` | NUMC | 18 | 🔑 | Number of EDM Profile |
| 5 | `VALUEDAY` | DATS | 8 | 🔑 | Day of profile values |
| 6 | `.INCLUDE` | &nbsp; | 0 |  | Structure for 30-Minute Values |
| 7 | `VAL0000` | DEC | 16 |  | Profile value |
| 8 | `VAL0030` | DEC | 16 |  | Profile value |
| 9 | `VAL0100` | DEC | 16 |  | Profile value |
| 10 | `VAL0130` | DEC | 16 |  | Profile value |
| 11 | `VAL0200` | DEC | 16 |  | Profile value |
| 12 | `VAL0230` | DEC | 16 |  | Profile value |
| 13 | `VAL0300` | DEC | 16 |  | Profile value |
| 14 | `VAL0330` | DEC | 16 |  | Profile value |
| 15 | `VAL0400` | DEC | 16 |  | Profile value |
| 16 | `VAL0430` | DEC | 16 |  | Profile value |
| 17 | `VAL0500` | DEC | 16 |  | Profile value |
| 18 | `VAL0530` | DEC | 16 |  | Profile value |
| 19 | `VAL0600` | DEC | 16 |  | Profile value |
| 20 | `VAL0630` | DEC | 16 |  | Profile value |
| 21 | `VAL0700` | DEC | 16 |  | Profile value |
| 22 | `VAL0730` | DEC | 16 |  | Profile value |
| 23 | `VAL0800` | DEC | 16 |  | Profile value |
| 24 | `VAL0830` | DEC | 16 |  | Profile value |
| 25 | `VAL0900` | DEC | 16 |  | Profile value |
| 26 | `VAL0930` | DEC | 16 |  | Profile value |
| 27 | `VAL1000` | DEC | 16 |  | Profile value |
| 28 | `VAL1030` | DEC | 16 |  | Profile value |
| 29 | `VAL1100` | DEC | 16 |  | Profile value |
| 30 | `VAL1130` | DEC | 16 |  | Profile value |
| 31 | `VAL1200` | DEC | 16 |  | Profile value |
| 32 | `VAL1230` | DEC | 16 |  | Profile value |
| 33 | `VAL1300` | DEC | 16 |  | Profile value |
| 34 | `VAL1330` | DEC | 16 |  | Profile value |
| 35 | `VAL1400` | DEC | 16 |  | Profile value |
| 36 | `VAL1430` | DEC | 16 |  | Profile value |
| 37 | `VAL1500` | DEC | 16 |  | Profile value |
| 38 | `VAL1530` | DEC | 16 |  | Profile value |
| 39 | `VAL1600` | DEC | 16 |  | Profile value |
| 40 | `VAL1630` | DEC | 16 |  | Profile value |
| 41 | `VAL1700` | DEC | 16 |  | Profile value |
| 42 | `VAL1730` | DEC | 16 |  | Profile value |
| 43 | `VAL1800` | DEC | 16 |  | Profile value |
| 44 | `VAL1830` | DEC | 16 |  | Profile value |
| 45 | `VAL1900` | DEC | 16 |  | Profile value |
| 46 | `VAL1930` | DEC | 16 |  | Profile value |
| 47 | `VAL2000` | DEC | 16 |  | Profile value |
| 48 | `VAL2030` | DEC | 16 |  | Profile value |
| 49 | `VAL2100` | DEC | 16 |  | Profile value |
| 50 | `VAL2130` | DEC | 16 |  | Profile value |
| 51 | `VAL2200` | DEC | 16 |  | Profile value |
| 52 | `VAL2230` | DEC | 16 |  | Profile value |
| 53 | `VAL2300` | DEC | 16 |  | Profile value |
| 54 | `VAL2330` | DEC | 16 |  | Profile value |
