# ZISBI_GS_DAILY
**Description:** Daily Report Summary
**Total Fields:** 11
**Key Fields:** MANDT, RUNDT, BUDAT, SCHEME

## Programs Using This Table
- `zisfi0314`
- `zisfi0316`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDT` | DATS | 8 | 🔑 | Batch run date |
| 3 | `BUDAT` | DATS | 8 | 🔑 | Posting Date |
| 4 | `SCHEME` | CHAR | 6 | 🔑 | Scheme |
| 5 | `CPUDT` | DATS | 8 |  | Date of Process |
| 6 | `CPUTM` | TIMS | 6 |  | Time of Process |
| 7 | `GS` | CURR | 13 |  | Gov Subsidy |
| 8 | `GS_REV` | CURR | 13 |  | Gov Subsidy Reversal |
| 9 | `GS_NET` | CURR | 13 |  | Net Gov Subsidy |
| 10 | `CREATION_DT` | DATS | 8 |  | Creation Date |
| 11 | `CREATION_TM` | TIMS | 6 |  | Creation Time |
