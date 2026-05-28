# ZISBIMFASWITCH
**Description:** Maintain ON/OFF switch for MFA
**Total Fields:** 10
**Key Fields:** MANDT, FROM_DATE

## Programs Using This Table
- `zisbi0237`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FROM_DATE` | DATS | 8 | 🔑 | Valid From Date |
| 3 | `TO_DATE` | DATS | 8 |  | Valid To Date |
| 4 | `SWITCH` | CHAR | 1 |  | MFA Switch (ON/OFF) |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERZET` | TIMS | 6 |  | Entry time |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 9 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 10 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
