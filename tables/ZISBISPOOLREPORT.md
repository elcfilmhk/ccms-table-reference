# ZISBISPOOLREPORT
**Description:** Table of spool for email count
**Total Fields:** 6
**Key Fields:** MANDT, ZZLETTERTYPE, PJIDENT, ZZSPTYPE

## Programs Using This Table
- `zisbi0176`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZLETTERTYPE` | CHAR | 30 | 🔑 | Letter type |
| 3 | `PJIDENT` | NUMC | 10 | 🔑 | Extended spool ID |
| 4 | `ZZSPTYPE` | CHAR | 20 | 🔑 | Spool type |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
