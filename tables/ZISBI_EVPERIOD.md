# ZISBI_EVPERIOD
**Description:** EV TOU Peak periods (Predefined time blocks)
**Total Fields:** 5
**Key Fields:** MANDT, EFFECTIVE_FROM, EFFECTIVE_TO, BLOCK_NAME

## Programs Using This Table
- `zisdm0209_ev`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EFFECTIVE_FROM` | DATS | 8 | 🔑 | Effective from date for block |
| 3 | `EFFECTIVE_TO` | DATS | 8 | 🔑 | Effective to date for block |
| 4 | `BLOCK_NAME` | CHAR | 10 | 🔑 | Block name |
| 5 | `BLOCK_PERIOD` | CHAR | 8 |  | Block Period-On peak/off peak/shoulder peak period |
