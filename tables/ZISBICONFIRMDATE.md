# ZISBICONFIRMDATE
**Description:** Confirmation date
**Total Fields:** 8
**Key Fields:** MANDT, OBJECT_KEY

## Programs Using This Table
- `zisbi0014`
- `zisbi0014t`
- `zisbi0027`
- `zisdm0170`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJECT_KEY` | CHAR | 32 | 🔑 | Object key |
| 3 | `TCODE` | CHAR | 20 |  | Transaction Code |
| 4 | `REPID` | CHAR | 40 |  | ABAP Program: Current Master Program |
| 5 | `DATE_CONF` | DATS | 8 |  | Confirmation Date |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERUZEIT` | TIMS | 6 |  | Created At |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
