# ZISCSINCSTATUS
**Description:** Incident Status Mapping Table
**Total Fields:** 3
**Key Fields:** MANDT, INC_STAT_EXT, INCIDENT_STATUS

## Programs Using This Table
- `ziscs0118`
- `ziscs0119`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `INC_STAT_EXT` | CHAR | 32 | 🔑 | Name Display in Drop Down Menu |
| 3 | `INCIDENT_STATUS` | CHAR | 32 | 🔑 | Name in custom table |
