# ZISDMLPBMRUCHG
**Description:** MRU change record
**Total Fields:** 11
**Key Fields:** MANDT, ANLAGE, NEW_EFFDT

## Programs Using This Table
- `zisdm0210`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `NEW_EFFDT` | DATS | 8 | 🔑 | Effective date of new MRU |
| 4 | `ORI_MRU` | CHAR | 8 |  | Meter reading unit |
| 5 | `NEW_MRU` | CHAR | 8 |  | Meter reading unit |
| 6 | `REV_EFFDT` | DATS | 8 |  | Effective date of MRU reversal |
| 7 | `STATUS` | CHAR | 4 |  | Request Status |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 11 | `AEDAT` | DATS | 8 |  | Date of Last Change |
