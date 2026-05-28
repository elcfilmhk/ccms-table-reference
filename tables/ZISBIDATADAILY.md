# ZISBIDATADAILY
**Description:** Data from BONB report - RBI78
**Total Fields:** 5
**Key Fields:** MANDT, BATCH_DATE, RPT_TYPE, KPIID

## Programs Using This Table
- `zisbi0042`
- `zisbi0042_ami`
- `zisbi0042_newfm`
- `zisbi0082`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCH_DATE` | DATS | 8 | 🔑 | Batch run date |
| 3 | `RPT_TYPE` | CHAR | 10 | 🔑 | Report type |
| 4 | `KPIID` | CHAR | 30 | 🔑 | KPI id |
| 5 | `FIGURE` | DEC | 14 |  | Figure |
