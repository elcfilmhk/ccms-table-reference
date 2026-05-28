# ZISDMMDMSCVINST
**Description:** Installation for new MDMS
**Total Fields:** 8
**Key Fields:** MANDT, ANLAGE, PROCESS_DATE

## Programs Using This Table
- `zismd0031`
- `zismd0032`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `PROCESS_DATE` | DATS | 8 | 🔑 | Field of type DATS |
| 4 | `PROCESSED` | CHAR | 1 |  | MDMS Processed |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
