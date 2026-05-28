# ZISBI_PM_AREA
**Description:** Segmentation - Promotion Area Config
**Total Fields:** 6
**Key Fields:** MANDT, LOGNUM

## Programs Using This Table
- `zisbi0229`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LOGNUM` | NUMC | 8 | 🔑 | Log number |
| 3 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 4 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 5 | `AREA` | CHAR | 20 |  | Promotion Area |
| 6 | `NO_OF_BLOCK` | NUMC | 3 |  | No. of block |
