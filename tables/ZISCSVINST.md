# ZISCSVINST
**Description:** Move-out and disconnection date of vacant installations
**Total Fields:** 4
**Key Fields:** MANDT, ANLAGE

## Programs Using This Table
- `zinstln`
- `ziscs0033`
- `ziscs0037`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 4 | `ACTDATE` | DATS | 8 |  | Disconnection Date |
