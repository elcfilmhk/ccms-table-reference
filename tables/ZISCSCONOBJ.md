# ZISCSCONOBJ
**Description:** Installation number for Job Allocation processing
**Total Fields:** 5
**Key Fields:** MANDT, HAUS, PID

## Programs Using This Table
- `ziscs0048`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HAUS` | CHAR | 30 | 🔑 | Connection Object |
| 3 | `PID` | NUMC | 5 | 🔑 | 5 Character Numeric NUMC |
| 4 | `VSTCNT` | NUMC | 8 |  | Counter for number of premise ID |
| 5 | `ZZAVG` | NUMC | 8 |  | Average Number |
