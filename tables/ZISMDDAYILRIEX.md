# ZISMDDAYILRIEX
**Description:** Store the meter list not generate into the daily RI schedule
**Total Fields:** 5
**Key Fields:** MANDT, SERNR

## Programs Using This Table
- `zisdm0185`
- `zismd0035`
- `zismd0035_nov17`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `BIDAILY_ODD` | CHAR | 1 |  | Bi-daily (Mon, Wed, Fri) |
| 4 | `BIDAILY_EVEN` | CHAR | 1 |  | Bi-daily (Sun, Tue, Thu) |
| 5 | `WEEKLY` | CHAR | 1 |  | Weekly |
