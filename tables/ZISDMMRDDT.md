# ZISDMMRDDT
**Description:** MR Download temporary table (for parallel jobs)
**Total Fields:** 9
**Key Fields:** MANDT, RUNDATE, MRDTYPE, PROCID, PCNAME, SEQNO, RECID

## Programs Using This Table
- `zisdh0002`
- `zisdm0027`
- `zisdm0082`
- `zisdm0185`
- `zismd0035`
- `zismd0035_nov17`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | Date stamp |
| 3 | `MRDTYPE` | CHAR | 1 | 🔑 | Meter Read Download Type (Aperiodic / Periodic) |
| 4 | `PROCID` | NUMC | 5 | 🔑 | Process ID |
| 5 | `PCNAME` | CHAR | 10 | 🔑 | Streetwise Download filename by PC ID |
| 6 | `SEQNO` | NUMC | 6 | 🔑 | Consecutive sequence number used for multiple records |
| 7 | `RECID` | CHAR | 2 | 🔑 | Record ID |
| 8 | `DATA` | CHAR | 250 |  | Meter Read Download record data |
| 9 | `ROUTESEQ` | NUMC | 8 |  | Route sequence number for each record |
