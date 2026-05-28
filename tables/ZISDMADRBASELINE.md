# ZISDMADRBASELINE
**Description:** ADR Baseline Result table
**Total Fields:** 12
**Key Fields:** MANDT, EVENTNAME, DRCUSTNO, EVENTDATE, STARTTIME

## Programs Using This Table
- `ziscs_drevent_del`
- `zisdm0310_adr`
- `zisdm0311_adr`
- `zisdm0328_adr`
- `zisdm0369_candi`
- `zisdm0371`
- `zisfi0249`
- `zisfi0249_dnld`
- `zisfi0250`
- `zisfi0250_backup`
- `zisfi0250_backup_1`
- `zisfi0251`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 4 | `EVENTDATE` | DATS | 8 | 🔑 | Event Date |
| 5 | `STARTTIME` | TIMS | 6 | 🔑 | Start Time |
| 6 | `ENDTIME` | TIMS | 6 |  | End Time |
| 7 | `BASELINE` | DEC | 31 |  | Baseline (kWh) |
| 8 | `ACTUAL` | DEC | 31 |  | Actual Demand (kWh) |
| 9 | `REDUCTION` | DEC | 31 |  | Qualified Demand Reduction (kWh) |
| 10 | `QUALIFIED` | DEC | 31 |  | Qualified (kWh) |
| 11 | `RATE` | DEC | 16 |  | Unit Rate |
| 12 | `INCENTIVE` | DEC | 16 |  | Incentive Payment |
