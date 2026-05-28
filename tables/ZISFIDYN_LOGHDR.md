# ZISFIDYN_LOGHDR
**Description:** Dynamic Log Records Header
**Total Fields:** 12
**Key Fields:** MANDT, UUID_9999, TABNAME_9999

## Programs Using This Table
- `zisfi0283`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `UUID_9999` | RAW | 16 | 🔑 | Global Unique ID for table |
| 3 | `TABNAME_9999` | CHAR | 30 | 🔑 | Table Name |
| 4 | `SIDE_9999` | CHAR | 1 |  | Side for Dynamic Records |
| 5 | `ACTION_9999` | CHAR | 1 |  | Action for Dynamic Records |
| 6 | `STATUS_9999` | CHAR | 1 |  | Status for Dynamic Records |
| 7 | `ERNAM_9999` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `ERDAT_9999` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERZET_9999` | TIMS | 6 |  | Entry time |
| 10 | `AENAM_9999` | CHAR | 12 |  | Name of person who changed object |
| 11 | `AEDAT_9999` | DATS | 8 |  | Date of Last Change |
| 12 | `AEZET_9999` | TIMS | 6 |  | Time last change was made |
