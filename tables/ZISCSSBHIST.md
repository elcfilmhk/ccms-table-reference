# ZISCSSBHIST
**Description:** Custom table to store the monthly opt out history
**Total Fields:** 9
**Key Fields:** MANDT, FROM_DATE, TO_DATE

## Programs Using This Table
- `ziscs0263`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FROM_DATE` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 3 | `TO_DATE` | DATS | 8 | 🔑 | Date at Which a Time Slice Expires |
| 4 | `DT` | INT4 | 10 |  | Natural number |
| 5 | `GST` | INT4 | 10 |  | Natural number |
| 6 | `HAND_DT` | INT4 | 10 |  | Natural number |
| 7 | `HAND_GST` | INT4 | 10 |  | Natural number |
| 8 | `OTHER_DT` | INT4 | 10 |  | Natural number |
| 9 | `OTHER_GST` | INT4 | 10 |  | Natural number |
