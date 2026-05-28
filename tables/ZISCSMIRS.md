# ZISCSMIRS
**Description:** Data extraction for MACS MIRS
**Total Fields:** 4
**Key Fields:** MANDT, PERIOD, KPIID

## Programs Using This Table
- `ziscs0016`
- `ziscs0018`
- `ziscs0021`
- `ziscs0026`
- `ziscs0026a`
- `ziscs0027`
- `ziscs0074`
- `zisdm0420`
- `zisfi0130`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PERIOD` | CHAR | 6 | 🔑 | Period |
| 3 | `KPIID` | CHAR | 30 | 🔑 | KPI id |
| 4 | `FIGURE` | DEC | 14 |  | Figure |
