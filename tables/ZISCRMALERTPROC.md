# ZISCRMALERTPROC
**Description:** Record Current Process in CIC0
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `zalertmsg`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `BP` | CHAR | 10 |  | Business Partner Number |
| 3 | `USER_ID` | CHAR | 12 |  | User Name in User Master Record |
| 4 | `PROCESS_DATE` | DATS | 8 |  | Process Date |
| 5 | `PROCESS_TIME` | TIMS | 6 |  | Process Time |
| 6 | `CURRENT_PROCESS` | CHAR | 2 |  | Current Process |
