# ZISDMDRHHPROFVAL
**Description:** Half Hour Load Profile Values
**Total Fields:** 30
**Key Fields:** MANDT, EVENTNAME, DRCUSTNO, PROFVALDAY

## Programs Using This Table
- `zisdm0310_adr`
- `zisdm0357`
- `zisdm0357_backup`
- `zisdm0359`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 4 | `PROFVALDAY` | DATS | 8 | 🔑 | Date |
| 5 | `VAL1100` | DEC | 31 |  | Profile value at application level |
| 6 | `VAL1130` | DEC | 31 |  | Profile value at application level |
| 7 | `VAL1200` | DEC | 31 |  | Profile value at application level |
| 8 | `VAL1230` | DEC | 31 |  | Profile value at application level |
| 9 | `VAL1300` | DEC | 31 |  | Profile value at application level |
| 10 | `VAL1330` | DEC | 31 |  | Profile value at application level |
| 11 | `VAL1400` | DEC | 31 |  | Profile value at application level |
| 12 | `VAL1430` | DEC | 31 |  | Profile value at application level |
| 13 | `VAL1500` | DEC | 31 |  | Profile value at application level |
| 14 | `VAL1530` | DEC | 31 |  | Profile value at application level |
| 15 | `VAL1600` | DEC | 31 |  | Profile value at application level |
| 16 | `VAL1630` | DEC | 31 |  | Profile value at application level |
| 17 | `VAL1700` | DEC | 31 |  | Profile value at application level |
| 18 | `VAL1730` | DEC | 31 |  | Profile value at application level |
| 19 | `VAL1800` | DEC | 31 |  | Profile value at application level |
| 20 | `VAL1830` | DEC | 31 |  | Profile value at application level |
| 21 | `VAL1900` | DEC | 31 |  | Profile value at application level |
| 22 | `VAL1930` | DEC | 31 |  | Profile value at application level |
| 23 | `VAL2000` | DEC | 31 |  | Profile value at application level |
| 24 | `VAL2030` | DEC | 31 |  | Profile value at application level |
| 25 | `VAL2100` | DEC | 31 |  | Profile value at application level |
| 26 | `VAL2130` | DEC | 31 |  | Profile value at application level |
| 27 | `TOTAL_VAL` | DEC | 31 |  | Profile value at application level |
| 28 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 29 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 30 | `ERZET` | TIMS | 6 |  | Entry time |
