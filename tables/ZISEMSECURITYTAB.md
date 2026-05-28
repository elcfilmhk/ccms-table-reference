# ZISEMSECURITYTAB
**Description:** Energy Manager - Security table UUID for myWorkplace
**Total Fields:** 9
**Key Fields:** MANDT, UUID

## Programs Using This Table
- `zisem0001`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `UUID` | RAW | 64 | 🔑 | UUID FROM myworkplace |
| 3 | `LOGONID` | CHAR | 40 |  | Logon ID of myWorkplace |
| 4 | `TERM` | CHAR | 20 |  | Terminal ID |
| 5 | `TID` | INT4 | 10 |  | Terminal ID |
| 6 | `URLPP` | CHAR | 32 |  | Energy Manager - URLPP |
| 7 | `CREATE_DATE` | DATS | 8 |  | Vesting Date |
| 8 | `CREATE_TIME` | TIMS | 6 |  | Time |
| 9 | `TIMEOUT` | CHAR | 1 |  | Energy Manager - WDA session for EM is timeout |
