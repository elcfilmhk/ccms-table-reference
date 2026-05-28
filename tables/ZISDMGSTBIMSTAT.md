# ZISDMGSTBIMSTAT
**Description:** GST Bi-monthly statistics
**Total Fields:** 4
**Key Fields:** MANDT, STAT_TYPE, STAT_DATE

## Programs Using This Table
- `zisdm0301`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `STAT_TYPE` | CHAR | 1 | 🔑 | GST Bi-Monthly Statistic Type |
| 3 | `STAT_DATE` | DATS | 8 | 🔑 | Field of type DATS |
| 4 | `NO_OF_INSTALL` | CHAR | 18 |  | Device |
