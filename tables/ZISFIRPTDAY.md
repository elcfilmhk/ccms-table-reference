# ZISFIRPTDAY
**Description:** FI customize table for reporting day range
**Total Fields:** 7
**Key Fields:** MANDT, REPID, ZZTRIGGER

## Programs Using This Table
- `zisfi0199`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 3 | `ZZTRIGGER` | CHAR | 1 | 🔑 | Triggering Event |
| 4 | `ZZRPTRANGE` | INT4 | 10 |  | FI Reporting date range |
| 5 | `DESCRIPTION` | CHAR | 50 |  | Description |
| 6 | `AENAME` | CHAR | 12 |  | Last Changed By |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
