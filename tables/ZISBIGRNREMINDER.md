# ZISBIGRNREMINDER
**Description:** Table of Green Bill Reminder Letter
**Total Fields:** 9
**Key Fields:** MANDT, ERDAT, OPBEL, VKONT

## Programs Using This Table
- `zisbi0153`
- `zisbi0154`
- `zisbi0158`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 3 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 7 | `EBILL_REMINDER` | CHAR | 2 |  | Green Bill Reminder |
| 8 | `PRINT_DATE` | DATS | 8 |  | Print Date |
| 9 | `PRINT_TIME` | TIMS | 6 |  | Print Time |
