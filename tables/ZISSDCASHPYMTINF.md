# ZISSDCASHPYMTINF
**Description:** Cash Payment Information
**Total Fields:** 11
**Key Fields:** MANDT, SALES_ORDER_NO, CI_INSTAL_NO

## Programs Using This Table
- `zissd00091`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SALES_ORDER_NO` | CHAR | 10 | 🔑 | Sales Order No |
| 3 | `CI_INSTAL_NO` | NUMC | 2 | 🔑 | CI Installment Number |
| 4 | `CI_INSTAL_AMT` | CURR | 13 |  | CI Installment Amount |
| 5 | `CHEQUE_NO` | CHAR | 20 |  | Cheque number |
| 6 | `EFMS_INV_DOC_NO` | CHAR | 10 |  | EFMS invoice document no. |
| 7 | `EFT_NO` | CHAR | 10 |  | EFT payment no. |
| 8 | `CHQ_LAST_UPD_REM` | CHAR | 60 |  | Cheque processing remarks |
| 9 | `CHQ_LAST_UPD_ID` | CHAR | 12 |  | Cheque last update by |
| 10 | `CHQ_LAST_UPD_DAT` | DATS | 8 |  | Cheque last update date |
| 11 | `CHQ_LAST_UPD_TIM` | TIMS | 6 |  | Cheque last update time |
