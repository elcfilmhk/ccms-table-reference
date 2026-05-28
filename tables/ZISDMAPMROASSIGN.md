# ZISDMAPMROASSIGN
**Description:** Aperiodic MRO Assignment
**Total Fields:** 12
**Key Fields:** MANDT, GERNR, ADATSOLL

## Programs Using This Table
- `zisdm0025`
- `zisdm0151`
- `zisdm0152`
- `zisdm0252`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GERNR` | CHAR | 18 | 🔑 | Device |
| 3 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 4 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 5 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 6 | `ASSIGN_READER` | CHAR | 6 |  | Assigned Meter Reader |
| 7 | `ASSIGN_DATE` | DATS | 8 |  | Assigned Meter Reading Date |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 11 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 12 | `DOWNLOADED` | CHAR | 1 |  | Downloaded |
