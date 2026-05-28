# ZISCRMPOPUPSTAT
**Description:** Target Selling - Pop Up Status Information
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `ztgcust`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `OBJECT_ID` | CHAR | 30 |  | Object ID for Target Customer List |
| 3 | `ALERT_TYPE` | CHAR | 2 |  | Object Type for Target Customer List |
| 4 | `LIST_ID` | CHAR | 12 |  | List ID indicate different interest/attribute for promotion |
| 5 | `ACCESS_DATE` | DATS | 8 |  | Access Date |
| 6 | `ACCESS_TIME` | TIMS | 6 |  | Access Time |
| 7 | `ACCESS_USER` | CHAR | 12 |  | Access User |
| 8 | `DISPATCH_CTRL` | CHAR | 4 |  | Dispatch Control |
