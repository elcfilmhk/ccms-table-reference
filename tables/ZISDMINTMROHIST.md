# ZISDMINTMROHIST
**Description:** Interim MRO Creation History Table
**Total Fields:** 13
**Key Fields:** MANDT, MAININST, BEGABRPE, ENDABRPE, EFFECT_DATE

## Programs Using This Table
- `zisdm0338`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MAININST` | CHAR | 10 | 🔑 | Key of Primary Installation |
| 3 | `BEGABRPE` | DATS | 8 | 🔑 | Start of billing period |
| 4 | `ENDABRPE` | DATS | 8 | 🔑 | End of billing period |
| 5 | `EFFECT_DATE` | DATS | 8 | 🔑 | Effective Date |
| 6 | `FINAL` | CHAR | 1 |  | Final Read at PI |
| 7 | `INTERIM` | CHAR | 1 |  | Interim Read at PI |
| 8 | `ACTIVE` | CHAR | 1 |  | Active Record |
| 9 | `VERTRAG` | CHAR | 10 |  | Contract |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 13 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
