# ZISDMJOALL
**Description:** Installation number for Job Allocation processing
**Total Fields:** 5
**Key Fields:** MANDT, ANLAGE, PID

## Programs Using This Table
- `zisdm0035`
- `zisdm0072`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `PID` | NUMC | 5 | 🔑 | 5 Character Numeric NUMC |
| 4 | `REGCNT` | NUMC | 8 |  | Register Counter |
| 5 | `ZZAVG` | NUMC | 8 |  | Average Number |
