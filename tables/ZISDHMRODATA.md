# ZISDHMRODATA
**Description:** Click MRO Download table (for parallel jobs)
**Total Fields:** 9
**Key Fields:** MANDT, RUNDATE, BATCH, MRDTYPE, PROCID, ANLAGE, ABLESGR, ADATSOLL, GERNR

## Programs Using This Table
- `zisdh0021`
- `zisdh0022`
- `zisdh0024`
- `zisdm0252`
- `zisdm0407`
- `zrdm_wd_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | Batch run date |
| 3 | `BATCH` | NUMC | 2 | 🔑 | Batch No |
| 4 | `MRDTYPE` | CHAR | 1 | 🔑 | Meter Read Download Type (Aperiodic / Periodic) |
| 5 | `PROCID` | NUMC | 5 | 🔑 | Process ID |
| 6 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 7 | `ABLESGR` | CHAR | 2 | 🔑 | Meter reading reason |
| 8 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 9 | `GERNR` | CHAR | 18 | 🔑 | Device |
