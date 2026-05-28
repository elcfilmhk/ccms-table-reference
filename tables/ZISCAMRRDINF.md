# ZISCAMRRDINF
**Description:** Next Meter Reading Information
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_account_info===========ft`
- `z_bapi_all_account_info=======ft`
- `zcl_z_bapi_account__02_mpc`
- `zcl_z_bapi_account__03_mpc`
- `zcl_z_bapi_all_account_mpc`
- `zcl_z_bapi_test_tab_01_mpc`
- `zcl_z_tesst_table_02_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CONTRACT_ACCOUNT` | CHAR | 12 |  | Contract Account Number |
| 2 | `CONTRACT` | CHAR | 10 |  | Contract |
| 3 | `INSTALLATION` | CHAR | 10 |  | Installation |
| 4 | `MR_DATE` | DATS | 8 |  | Scheduled meter reading date |
| 5 | `MRDATEFORBILLING` | DATS | 8 |  | Meter reading date relevant to billing |
