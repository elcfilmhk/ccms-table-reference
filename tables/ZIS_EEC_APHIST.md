# ZIS_EEC_APHIST
**Description:** FiT Approval Details
**Total Fields:** 8
**Key Fields:** MANDT, RE_APP_NO, PAST

## Programs Using This Table
- `ziscs0208`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RE_APP_NO` | CHAR | 12 | 🔑 | Notification No |
| 3 | `PAST` | CHAR | 1 | 🔑 | General Flag |
| 4 | `LAST_APPROVER` | CHAR | 12 |  | Name of person who approved data |
| 5 | `RE_AP_DATE` | DATS | 8 |  | Date of approval |
| 6 | `CAPACITY` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 7 | `AMOUNT` | CURR | 13 |  | Amount |
| 8 | `RATE` | DEC | 4 |  | FiT Rate |
