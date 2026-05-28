# ZISDMMONBILL_MS
**Description:** Temp Store data for DM monthly bill process - Master Sub
**Total Fields:** 15
**Key Fields:** MANDT, BATCH_RUN_DATE, MASTER_INST, SUB_INST, SERNR, ADATSOLL

## Programs Using This Table
- `zisdm0297`
- `zisdm0298`
- `zisdm0298_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCH_RUN_DATE` | DATS | 8 | 🔑 | Batch Run Date |
| 3 | `MASTER_INST` | CHAR | 10 | 🔑 | Installation |
| 4 | `SUB_INST` | CHAR | 10 | 🔑 | Installation |
| 5 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 6 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 7 | `MONTHLYBILL` | CHAR | 1 |  | Monthly bill |
| 8 | `INST_TYPE` | CHAR | 20 |  | Installation Type |
| 9 | `PID` | NUMC | 5 |  | Process ID |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 13 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 14 | `PROCESSED` | CHAR | 1 |  | Processed |
| 15 | `ERROR_MSG` | CHAR | 100 |  | Error Message |
