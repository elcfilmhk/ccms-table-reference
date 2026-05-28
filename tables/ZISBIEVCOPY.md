# ZISBIEVCOPY
**Description:** Copy standalone EV Bill requests
**Total Fields:** 5
**Key Fields:** MANDT, REQUEST_DATE, OPBEL

## Programs Using This Table
- `zisbi0002`
- `zisbi0135`
- `zisbi0136`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REQUEST_DATE` | DATS | 8 | 🔑 | Request Date |
| 3 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 4 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 5 | `DRUCKDAT` | DATS | 8 |  | Print Date |
