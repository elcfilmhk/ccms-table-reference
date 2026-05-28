# ZISBIHICOMPEXLST
**Description:** High Consumption exclusion account list table
**Total Fields:** 6
**Key Fields:** MANDT, LISTTYPE, VKONT

## Programs Using This Table
- `zisbi0146`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LISTTYPE` | CHAR | 1 | 🔑 | High Consumption List Type (Inclusive / Exclusive) |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 5 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 6 | `REMARK` | CHAR | 100 |  | Remark for high consumption table |
