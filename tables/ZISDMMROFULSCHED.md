# ZISDMMROFULSCHED
**Description:** MRO Fulfilment Scheduler
**Total Fields:** 11
**Key Fields:** MANDT, MRU, SMRD

## Programs Using This Table
- `zisdm0397`
- `zisdm0398`
- `zrmrd_fulfilment_day`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MRU` | CHAR | 8 | 🔑 | Meter reading unit |
| 3 | `SMRD` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 4 | `EXEC_START_DATE` | DATS | 8 |  | Execution Start Date |
| 5 | `EXEC_START_TIME` | TIMS | 6 |  | Execution Start Time |
| 6 | `EXEC_EXPIRY_DAY` | INT1 | 3 |  | Execution Expiry Day |
| 7 | `EXEC_EXPIRY_DATE` | DATS | 8 |  | Execution Expiry Date |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 11 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
