# ZISDHUPTRG
**Description:** Trigger for processing MR results data
**Total Fields:** 10
**Key Fields:** MANDT, DATE_UPLOAD

## Programs Using This Table
- `zisdh0005`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATE_UPLOAD` | DATS | 8 | 🔑 | Date |
| 3 | `TRIGGER_UPLOAD` | CHAR | 1 |  | Trigger Upload flag |
| 4 | `.INCLUDE` | &nbsp; | 0 |  | Administrative data |
| 5 | `CREATION_DATE` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `CREATION_TIME` | TIMS | 6 |  | Creation time |
| 7 | `CREATED_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `CHANGE_DATE` | DATS | 8 |  | Date of Last Change |
| 9 | `CHANGE_TIME` | TIMS | 6 |  | Change time |
| 10 | `CHANGE_BY` | CHAR | 12 |  | Name of person who changed object |
