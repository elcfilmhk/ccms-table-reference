# ZISCS_APPL_TRACK_RESULT_01
**Description:** Return structure of Customer Applications tracking 01
**Total Fields:** 19
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_chk_appl_prog==========ft`
- `z_bapi_get_mi_check===========ft`
- `z_bapi_get_track_mi_temp_01===ft`
- `z_bapi_prog_check=============ft`
- `zcl_zbapi_chk_appl_pro_dpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZKEY` | CHAR | 50 |  | Key for joining with other return tables |
| 2 | `APPL_TY` | CHAR | 2 |  | Application Type |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 5 | `NAME` | CHAR | 255 |  | Name of Registered customer |
| 6 | `RECEIVED_DATE` | DATS | 8 |  | Customer requested date |
| 7 | `ADDR_SUPPLY` | CHAR | 200 |  | New address for refund and final bill mailing |
| 8 | `APPL_CHNL` | CHAR | 20 |  | Data source of Application |
| 9 | `STATUS_TRACK` | CHAR | 30 |  | Status Track Code |
| 10 | `CURR_STATUS` | CHAR | 30 |  | Current Status |
| 11 | `TXNNUM` | CHAR | 10 |  | CRM transaction no. |
| 12 | `SO_NUM` | CHAR | 12 |  | Order Number |
| 13 | `MOVE_IN_CA` | CHAR | 12 |  | Contract Account Number |
| 14 | `ACT_REQ_STR_ID` | CHAR | 20 |  | "Customer's Actions Required" string ID |
| 15 | `ADD_INFO_STR` | CHAR | 20 |  | "Additional Info" string ID |
| 16 | `MSG_01` | CHAR | 500 |  | message 1 for ACT_REQ_STR_ID |
| 17 | `MSG_02` | CHAR | 500 |  | message 2 for ACT_REQ_STR_ID |
| 18 | `MSG_03` | CHAR | 500 |  | message 3 for ADD_INFO_STR |
| 19 | `MSG_04` | CHAR | 500 |  | message 4 for ADD_INFO_STR |
