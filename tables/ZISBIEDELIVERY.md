# ZISBIEDELIVERY
**Description:** Spool table for e-Delivery
**Total Fields:** 7
**Key Fields:** MANDT, SPOOL_NO

## Programs Using This Table
- `zisbi0180`
- `zisfi0256`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SPOOL_NO` | NUMC | 10 | 🔑 | Extended spool ID |
| 3 | `LETTER_ID` | CHAR | 2 |  | Letter ID |
| 4 | `LETTER_TITLE` | CHAR | 30 |  | Letter Title |
| 5 | `SPOOL_TYPE` | CHAR | 20 |  | Spool type |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
