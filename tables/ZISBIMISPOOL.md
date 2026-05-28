# ZISBIMISPOOL
**Description:** Custom table for Welcome E-mail Bounce Back Main Program
**Total Fields:** 5
**Key Fields:** MANDT, PJIDENT, ZZSPTYPE

## Programs Using This Table
- `zisbi0120`
- `zisbi0126`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PJIDENT` | NUMC | 10 | 🔑 | Extended spool ID |
| 3 | `ZZSPTYPE` | CHAR | 20 | 🔑 | Spool type |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
