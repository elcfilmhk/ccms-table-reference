# ZISDMCONNOBJREL
**Description:** Connection object to release
**Total Fields:** 4
**Key Fields:** MANDT, RUNDATE, HAUS

## Programs Using This Table
- `zisdm0137`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | Date of Program Run |
| 3 | `HAUS` | CHAR | 30 | 🔑 | Connection Object |
| 4 | `PROCESSED` | CHAR | 1 |  | Process Flag |
