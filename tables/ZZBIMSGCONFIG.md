# ZZBIMSGCONFIG
**Description:** BI Message Activation
**Total Fields:** 13
**Key Fields:** MANDT, TYPE, OFFIC_EX, FROM_DATE

## Programs Using This Table
- `zisbi0257`
- `zisfi0310b`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TYPE` | CHAR | 10 | 🔑 | Message Type |
| 3 | `OFFIC_EX` | CHAR | 35 | 🔑 | External ID of Branch or Agent |
| 4 | `FROM_DATE` | DATS | 8 | 🔑 | Valid From Date |
| 5 | `TO_DATE` | DATS | 8 |  | Valid To Date |
| 6 | `GROUPING` | CHAR | 10 |  | Message Grouping |
| 7 | `ACTIVE` | CHAR | 1 |  | Active |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERZET` | TIMS | 6 |  | Entry time |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 12 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 13 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
