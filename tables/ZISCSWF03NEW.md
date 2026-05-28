# ZISCSWF03NEW
**Description:** Alignment of Move-in Date table
**Total Fields:** 7
**Key Fields:** MANDT, EINZBELEG

## Programs Using This Table
- `ziscs0326`
- `zmoveindoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EINZBELEG` | CHAR | 12 | 🔑 | Consecutive number of move-in document |
| 3 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `UZEIT` | TIMS | 6 |  | Time |
| 7 | `STATUS` | CHAR | 1 |  | Alignment of Move-in Date WF status |
