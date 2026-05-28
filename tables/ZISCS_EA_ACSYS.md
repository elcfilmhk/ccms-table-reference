# ZISCS_EA_ACSYS
**Description:** EA Major Air Conditioning System
**Total Fields:** 7
**Key Fields:** MANDT, MAJOR_AC_SYSTEM

## Programs Using This Table
- `ziscs0723`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MAJOR_AC_SYSTEM` | CHAR | 3 | 🔑 | Major Air Conditioning System |
| 3 | `DESCRIPTION` | CHAR | 100 |  | General Description |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 7 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
