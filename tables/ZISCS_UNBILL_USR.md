# ZISCS_UNBILL_USR
**Description:** Unbilled consumption user
**Total Fields:** 3
**Key Fields:** MANDT, LOCALITY, USERID

## Programs Using This Table
- `ziscs0373`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LOCALITY` | CHAR | 2 | 🔑 | Locality of work center |
| 3 | `USERID` | CHAR | 12 | 🔑 | ABAP System Field: Name of Current User |
