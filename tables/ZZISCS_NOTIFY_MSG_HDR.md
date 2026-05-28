# ZZISCS_NOTIFY_MSG_HDR
**Description:** Notify Message header
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0408`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `NOTIF_MSG_ID` | INT4 | 10 |  | Notify Message ID |
| 2 | `CASE_ID` | INT4 | 10 |  | Notify Case ID |
| 3 | `SERVICE_TYPE` | CHAR | 1 |  | Type of eService |
| 4 | `CASE_TYPE` | CHAR | 50 |  | Case Type of "Notify Case" Object |
| 5 | `NOTIF_EVENT_TYPE` | CHAR | 50 |  | Event Type code for Notification |
