# ZISCSBCUSER
**Description:** Business Center User right Maintenance
**Total Fields:** 9
**Key Fields:** MANDT, UNAME

## Programs Using This Table
- `ziscs0200`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `UNAME` | CHAR | 12 | 🔑 | User Name |
| 3 | `UPDATE_SO` | CHAR | 1 |  | Update Service Order Flag |
| 4 | `BC_USER` | CHAR | 1 |  | BC user |
| 5 | `REGION_USER` | CHAR | 1 |  | Region User |
| 6 | `DAILY` | CHAR | 1 |  | Daily Report |
| 7 | `MONTHLY` | CHAR | 1 |  | Monthly Report |
| 8 | `EMAIL` | CHAR | 50 |  | Correspondence email |
| 9 | `REGION` | CHAR | 15 |  | Region |
