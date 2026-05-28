# ZISCSFOLLOWUP
**Description:** Follow Up Input File
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0110`
- `ziscs0115`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CONTRACT` | CHAR | 10 |  | Order Number |
| 2 | `FOLLOWUP_ID` | CHAR | 24 |  | Follow Up Order Identifier |
| 3 | `FOLLOWUP_TYPE` | CHAR | 16 |  | Follow Up Order Type |
| 4 | `CREATEORDER_ID` | CHAR | 24 |  | Createing Order Identifier |
| 5 | `METER` | CHAR | 10 |  | Meter Number |
| 6 | `INSTRUCTIONS` | CHAR | 500 |  | Instructions |
| 7 | `OP_CENTER` | CHAR | 2 |  | Operation Center |
| 8 | `INTERFACE_ID` | NUMC | 8 |  | Interface ID |
| 9 | `CREATE_DATE` | DATS | 8 |  | Create Date |
