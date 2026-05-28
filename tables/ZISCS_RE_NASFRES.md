# ZISCS_RE_NASFRES
**Description:** RE App SO Network Assessment Failure Reason
**Total Fields:** 10
**Key Fields:** MANDT, NASF_REASON

## Programs Using This Table
- `ziscs0838`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `NASF_REASON` | CHAR | 2 | 🔑 | NASF Reason |
| 3 | `SEQUENCE` | NUMC | 2 |  | Sequence No. |
| 4 | `DESCRIPTION` | CHAR | 100 |  | General Description |
| 5 | `REM_MANDATORY` | CHAR | 1 |  | Checkbox |
| 6 | `INACTIVE` | CHAR | 1 |  | Checkbox |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 10 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
