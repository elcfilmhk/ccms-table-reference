# ZISCS_FIT_INFO
**Description:** FIT information for CA
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_fit_info===========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `RE_APP_NO` | CHAR | 12 |  | Notification No |
| 3 | `APP_TYPE` | CHAR | 2 |  | Application Type |
| 4 | `RE_APP_STATUS` | CHAR | 2 |  | RE Application Status |
| 5 | `LAST_CHANGE_TIME` | CHAR | 14 |  | Streamserve Timestamp |
| 6 | `LOEVM` | CHAR | 1 |  | Mark Contract Account for Deletion |
| 7 | `PAY_OPTION` | CHAR | 2 |  | FiT Payment Option |
| 8 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 9 | `DISTRICT` | CHAR | 40 |  | District |
| 10 | `EXP_COMP_DAT` | DATS | 8 |  | Expected Completion Date |
| 11 | `BUILD_TYPE` | CHAR | 2 |  | Building Type |
