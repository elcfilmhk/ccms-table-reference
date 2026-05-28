# ZISBIHICOMPCRI
**Description:** ZISBIHICOMPCRI
**Total Fields:** 9
**Key Fields:** MANDT, RATE_CAT_DESC, AB, BIS

## Programs Using This Table
- `zisbi0145`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RATE_CAT_DESC` | CHAR | 4 | 🔑 | Rate Cat. in short form |
| 3 | `AB` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 4 | `BIS` | DATS | 8 | 🔑 | Date at Which a Time Slice Expires |
| 5 | `X_PERC` | CURR | 13 |  | High Consumption - X Percentage |
| 6 | `Y_CONSECUTIVE` | CURR | 13 |  | High Consumption - Y Consecutive |
| 7 | `THIS_CONSUMP` | CURR | 13 |  | High Consumption - Z (This Consumption) |
| 8 | `LAST_CONSUMP` | CURR | 13 |  | High Consumption - W (Last Consumption) |
| 9 | `REMARK` | CHAR | 100 |  | Remark for high consumption table |
