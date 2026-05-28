# ZISDMADRINTRATE
**Description:** ADR Event incentive rate
**Total Fields:** 6
**Key Fields:** MANDT, EVENTNAME, DRCUSTNO, RATETYPE

## Programs Using This Table
- `zisdm0309`
- `zisdm0310_adr`
- `zisdm0356`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 4 | `RATETYPE` | CHAR | 20 | 🔑 | Incentive Rate Type |
| 5 | `RATE` | DEC | 16 |  | Unit Rate |
| 6 | `UNIT` | CHAR | 10 |  | Incentive Rate Unit |
