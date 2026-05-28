# ZISSDSOPENDBILL
**Description:** Sales order entries pending for billing
**Total Fields:** 9
**Key Fields:** MANDT, SALES_ORDER_NO

## Programs Using This Table
- `zissd00068`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SALES_ORDER_NO` | CHAR | 10 | 🔑 | Sales Order No |
| 3 | `STATUS` | CHAR | 1 |  | SO Billing Status |
| 4 | `REQUESTOR` | CHAR | 12 |  | Requestor |
| 5 | `REQUEST_DATE` | DATS | 8 |  | Request date |
| 6 | `REQUEST_TIME` | TIMS | 6 |  | Request time |
| 7 | `LAST_UPD_BY` | CHAR | 12 |  | Last updated by |
| 8 | `LAST_UPD_DATE` | DATS | 8 |  | Last update date |
| 9 | `LAST_UPD_TIME` | TIMS | 6 |  | Last update time |
