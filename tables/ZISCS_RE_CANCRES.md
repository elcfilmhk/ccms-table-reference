# ZISCS_RE_CANCRES
**Description:** RE Application Cancellation Reason
**Total Fields:** 8
**Key Fields:** MANDT, CANC_REASON

## Programs Using This Table
- `ziscs0838`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CANC_REASON` | CHAR | 2 | 🔑 | RE Application Cancellation Reason |
| 3 | `DESCRIPTION` | CHAR | 100 |  | General Description |
| 4 | `REM_MANDATORY` | CHAR | 1 |  | Checkbox |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
