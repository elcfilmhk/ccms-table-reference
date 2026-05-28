# ZISFIDUNTHRES
**Description:** Dunning Threshold setting table
**Total Fields:** 14
**Key Fields:** MANDT, EFFECT_FROM, EFFECT_TO, MAHNV, SEQ

## Programs Using This Table
- `ziscs0308`
- `zisfi0005_dun`
- `zisfi0213`
- `zisfi0214`
- `zisfi0215`
- `zisfi0273`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EFFECT_FROM` | DATS | 8 | 🔑 | Effective From |
| 3 | `EFFECT_TO` | DATS | 8 | 🔑 | Effective To |
| 4 | `MAHNV` | CHAR | 2 | 🔑 | Dunning Procedure |
| 5 | `SEQ` | NUMC | 2 | 🔑 | Sequence No. |
| 6 | `THRESHOLD_AMT` | CURR | 13 |  | Dunning Threshold amount |
| 7 | `JIT` | NUMC | 3 |  | Just in Time |
| 8 | `STATUS` | CHAR | 1 |  | Status (A - add, D - delete) |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERZET` | TIMS | 6 |  | Entry time |
| 12 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 13 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 14 | `AEZET` | TIMS | 6 |  | Time last change was made |
