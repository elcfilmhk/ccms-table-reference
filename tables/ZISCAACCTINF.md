# ZISCAACCTINF
**Description:** Account Information
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_account_info===========ft`
- `z_bapi_all_account_info=======ft`
- `zcl_z_bapi_account__02_mpc`
- `zcl_z_bapi_account__03_mpc`
- `zcl_z_bapi_all_account_mpc`
- `zcl_z_tesst_table_02_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CONTRACT_ACCOUNT` | CHAR | 12 |  | Contract Account Number |
| 2 | `CONTRACT` | CHAR | 10 |  | Contract |
| 3 | `RATE_CATEGORY` | CHAR | 10 |  | Rate category |
| 4 | `LANGUAGE` | LANG | 1 |  | Language in connection with the contract account |
| 5 | `AUTOPAY_CEIL_AMT` | CURR | 13 |  | Maximum Amount for a Payment with this Payment Method |
| 6 | `ACCOUNT_CLASS` | CHAR | 4 |  | Account class |
| 7 | `ACCOUNT_CLASS_DESC` | CHAR | 40 |  | Text for account class |
| 8 | `TRADE_CLASS` | CHAR | 4 |  | Trade Class |
| 9 | `TRADE_CLASS_DESC` | CHAR | 40 |  | Text for account class |
| 10 | `SEGMENT_LABEL` | CHAR | 1 |  | Segment label |
| 11 | `VIP_PRIORITY` | CHAR | 3 |  | VIP priority |
