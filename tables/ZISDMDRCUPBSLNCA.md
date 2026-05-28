# ZISDMDRCUPBSLNCA
**Description:** DR Customer load profile for calculatiing the Baselin by CA.
**Total Fields:** 12
**Key Fields:** MANDT, EVENTNAME, DRCUSTNO, VKONT, DAYSEQ, ZDATE, STARTTIME

## Programs Using This Table
- `zisdm0310_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `DAYSEQ` | NUMC | 3 | 🔑 | ADR Day Sequence Number |
| 6 | `ZDATE` | DATS | 8 | 🔑 | Date |
| 7 | `STARTTIME` | TIMS | 6 | 🔑 | Time |
| 8 | `ENDTIME` | TIMS | 6 |  | Time |
| 9 | `VALUE` | DEC | 31 |  | Profile value at application level |
| 10 | `TOTALVALUE` | DEC | 31 |  | Profile value at application level |
| 11 | `ISEVENTDAY` | CHAR | 1 |  | Y/N |
| 12 | `RANKING` | NUMC | 3 |  | ADR Baseline ranking |
