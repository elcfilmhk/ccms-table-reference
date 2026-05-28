# ZISCS_GS_CHK
**Description:** Government Subsidy Termination Check (All figure)
**Total Fields:** 15
**Key Fields:** MANDT, REFMTH, RUNDT, VKONT

## Programs Using This Table
- `ziscs0360`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REFMTH` | DATS | 8 | 🔑 | Entitlement ref month |
| 3 | `RUNDT` | DATS | 8 | 🔑 | Batch Run Date |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `ENT_EXIST` | CHAR | 1 |  | Current Entitement exists |
| 6 | `LAST_EXIST` | CHAR | 1 |  | Last Month balance exists |
| 7 | `CURR_EXIST` | CHAR | 1 |  | Current Month balance exists |
| 8 | `BALSUBS` | CURR | 13 |  | Entitlement subsidy balance |
| 9 | `CPUDT` | DATS | 8 |  | Date of entry |
| 10 | `CPUTM` | TIMS | 6 |  | Time of Entry |
| 11 | `RPZDAT` | DATS | 8 |  | Report zero (balance zero during reporting) batch date |
| 12 | `RPZIND` | CHAR | 2 |  | Entitlement report zero indicator |
| 13 | `CREATE_DATE` | DATS | 8 |  | Creation date |
| 14 | `CREATE_TIME` | TIMS | 6 |  | Creation Time |
| 15 | `UPDATED` | CHAR | 1 |  | Updated Indicator |
