# ZZISCS_ACB_CA_SMS
**Description:** ACB CA SMS structure
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `z_acb_get_ca_sms==============ft`
- `ziscs0407`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | Stores SMS numbers for ACB Notification |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `SMS` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 5 | `ROLE_ID` | INT4 | 10 |  | ACB Notification: EMO Role ID |
| 6 | `LANG` | CHAR | 1 |  | CEP: Home Energy Report (HER) Language |
| 7 | `LAST_CHANGE_DT` | CHAR | 14 |  | Changed Datetime |
| 8 | `LAST_CHANGE_USER` | CHAR | 12 |  | Changed By |
| 9 | `DELETE_DT` | CHAR | 14 |  | Deleted Datetime |
| 10 | `DELETE_USER` | CHAR | 12 |  | Deleted By |
| 11 | `ROLE_NAME` | CHAR | 30 |  | 30 Characters |
