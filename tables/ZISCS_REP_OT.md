# ZISCS_REP_OT
**Description:** Log Report access - Output screen/files
**Total Fields:** 8
**Key Fields:** MANDT, REPORT_NAME, RUN_DT, RUN_USER, OUT_FILE_SEQ

## Programs Using This Table
- `ziscs0842`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_NAME` | CHAR | 40 | 🔑 | Report Name |
| 3 | `RUN_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `RUN_USER` | CHAR | 12 | 🔑 | User Name |
| 5 | `OUT_FILE_SEQ` | INT4 | 10 | 🔑 | Natural number |
| 6 | `ON_SCREEN` | CHAR | 1 |  | General Flag |
| 7 | `FILENAME` | CHAR | 255 |  | Char255 |
| 8 | `ROW_COUNT` | INT4 | 10 |  | Natural number |
