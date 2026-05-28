# ZISDMAMASSDELLOG
**Description:** Aperiodic Meter Reading Order Assignment Deletion Log
**Total Fields:** 15
**Key Fields:** MANDT, SEQ_NO, GERNR, ADATSOLL

## Programs Using This Table
- `zisdm0151`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SEQ_NO` | NUMC | 4 | 🔑 | Sequence Num. |
| 3 | `GERNR` | CHAR | 18 | 🔑 | Device |
| 4 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 5 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 6 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 7 | `ASSIGN_READER` | CHAR | 6 |  | Assigned Meter Reader |
| 8 | `ASSIGN_DATE` | DATS | 8 |  | Assigned Meter Reading Date |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 12 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 13 | `DOWNLOADED` | CHAR | 1 |  | Downloaded |
| 14 | `DEL_DATE` | DATS | 8 |  | Date on Which the Record Was Deleted |
| 15 | `DEL_BY` | CHAR | 12 |  | User who Deleted the Record |
