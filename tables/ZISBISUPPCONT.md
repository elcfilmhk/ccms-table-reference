# ZISBISUPPCONT
**Description:** Regular Bill Control Table
**Total Fields:** 8
**Key Fields:** MANDT, REGULAR_TYPE, RELEASE_DATE

## Programs Using This Table
- `zisbi0123`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REGULAR_TYPE` | CHAR | 1 | 🔑 | Regular Bill Type |
| 3 | `RELEASE_DATE` | DATS | 8 | 🔑 | Release Bill Suppression Date |
| 4 | `REMARK` | CHAR | 100 |  | Regular bill Remark |
| 5 | `UPDATE_DATE` | DATS | 8 |  | Date of Last Change |
| 6 | `UPDATE_TIME` | TIMS | 6 |  | Time of Change |
| 7 | `UPDATE_BY` | CHAR | 12 |  | Last Changed By |
| 8 | `DEL_FLAG` | CHAR | 1 |  | Deletion Flag |
