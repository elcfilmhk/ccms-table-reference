# ZISSDPRRELEASE
**Description:** PR Release for Mass Upload Retail Sales Order
**Total Fields:** 10
**Key Fields:** MANDT, SO, PR

## Programs Using This Table
- `zissd00108`
- `zissd00110`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SO` | CHAR | 10 | 🔑 | Sales Document |
| 3 | `PR` | CHAR | 10 | 🔑 | Purchase Requisition Number |
| 4 | `RELEASED` | CHAR | 1 |  | Released Indicator |
| 5 | `CREATE_DATE` | DATS | 8 |  | Created on |
| 6 | `CREATE_TIME` | TIMS | 6 |  | Time of creation |
| 7 | `CREATE_BY` | CHAR | 12 |  | Created by |
| 8 | `CHANGE_DATE` | DATS | 8 |  | Changed on |
| 9 | `CHANGE_TIME` | TIMS | 6 |  | Time of change |
| 10 | `CHANGE_BY` | CHAR | 12 |  | Last changed by |
