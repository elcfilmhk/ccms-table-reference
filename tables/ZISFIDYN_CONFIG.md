# ZISFIDYN_CONFIG
**Description:** Dynamic Log Configuration
**Total Fields:** 6
**Key Fields:** MANDT, TCODE, TABNAME

## Programs Using This Table
- `zisfi0283`
- `zisfi0284`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TCODE` | CHAR | 20 | 🔑 | Transaction Code |
| 3 | `TABNAME` | CHAR | 30 | 🔑 | Table Name |
| 4 | `SIDE` | CHAR | 1 |  | Side for Dynamic Records |
| 5 | `ONE_LEVEL_INPUT` | CHAR | 1 |  | '' - dual input, 'X' - One Level input |
| 6 | `TITLE` | CHAR | 70 |  | ABAP System Field: Title Line Content of Current Dynpro |
