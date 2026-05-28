# ZISSDHDRADDDATAB
**Description:** Fields under 'Additional data B' of sales quotation/order
**Total Fields:** 60
**Key Fields:** MANDT, QUOTATION_NO, SALES_ORDER_NO

## Programs Using This Table
- `ziscs1122`
- `zissd00065`
- `zissd00070`
- `zissd00091`
- `zissd00101`
- `zpc_rank_patch`
- `zsdsodl05`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `QUOTATION_NO` | CHAR | 10 | 🔑 | Quotation No |
| 3 | `SALES_ORDER_NO` | CHAR | 10 | 🔑 | Sales Order No |
| 4 | `PROJECT_NO` | CHAR | 18 |  | Project No |
| 5 | `EDMS_LINK` | CHAR | 250 |  | EDMS Link |
| 6 | `PROJ_CAT` | CHAR | 5 |  | Project Category |
| 7 | `INSTALL_DATE` | DATS | 8 |  | Equipment install date |
| 8 | `AGREEMENT_PERIOD` | NUMC | 3 |  | Agreement period |
| 9 | `RATE_CAT_Q` | CHAR | 10 |  | Rate Category |
| 10 | `TOT_PROJ_COST_Q` | CURR | 13 |  | Total Project Cost |
| 11 | `MAX_INC_APPR_Q` | CURR | 13 |  | Max Incentive Approved |
| 12 | `MAX_INC_PCENT_Q` | NUMC | 3 |  | Max Incentive as % of total Proj Cost |
| 13 | `CONT_CAPACITY_Q` | DEC | 12 |  | Contract Capacity |
| 14 | `BC_RATIO_Q` | DEC | 8 |  | BC Ratio (10 Year) |
| 15 | `PEAK_LOAD_IMP_Q` | NUMC | 3 |  | Peak Load Impact |
| 16 | `EST_PAYBK_PER_Q` | DEC | 6 |  | Estimated Payback Period |
| 17 | `PRO_ADD_SALES_Q` | DEC | 12 |  | Proposed Additional Sales p.a. |
| 18 | `COSTGWH_RATIO_Q` | DEC | 6 |  | Cost/Gwh Ratio |
| 19 | `RIM_NO_CHANGE_S` | CHAR | 1 |  | RIM No Change |
| 20 | `RATE_CAT_S` | CHAR | 10 |  | Rate Category |
| 21 | `TOT_PROJ_COST_S` | CURR | 13 |  | Total Project Cost |
| 22 | `MAX_INC_APPR_S` | CURR | 13 |  | Max Incentive Approved |
| 23 | `MAX_INC_PCENT_S` | NUMC | 3 |  | Max Incentive as % of total Proj Cost |
| 24 | `CONT_CAPACITY_S` | DEC | 12 |  | Contract Capacity |
| 25 | `BC_RATIO_S` | DEC | 8 |  | BC Ratio (10 Year) |
| 26 | `PEAK_LOAD_IMP_S` | NUMC | 3 |  | Peak Load Impact |
| 27 | `EST_PAYBK_PER_S` | DEC | 6 |  | Estimated Payback Period |
| 28 | `PRO_ADD_SALES_S` | DEC | 12 |  | Proposed Additional Sales p.a. |
| 29 | `COSTGWH_RATIO_S` | DEC | 6 |  | Cost/Gwh Ratio |
| 30 | `RIM_NO_CHANGE_B` | CHAR | 1 |  | RIM No Change |
| 31 | `RATE_CAT_B` | CHAR | 10 |  | Rate Category |
| 32 | `TOT_PROJ_COST_B` | CURR | 13 |  | Total Project Cost |
| 33 | `MAX_INC_APPR_B` | CURR | 13 |  | Max Incentive Approved |
| 34 | `MAX_INC_PCENT_B` | NUMC | 3 |  | Max Incentive as % of total Proj Cost |
| 35 | `CONT_CAPACITY_B` | DEC | 12 |  | Contract Capacity |
| 36 | `BC_RATIO_B` | DEC | 8 |  | BC Ratio (10 Year) |
| 37 | `PEAK_LOAD_IMP_B` | NUMC | 3 |  | Peak Load Impact |
| 38 | `EST_PAYBK_PER_B` | DEC | 6 |  | Estimated Payback Period |
| 39 | `PRO_ADD_SALES_B` | DEC | 12 |  | Proposed Additional Sales p.a. |
| 40 | `COSTGWH_RATIO_B` | DEC | 6 |  | Cost/Gwh Ratio |
| 41 | `CHECK_METER_NO` | CHAR | 60 |  | Check Meter Number |
| 42 | `CHECK_METER_REM` | CHAR | 60 |  | Check meter remarks |
| 43 | `TRADING_NAME` | CHAR | 60 |  | Trading name |
| 44 | `SUPPLIER` | CHAR | 40 |  | Supplier |
| 45 | `SUPPLIER2` | CHAR | 40 |  | Supplier |
| 46 | `CHEQUE_NO` | CHAR | 20 |  | Cheque number |
| 47 | `CREATE_DATE` | DATS | 8 |  | Create date |
| 48 | `CREATE_TIME` | TIMS | 6 |  | Create time |
| 49 | `CREATE_BY` | CHAR | 12 |  | Create by |
| 50 | `UPDATE_DATE` | DATS | 8 |  | Last update date |
| 51 | `UPDATE_TIME` | TIMS | 6 |  | Last update time |
| 52 | `UPDATE_BY` | CHAR | 12 |  | Last updated by |
| 53 | `AGREEMENT_NO` | CHAR | 18 |  | Agreement number |
| 54 | `AGREEMENT_DATE` | DATS | 8 |  | Agreement expiry date |
| 55 | `PROJ_CAT_DTL` | CHAR | 60 |  | Project Category Description |
| 56 | `CHQ_LAST_UPD_REM` | CHAR | 60 |  | Cheque processing remarks |
| 57 | `EFT_NO` | CHAR | 10 |  | EFT payment no. |
| 58 | `EFMS_INV_DOC_NO` | CHAR | 10 |  | EFMS invoice document no. |
| 59 | `PAYMENT_METHOD` | CHAR | 3 |  | Payment Method |
| 60 | `PAYEE_NAME` | CHAR | 81 |  | Payee Name |
