# ZISCS_EA_EMOITEM
**Description:** EMO Summary Item
**Total Fields:** 9
**Key Fields:** MANDT, EMO_SUM_ITEM

## Programs Using This Table
- `ziscs0723`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EMO_SUM_ITEM` | CHAR | 3 | 🔑 | EMO Summary Item |
| 3 | `DESCRIPTION` | CHAR | 100 |  | General Description |
| 4 | `CALCULATION` | CHAR | 50 |  | Text Field |
| 5 | `REMARKS` | CHAR | 50 |  | Text Field |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
