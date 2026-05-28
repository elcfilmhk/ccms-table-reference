# ZISCSMAILGROUP
**Description:** Email Group
**Total Fields:** 5
**Key Fields:** MANDT, GROUPNAME, USERNO

## Programs Using This Table
- `ziscs0113`
- `ziscs0114`
- `ziscs0117`
- `ziscs0123`
- `ziscs0125`
- `ziscs0140`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GROUPNAME` | CHAR | 20 | 🔑 | Group Name |
| 3 | `USERNO` | NUMC | 3 | 🔑 | User No |
| 4 | `REC_TYPE` | CHAR | 1 |  | Specification of recipient type |
| 5 | `REC_ID` | CHAR | 17 |  | Recipient ID |
