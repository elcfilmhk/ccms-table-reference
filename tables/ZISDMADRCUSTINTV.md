# ZISDMADRCUSTINTV
**Description:** ADR Event Customer Interval
**Total Fields:** 9
**Key Fields:** MANDT, EVENTNAME, DRCUSTNO, STARTTIME

## Programs Using This Table
- `zisdm0309`
- `zisdm0310_adr`
- `zisdm0356`
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
| 4 | `STARTTIME` | TIMS | 6 | 🔑 | Time |
| 5 | `ENDTIME` | TIMS | 6 |  | Time |
| 6 | `TARGETCUT` | DEC | 8 |  | ADR Max/Target Cut value |
| 7 | `MAXCUT` | DEC | 8 |  | ADR Max/Target Cut value |
| 8 | `MAXCUTRATE` | DEC | 8 |  | ADR Max/Target Cut value |
| 9 | `UNIT` | UNIT | 3 |  | Unit of measurement for meter reading |
