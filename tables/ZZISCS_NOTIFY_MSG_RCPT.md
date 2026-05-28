# ZZISCS_NOTIFY_MSG_RCPT
**Description:** Notify Message Receipients
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0408`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `NOTIF_MSG_ID` | INT4 | 10 |  | Notify Message ID |
| 2 | `ID` | INT1 | 3 |  | Artificial Key for Out-Going Contacts |
| 3 | `DISPATCH` | CHAR | 1 |  | Dispatch |
| 4 | `CONTACT` | CHAR | 300 |  | Contact ID (eg. A tel#, an email addr, WeChatOpenID, etc...) |
