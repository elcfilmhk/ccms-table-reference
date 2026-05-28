# ZCAPROFVAL30KTMP
**Description:** CA Load Profile Key Temporary table
**Total Fields:** 9
**Key Fields:** MANDT, DATUM, UZEIT, BATCH, DATEFROM, DATETO, TIMEFROM, TIMETO, VKONT

## Programs Using This Table
- `zisdm0380`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATUM` | DATS | 8 | 🔑 | Date |
| 3 | `UZEIT` | TIMS | 6 | 🔑 | Time |
| 4 | `BATCH` | NUMC | 2 | 🔑 | Batch No. |
| 5 | `DATEFROM` | DATS | 8 | 🔑 | From-Date |
| 6 | `DATETO` | DATS | 8 | 🔑 | To-Date |
| 7 | `TIMEFROM` | TIMS | 6 | 🔑 | From-time |
| 8 | `TIMETO` | TIMS | 6 | 🔑 | To-Time |
| 9 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
