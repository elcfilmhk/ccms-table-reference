# ZISDMEST_MTR_MAP
**Description:** Estimating Meter Mapping
**Total Fields:** 13
**Key Fields:** MANDT, NEW_METER, NEW_REG

## Programs Using This Table
- `zisdm0391`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `NEW_METER` | CHAR | 18 | 🔑 | Device |
| 3 | `NEW_REG` | NUMC | 3 | 🔑 | Register |
| 4 | `OLD_METER` | CHAR | 18 |  | Device |
| 5 | `OLD_REG` | NUMC | 3 |  | Register |
| 6 | `FACTOR` | DEC | 7 |  | Factor (%) 00000.xx |
| 7 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERZET` | TIMS | 6 |  | Entry time |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 12 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 13 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
