# ZISMDSLASTSLADAT
**Description:** Parameter of SLA day(s) for SLA Service Type
**Total Fields:** 4
**Key Fields:** MANDT, SERVICETYPE

## Programs Using This Table
- `zised0049`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERVICETYPE` | CHAR | 2 | 🔑 | Load Profile Service Type |
| 3 | `CUTOFFDAY` | INT1 | 3 |  | Cut-off Days of Agreed Service Level |
| 4 | `DESCRIPTION` | CHAR | 20 |  | Text (20 Characters) |
