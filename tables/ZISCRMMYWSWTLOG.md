# ZISCRMMYWSWTLOG
**Description:** All web-traffic Log
**Total Fields:** 6
**Key Fields:** MANDT, FUNCID, TARIFTYP, LOG_DATE, LOG_TIME, WEBID

## Programs Using This Table
- `ziscrm0013`
- `ziscrm0013a`
- `ziscrm0016`
- `ziscrm0016a`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FUNCID` | CHAR | 5 | 🔑 | Function ID |
| 3 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 4 | `LOG_DATE` | DATS | 8 | 🔑 | Date |
| 5 | `LOG_TIME` | TIMS | 6 | 🔑 | Time |
| 6 | `WEBID` | CHAR | 50 | 🔑 | Web Login ID |
