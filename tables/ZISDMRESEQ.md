# ZISDMRESEQ
**Description:** Re-sequence meter reading order
**Total Fields:** 8
**Key Fields:** MANDT, USER_ID, UPDATE_DATE, UPDATE_TIME, ROUTE_ID, DEVICE, POS_OLD, POS_NEW

## Programs Using This Table
- `zisdm0165`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `USER_ID` | CHAR | 12 | 🔑 | User Name |
| 3 | `UPDATE_DATE` | DATS | 8 | 🔑 | System Date |
| 4 | `UPDATE_TIME` | TIMS | 6 | 🔑 | System Time |
| 5 | `ROUTE_ID` | CHAR | 8 | 🔑 | Meter reading unit |
| 6 | `DEVICE` | CHAR | 18 | 🔑 | Serial Number |
| 7 | `POS_OLD` | CHAR | 6 | 🔑 | Old Position in Partial Street Route |
| 8 | `POS_NEW` | CHAR | 6 | 🔑 | New Position in Partial Street Route |
