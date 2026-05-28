# ZBACBBTVOL
**Description:** Batch job result - data volume
**Total Fields:** 5
**Key Fields:** MANDT, JOBNAME, INDAT, INTIME

## Programs Using This Table
- `zbacbt600`
- `zisdm0040`
- `zrdm_us_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `JOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 3 | `INDAT` | DATS | 8 | 🔑 | Insert date |
| 4 | `INTIME` | TIMS | 6 | 🔑 | Insert time |
| 5 | `DVOL` | CHAR | 10 |  | Data Volume |
