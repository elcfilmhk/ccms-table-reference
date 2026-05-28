# ZISCSEML_CSV_HD
**Description:** Email Tracking Platform - CSV file header (Raw Strings)
**Total Fields:** 5
**Key Fields:** MANDT, COL_HEADER_ID

## Programs Using This Table
- `ziscs0478_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `COL_HEADER_ID` | INT4 | 10 | 🔑 | Natural number |
| 3 | `COL_HEADER_255` | CHAR | 255 |  | Header String - First 255 char for index |
| 4 | `COL_HEADER_STR` | CHAR | 1000 |  | Case-sensitive Text of 1000 length |
| 5 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
