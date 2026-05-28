# ZISDMMONBILLTEMP
**Description:** Temp Store data for DM monthly bill process
**Total Fields:** 9
**Key Fields:** MANDT, BATCH_RUN_DATE, ANLAGE

## Programs Using This Table
- `zisdm0297`
- `zisdm0297_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCH_RUN_DATE` | DATS | 8 | 🔑 | Batch Run Date |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 5 | `MONTHLYBILL` | CHAR | 1 |  | Monthly bill |
| 6 | `INST_TYPE` | CHAR | 20 |  | Installation Type |
| 7 | `PID` | NUMC | 5 |  | Process ID |
| 8 | `PROCESSED` | CHAR | 1 |  | Processed |
| 9 | `ERROR_MSG` | CHAR | 100 |  | Error Message |
