# ZISSDEC
**Description:** Electricity Coupon and Cash Incentive
**Total Fields:** 57
**Key Fields:** MANDT, EC_ORDER_NO, EC_ORDER_ITEM

## Programs Using This Table
- `zisfi0118`
- `zisfi0121`
- `zissd00065`
- `zissd00066`
- `zissd00089`
- `zissd00090`
- `zissd00091`
- `zissd00094`
- `zissd00095`
- `zsdsodl05`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EC_ORDER_NO` | CHAR | 10 | 🔑 | Sales Order Number |
| 3 | `EC_ORDER_ITEM` | NUMC | 6 | 🔑 | Sales Order Item Number |
| 4 | `EC_CREAT_DATE` | DATS | 8 |  | EC Creation Date |
| 5 | `EC_CREAT_TIME` | TIMS | 6 |  | EC Creation Time |
| 6 | `EC_CREATE_BY` | CHAR | 12 |  | EC Created By |
| 7 | `TOT_INCENTIVE` | CURR | 13 |  | Total Incentive Amount |
| 8 | `CASH_INCENTIVE` | CURR | 13 |  | Cash Incentive (not related to EC) |
| 9 | `EC_TOTAL` | CURR | 13 |  | EC Total Amount (Total Amount of Sales Bonus) |
| 10 | `EC_COST_CTR` | CHAR | 10 |  | EC Cost Centre |
| 11 | `EC_STATUS` | CHAR | 1 |  | EC Status |
| 12 | `EC_CANCEL_DATE` | DATS | 8 |  | EC Cancelled Date |
| 13 | `EC_CANCEL_TIME` | TIMS | 6 |  | EC Cancelled Time |
| 14 | `EC_CANCEL_BY` | CHAR | 12 |  | EC Cancelled By |
| 15 | `EC_EXTEND` | CHAR | 1 |  | EC Extension Flag |
| 16 | `EC_EXTEND_TOTAMT` | CURR | 13 |  | EC Extension: Total Amount |
| 17 | `EC_EXTEND_NO_INS` | DEC | 10 |  | EC Extension: Number of Installment |
| 18 | `EC_EXTEND_DATE` | DATS | 8 |  | EC Extension: Creation Date |
| 19 | `EC_EXTEND_TIME` | TIMS | 6 |  | EC Extension: Creation Time |
| 20 | `EC_EXTEND_BY` | CHAR | 12 |  | EC Extension: Created By |
| 21 | `EC_START_DATE` | DATS | 8 |  | EC Start Date |
| 22 | `EC_END_DATE` | DATS | 8 |  | EC End Date |
| 23 | `CONTRACT_REF_NO` | CHAR | 18 |  | Contract Reference Number |
| 24 | `EC_APPROVER` | CHAR | 45 |  | EC Approver |
| 25 | `EC_NO_OF_INSTALL` | DEC | 10 |  | Total Number of EC Installment |
| 26 | `EC_UPDATE_DATE` | DATS | 8 |  | EC Update Date |
| 27 | `EC_UPDATE_TIME` | TIMS | 6 |  | EC Update Time |
| 28 | `EC_UPDATE_BY` | CHAR | 12 |  | EC Update By |
| 29 | `EC_REV_TOTAL` | CURR | 13 |  | Revised Electricity Sales Bonus Amount |
| 30 | `EC_EXTEND_NO_OLD` | DEC | 10 |  | EC Extension: Number of Installment |
| 31 | `EC_ORIG_TOTAL` | CURR | 13 |  | Original Electricity Sales Bonus Amount |
| 32 | `CI_CREAT_DATE` | DATS | 8 |  | CI Creation Date |
| 33 | `CI_CREAT_TIME` | TIMS | 6 |  | CI Creation Time |
| 34 | `CI_CREATE_BY` | CHAR | 12 |  | CI Created By |
| 35 | `CI_TOTAL` | CURR | 13 |  | CI Total amount (Total amount of Cash Installment) |
| 36 | `CI_COST_CTR` | CHAR | 10 |  | CI Cost Centre |
| 37 | `CI_STATUS` | CHAR | 1 |  | CI Status |
| 38 | `CI_CANCEL_DATE` | DATS | 8 |  | CI Cancelled Date |
| 39 | `CI_CANCEL_TIME` | TIMS | 6 |  | CI Cancelled Time |
| 40 | `CI_CANCEL_BY` | CHAR | 12 |  | CI Cancelled By |
| 41 | `CI_EXTEND` | CHAR | 1 |  | CI Extension Flag |
| 42 | `CI_EXTEND_TOTAMT` | CURR | 13 |  | CI Extension: Total Amount |
| 43 | `CI_EXTEND_NO_INS` | DEC | 10 |  | CI Extension: Number of Installment |
| 44 | `CI_EXTEND_DATE` | DATS | 8 |  | CI Extension: Creation Date |
| 45 | `CI_EXTEND_TIME` | TIMS | 6 |  | CI Extension: Creation Time |
| 46 | `CI_EXTEND_BY` | CHAR | 12 |  | CI Extension: Created By |
| 47 | `CI_START_DATE` | DATS | 8 |  | CI Start Date |
| 48 | `CI_END_DATE` | DATS | 8 |  | CI End Date |
| 49 | `CI_APPROVER` | CHAR | 45 |  | CI Approver |
| 50 | `CI_NO_OF_INSTALL` | DEC | 10 |  | Total Number of CI Installment |
| 51 | `CI_UPDATE_DATE` | DATS | 8 |  | CI Update Date |
| 52 | `CI_UPDATE_TIME` | TIMS | 6 |  | CI Update Time |
| 53 | `CI_UPDATE_BY` | CHAR | 12 |  | CI Update By |
| 54 | `CI_REV_TOTAL` | CURR | 13 |  | Revised Cash Installment Amount |
| 55 | `CI_EXTEND_NO_OLD` | DEC | 10 |  | CI Extension: Number of Installment |
| 56 | `CI_ORIG_TOTAL` | CURR | 13 |  | Original Cash Installment Amount |
| 57 | `CI_CHG_EMAIL_TXT` | CHAR | 255 |  | CI Request to Change E-mail Text |
