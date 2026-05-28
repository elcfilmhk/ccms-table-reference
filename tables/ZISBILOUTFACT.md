# ZISBILOUTFACT
**Description:** Leftout factor
**Total Fields:** 4
**Key Fields:** MANDT, AB

## Programs Using This Table
- `zisbi0062_1`
- `zisbi0062_1t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AB` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 3 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 4 | `FACTOR` | DEC | 8 |  | Factor |
