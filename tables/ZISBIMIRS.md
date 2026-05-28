# ZISBIMIRS
**Description:** Data extraction for MACS MIRS
**Total Fields:** 4
**Key Fields:** MANDT, PERIOD, KPIID

## Programs Using This Table
- `zisbi0001`
- `zisbi0063`
- `zisbi0082`
- `ziscs0085`
- `zisfi0130`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PERIOD` | CHAR | 6 | 🔑 | Period (MMYYYY) |
| 3 | `KPIID` | CHAR | 30 | 🔑 | KPI id |
| 4 | `FIGURE` | DEC | 14 |  | Figure |
