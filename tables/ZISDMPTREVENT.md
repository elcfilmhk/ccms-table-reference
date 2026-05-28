# ZISDMPTREVENT
**Description:** PTR Event
**Total Fields:** 11
**Key Fields:** MANDT, EVENT_START_DATE, EVENT_START_TIME

## Programs Using This Table
- `ziscs0334`
- `ziscs0713`
- `zisdm0280`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENT_START_DATE` | DATS | 8 | 🔑 | Event Start Date |
| 3 | `EVENT_START_TIME` | TIMS | 6 | 🔑 | Event Start Time |
| 4 | `EVENT_END_DATE` | DATS | 8 |  | Event End Date |
| 5 | `EVENT_END_TIME` | TIMS | 6 |  | Event End Time |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `ERTIM` | TIMS | 6 |  | Create Time |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 11 | `AETIM` | TIMS | 6 |  | Change Time |
