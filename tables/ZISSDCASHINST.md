# ZISSDCASHINST
**Description:** Cash Installment Details
**Total Fields:** 16
**Key Fields:** MANDT, EC_ORDER_NO, EC_ORDER_ITEM, VKONT, CI_INSTAL_NO

## Programs Using This Table
- `zisfi0238`
- `zissd00065`
- `zissd00089`
- `zissd00090`
- `zissd00091`
- `zissd00093`
- `zissd00115`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EC_ORDER_NO` | CHAR | 10 | 🔑 | Sales Order Number |
| 3 | `EC_ORDER_ITEM` | NUMC | 6 | 🔑 | Sales Order Item Number |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `CI_INSTAL_NO` | NUMC | 2 | 🔑 | CI Installment Number |
| 6 | `CI_INSTAL_AMT` | CURR | 13 |  | CI Installment Amount |
| 7 | `CI_PAYM_DATE` | DATS | 8 |  | CI Payment Date |
| 8 | `CI_CONFIRM_PAY` | CHAR | 1 |  | Confirm Payment Flag |
| 9 | `CI_CONF_PAYM_DAT` | DATS | 8 |  | Confirm Payment Date |
| 10 | `CI_REVISED_AMT` | CURR | 13 |  | Revised Amount |
| 11 | `CI_UPDATE_DATE` | DATS | 8 |  | Date of Last Change |
| 12 | `CI_UPDATE_TIME` | TIMS | 6 |  | Time of Change |
| 13 | `CI_UPDATE_BY` | CHAR | 12 |  | Name of person who changed object |
| 14 | `CI_ACTUAL_PAYM_D` | DATS | 8 |  | Actual Payment Date |
| 15 | `CI_ORIG_PAYDATE` | DATS | 8 |  | Original CI Payment Date |
| 16 | `SENDEMAIL_STATUS` | CHAR | 1 |  | Send Email Status |
