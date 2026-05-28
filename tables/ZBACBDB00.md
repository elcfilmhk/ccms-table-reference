# ZBACBDB00
**Description:** IXOS Data Archival: BCAS Quarters
**Total Fields:** 6
**Key Fields:** MANDT, QUARTER

## Programs Using This Table
- `zbacbdb01`
- `zbacbdb11`
- `zbacbdb51`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `QUARTER` | CHAR | 1 | 🔑 | IXOS: Data Archival: BCAS Quarter |
| 3 | `LOW_DAY` | CHAR | 2 |  | Low Date: Day |
| 4 | `LOW_MONTH` | CHAR | 2 |  | Low Date: Month |
| 5 | `HIGH_DAY` | CHAR | 2 |  | High Date: Day |
| 6 | `HIGH_MONTH` | CHAR | 2 |  | High Date: Month |
