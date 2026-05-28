# ZISCS_NOTIF_MSG1
**Description:** Receipients for ZISCS_NOTIF_MSG
**Total Fields:** 7
**Key Fields:** MANDT, NOTIF_MSG_ID, ID

## Programs Using This Table
- `ziscs0372`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `NOTIF_MSG_ID` | INT4 | 10 | 🔑 | Notify Message ID |
| 3 | `ID` | INT1 | 3 | 🔑 | Artificial Key for Out-Going Contacts |
| 4 | `DISPATCH` | CHAR | 1 |  | Dispatch |
| 5 | `CONTACT` | CHAR | 300 |  | Contact ID (eg. A tel#, an email addr, WeChatOpenID, etc...) |
| 6 | `MSG_SENT_DT` | CHAR | 14 |  | Notify Message Sent Datetime |
| 7 | `UNSENT_REASON` | CHAR | 10 |  | Unsent Reason Code |
