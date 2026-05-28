# ZVARI
**Description:** Custom Variant Master
**Total Fields:** 11
**Key Fields:** MANDT, REPORT, VARIANT

## Programs Using This Table
- `zisdm0406`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT` | CHAR | 40 | 🔑 | ABAP: Program Name in Variant Key |
| 3 | `VARIANT` | CHAR | 14 | 🔑 | ABAP: Name of variant (without program name) |
| 4 | `VTEXT` | CHAR | 30 |  | Program variant short text |
| 5 | `PROTECTED` | CHAR | 1 |  | Variant protected |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERZET` | TIMS | 6 |  | Entry time |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 10 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 11 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
