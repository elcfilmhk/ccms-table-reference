# ZISFIAMTRANGE
**Description:** Amount ranges
**Total Fields:** 5
**Key Fields:** MANDT, RANGE_NR

## Programs Using This Table
- `zisfi0038`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RANGE_NR` | NUMC | 2 | 🔑 | Range number |
| 3 | `FR_AMOUNT` | CURR | 17 |  | From amount |
| 4 | `TO_AMOUNT` | CURR | 17 |  | To amount |
| 5 | `TEXT` | CHAR | 30 |  | Range description |
