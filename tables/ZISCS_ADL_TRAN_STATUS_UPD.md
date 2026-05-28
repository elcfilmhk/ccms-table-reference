# ZISCS_ADL_TRAN_STATUS_UPD
**Description:** ADL Domeo ID Update
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `zcl_z_bapi_mcom_adl_tr_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TRANS_ID` | CHAR | 32 |  | ADL Transaction ID |
| 2 | `EMAIL_ID` | CHAR | 241 |  | E-Mail Address |
| 3 | `DOMEO_ID` | CHAR | 100 |  | Contact |
| 4 | `STATUS` | CHAR | 1 |  | Message type: S Success, E Error, W Warning, I Info, A Abort |
| 5 | `MESSAGE` | CHAR | 255 |  | Text, 255 Characters |
