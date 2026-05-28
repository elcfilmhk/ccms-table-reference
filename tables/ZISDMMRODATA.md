# ZISDMMRODATA
**Description:** MR Download temporary table (for parallel jobs)
**Total Fields:** 10
**Key Fields:** MANDT, RUNDATE, BATCH, MRDTYPE, PROCID, PCNAME, SEQNO, RECID, DATA

## Programs Using This Table
- `zisdm0082`
- `zisdm0185`
- `zisdm0252`
- `zismd0035`
- `zismd0035_nov17`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | Date stamp |
| 3 | `BATCH` | NUMC | 2 | 🔑 | Batch No |
| 4 | `MRDTYPE` | CHAR | 1 | 🔑 | Meter Read Download Type (Aperiodic / Periodic) |
| 5 | `PROCID` | NUMC | 5 | 🔑 | Process ID |
| 6 | `PCNAME` | CHAR | 10 | 🔑 | Streetwise Download filename by PC ID |
| 7 | `SEQNO` | NUMC | 6 | 🔑 | Consecutive sequence number used for multiple records |
| 8 | `RECID` | CHAR | 2 | 🔑 | Record ID |
| 9 | `DATA` | CHAR | 250 | 🔑 | Meter Read Download record data |
| 10 | `ROUTESEQ` | NUMC | 8 |  | Route sequence number for each record |
