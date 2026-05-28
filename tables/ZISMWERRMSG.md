# ZISMWERRMSG
**Description:** Middleware job error message list
**Total Fields:** 4
**Key Fields:** MANDT, MSGID, MSGNO

## Programs Using This Table
- `ziscrm0035`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MSGID` | CHAR | 20 | 🔑 | Message Class |
| 3 | `MSGNO` | NUMC | 3 | 🔑 | Message Number |
| 4 | `ERRCOUNT` | NUMC | 2 |  | Error count |
