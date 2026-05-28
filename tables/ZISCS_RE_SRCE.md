# ZISCS_RE_SRCE
**Description:** RE Technology/Source
**Total Fields:** 8
**Key Fields:** MANDT, RE_SOURCE

## Programs Using This Table
- `ziscs0507`
- `ziscs0515`
- `ziscs0519`
- `zrvee_report`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RE_SOURCE` | CHAR | 2 | 🔑 | RE Source |
| 3 | `DESCRIPTION` | CHAR | 30 |  | Description |
| 4 | `DESCRIPTION_CH` | CHAR | 80 |  | Description |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
