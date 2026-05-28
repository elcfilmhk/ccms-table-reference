# ZISFIDUNCTRL
**Description:** Payment Channel Checking Control
**Total Fields:** 9
**Key Fields:** MANDT, CHANNEL, CREATE_ON

## Programs Using This Table
- `zisfi0317`
- `zisfi0320`
- `zisfi0335`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CHANNEL` | CHAR | 35 | 🔑 | Payment Channel |
| 3 | `CREATE_ON` | DATS | 8 | 🔑 | Created on |
| 4 | `FILEFLAG` | CHAR | 1 |  | File Flag Control |
| 5 | `DUNFLAG` | CHAR | 1 |  | Dunning Flag Control |
| 6 | `FROM_DATE` | DATS | 8 |  | Valid From Date |
| 7 | `TO_DATE` | DATS | 8 |  | Valid To Date |
| 8 | `CREATE_BY` | CHAR | 12 |  | Created by |
| 9 | `REMARK` | CHAR | 50 |  | Remark |
