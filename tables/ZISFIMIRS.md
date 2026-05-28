# ZISFIMIRS
**Description:** Data extraction for MACS MIRS
**Total Fields:** 4
**Key Fields:** MANDT, PERIOD, KPIID

## Programs Using This Table
- `zisfi0084`
- `zisfi0084t`
- `zisfi0128`
- `zisfi0130`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PERIOD` | CHAR | 6 | 🔑 | Period (MMYYYY) |
| 3 | `KPIID` | CHAR | 30 | 🔑 | Key ID |
| 4 | `FIGURE` | DEC | 14 |  | Figure |
