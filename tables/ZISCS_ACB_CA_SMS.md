# ZISCS_ACB_CA_SMS
**Description:** Stores SMS numbers for ACB Notification
**Total Fields:** 9
**Key Fields:** MANDT, VKONT, SMS

## Programs Using This Table
- `ziscs_migration_account_notif`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `SMS` | CHAR | 50 | 🔑 | Attribute 1 for Contact Information |
| 4 | `ROLE_ID` | INT4 | 10 |  | ACB Notification: EMO Role ID |
| 5 | `LANG` | CHAR | 1 |  | CEP: Home Energy Report (HER) Language |
| 6 | `LAST_CHANGE_DT` | CHAR | 14 |  | Changed Datetime |
| 7 | `LAST_CHANGE_USER` | CHAR | 12 |  | Changed By |
| 8 | `DELETE_DT` | CHAR | 14 |  | Deleted Datetime |
| 9 | `DELETE_USER` | CHAR | 12 |  | Deleted By |
