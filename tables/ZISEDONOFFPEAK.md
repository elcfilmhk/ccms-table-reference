# ZISEDONOFFPEAK
**Description:** On peak and off peak hour specification
**Total Fields:** 5
**Key Fields:** MANDT, DATE_INDICATOR, START_TIME

## Programs Using This Table
- `zisdm0207`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATE_INDICATOR` | CHAR | 1 | 🔑 | 'W'-Working Day 'N'-Non-working Day |
| 3 | `START_TIME` | TIMS | 6 | 🔑 | Start time of the period |
| 4 | `END_TIME` | TIMS | 6 |  | End time of the period |
| 5 | `PEAK_INDICATOR` | CHAR | 10 |  | On Peak / Off Peak |
