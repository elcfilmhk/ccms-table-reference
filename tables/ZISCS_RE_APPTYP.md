# ZISCS_RE_APPTYP
**Description:** RE Connection/FiT Application Type
**Total Fields:** 7
**Key Fields:** MANDT, APP_TYPE

## Programs Using This Table
- `ziscs0507`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `APP_TYPE` | CHAR | 2 | 🔑 | Application Type |
| 3 | `DESCRIPTION` | CHAR | 30 |  | Description |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 7 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
