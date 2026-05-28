# ZISDMMRDRP
**Description:** MR Download report table (for parallel jobs)
**Total Fields:** 7
**Key Fields:** MANDT, REPDATE, MRDTYPE, TYPE, PID, SEQNO

## Programs Using This Table
- `zisdh0002`
- `zisdm0027`
- `zisdm0082`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPDATE` | DATS | 8 | 🔑 | Date stamp |
| 3 | `MRDTYPE` | CHAR | 1 | 🔑 | Meter Read Download Type (Aperiodic / Periodic) |
| 4 | `TYPE` | CHAR | 1 | 🔑 | Streetwise Download Report type |
| 5 | `PID` | NUMC | 5 | 🔑 | Process ID |
| 6 | `SEQNO` | NUMC | 6 | 🔑 | Consecutive sequence number used for multiple records |
| 7 | `CONTENT` | CHAR | 255 |  | Context string |
