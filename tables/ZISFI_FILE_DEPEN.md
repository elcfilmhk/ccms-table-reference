# ZISFI_FILE_DEPEN
**Description:** File Dependency Transaction
**Total Fields:** 8
**Key Fields:** MANDT, PRDATE, CHANNEL

## Programs Using This Table
- `zisfi0066`
- `zisfi0333`
- `zrfkkpcds`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PRDATE` | DATS | 8 | 🔑 | Payment Run/Registration File Date |
| 3 | `CHANNEL` | CHAR | 35 | 🔑 | Payment Channel |
| 4 | `FILENAME` | CHAR | 64 |  | Payment/Registration File Name |
| 5 | `STATUS` | CHAR | 1 |  | File Generation Status (Y/Blank) |
| 6 | `REDATE` | DATS | 8 |  | Return/Response File Date |
| 7 | `REFILENAME` | CHAR | 64 |  | Return/Response File Name |
| 8 | `RESTATUS` | CHAR | 1 |  | Return/Response File Status (Y/Blank) |
