# ZISDMBULKMR
**Description:** Bulk MR report entries
**Total Fields:** 20
**Key Fields:** MANDT, ERNAM, ERDAT, SUCCESS, ABLBELNR

## Programs Using This Table
- `zisdm0110`
- `zisdm0246`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERNAM` | CHAR | 12 | 🔑 | Name of Person Who Created the Object |
| 3 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 4 | `SUCCESS` | CHAR | 1 | 🔑 | Success Message |
| 5 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 6 | `GERNR` | CHAR | 18 |  | Serial Number |
| 7 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 8 | `ZWFAKT` | DEC | 12 |  | Register factor |
| 9 | `ANLAGE` | CHAR | 10 |  | Installation |
| 10 | `LASTREADING` | DEC | 17 |  | Last Meter Reading |
| 11 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 12 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 13 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 14 | `READING` | DEC | 17 |  | Meter Reading |
| 15 | `ADATTATS` | DATS | 8 |  | Actual meter reading date |
| 16 | `ABLESER` | CHAR | 3 |  | Meter reader number |
| 17 | `ACTOR` | CHAR | 14 |  | Concatenated Identification (Type and ID) of Org.Objects |
| 18 | `MRTYPE` | CHAR | 2 |  | Meter reading type |
| 19 | `MRACTIVE` | CHAR | 1 |  | Meter reading active |
| 20 | `ERROR` | CHAR | 80 |  | Error log |
