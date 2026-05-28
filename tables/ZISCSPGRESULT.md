# ZISCSPGRESULT
**Description:** Online Application Track Result
**Total Fields:** 13
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_track_result_ap====ft`
- `z_bapi_get_track_result_mi====ft`
- `z_bapi_get_track_result_mo====ft`
- `z_bapi_get_track_result_mo_unift`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TXNNUM` | CHAR | 10 |  | CRM transaction no. |
| 2 | `RECEIVED_DATE` | DATS | 8 |  | Customer requested date |
| 3 | `STATUS` | CHAR | 2 |  | Status |
| 4 | `BANKKEY` | CHAR | 15 |  | Bank Keys |
| 5 | `BANKNUM` | CHAR | 18 |  | Bank account number |
| 6 | `HM_MO_CA` | CHAR | 12 |  | Source CA |
| 7 | `HM_MI_CA` | CHAR | 12 |  | Target CA |
| 8 | `REFUND_AMOUNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 9 | `TP_AMT` | CURR | 13 |  | Total Amount |
| 10 | `ZZADDRESS` | CHAR | 200 |  | New address for refund and final bill mailing |
| 11 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 12 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 13 | `APPL_SRC` | CHAR | 20 |  | Data source of Application |
