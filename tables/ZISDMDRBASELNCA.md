# ZISDMDRBASELNCA
**Description:** ADR Baseline Result table by CA
**Total Fields:** 14
**Key Fields:** MANDT, EVENTNAME, DRCUSTNO, VKONT, EVENTDATE, STARTTIME

## Programs Using This Table
- `zisdm0310_adr`
- `zisdm0328_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `EVENTDATE` | DATS | 8 | 🔑 | Event Date |
| 6 | `STARTTIME` | TIMS | 6 | 🔑 | Start Time |
| 7 | `ENDTIME` | TIMS | 6 |  | End Time |
| 8 | `BASELINE` | DEC | 31 |  | Baseline (kWh) |
| 9 | `ACTUAL` | DEC | 31 |  | Actual Demand (kWh) |
| 10 | `REDUCTION` | DEC | 31 |  | Qualified Demand Reduction (kWh) |
| 11 | `QUALIFIED` | DEC | 31 |  | Qualified (kWh) |
| 12 | `RATE` | DEC | 16 |  | Unit Rate |
| 13 | `INCENTIVE` | DEC | 16 |  | Incentive Payment |
| 14 | `PERCENT` | DEC | 3 |  | Percentage for ADR |
