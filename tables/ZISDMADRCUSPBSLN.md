# ZISDMADRCUSPBSLN
**Description:** Event Customer load profile for calculatiing the Baseline.
**Total Fields:** 11
**Key Fields:** MANDT, EVENTNAME, DRCUSTNO, DAYSEQ, ZDATE, STARTTIME

## Programs Using This Table
- `zisdm0310_adr`
- `zisdm0369_candi`
- `zisfi0249`
- `zisfi0250_backup`
- `zisfi0250_backup_1`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 4 | `DAYSEQ` | NUMC | 3 | 🔑 | ADR Day Sequence Number |
| 5 | `ZDATE` | DATS | 8 | 🔑 | Date |
| 6 | `STARTTIME` | TIMS | 6 | 🔑 | Time |
| 7 | `ENDTIME` | TIMS | 6 |  | Time |
| 8 | `VALUE` | DEC | 31 |  | Profile value at application level |
| 9 | `TOTALVALUE` | DEC | 31 |  | Profile value at application level |
| 10 | `ISEVENTDAY` | CHAR | 1 |  | Y/N |
| 11 | `RANKING` | NUMC | 3 |  | ADR Baseline ranking |
