# ZISBIBPGAH
**Description:** Custom Table for RBI11-Group Account Result(Total BP & GA)
**Total Fields:** 8
**Key Fields:** MANDT, UNIQUE_ID

## Programs Using This Table
- `zisbi0021`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `UNIQUE_ID` | NUMC | 4 | 🔑 | Unique ID |
| 3 | `PERIOD_MONTH` | CHAR | 3 |  | 3 Characters to represent month |
| 4 | `PERIOD_YEAR` | NUMC | 4 |  | Year for period |
| 5 | `TOTAL_BP` | INT4 | 10 |  | Total number of parent BP |
| 6 | `TOTAL_GA` | INT4 | 10 |  | Total number of Group Account |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
