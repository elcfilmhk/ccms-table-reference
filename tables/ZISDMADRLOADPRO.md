# ZISDMADRLOADPRO
**Description:** ADR Event Customer Meter Load Profile
**Total Fields:** 9
**Key Fields:** MANDT, EVENTNAME, DRCUSTNO, VKONT, SERNR, ZDATE, STARTTIME, ENDTIME

## Programs Using This Table
- `zisdm0310_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 6 | `ZDATE` | DATS | 8 | 🔑 | Date |
| 7 | `STARTTIME` | TIMS | 6 | 🔑 | Time |
| 8 | `ENDTIME` | TIMS | 6 | 🔑 | Time |
| 9 | `VALUE` | DEC | 31 |  | Profile value at application level |
