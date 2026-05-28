# ZISCEL_STATUS
**Description:** Concessionary audit status
**Total Fields:** 3
**Key Fields:** MANDT, STAUS

## Programs Using This Table
- `ziscs0420`
- `ziscs0435`
- `ziscs0441`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `STAUS` | CHAR | 2 | 🔑 | Audit status |
| 3 | `DESCR` | CHAR | 30 |  | Concessionary audit status description |
