# ZISSDAPPRHIST
**Description:** Approval history for request for billing
**Total Fields:** 64
**Key Fields:** MANDT, SALES_ORDER_NO, UPD_SEQ

## Programs Using This Table
- `ziscs1122`
- `zissd00065`
- `zissd00069`
- `zissd00090`
- `zissd00091`
- `zissd00101`
- `zpc_rank_patch`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SALES_ORDER_NO` | CHAR | 10 | 🔑 | Sales Order No |
| 3 | `UPD_SEQ` | NUMC | 4 | 🔑 | Update sequence number |
| 4 | `APPR_STATUS` | CHAR | 3 |  | Current status |
| 5 | `CREATE_DATE` | DATS | 8 |  | Create date |
| 6 | `CREATE_TIME` | TIMS | 6 |  | Create time |
| 7 | `CREATE_BY` | CHAR | 12 |  | Create by |
| 8 | `LAST_UPD_BY` | CHAR | 12 |  | Last updated by |
| 9 | `LAST_UPD_DATE` | DATS | 8 |  | Last update date |
| 10 | `LAST_UPD_TIME` | TIMS | 6 |  | Last update time |
| 11 | `REQUESTOR` | CHAR | 12 |  | Requestor |
| 12 | `REQUEST_DATE` | DATS | 8 |  | Request date |
| 13 | `REQUEST_TIME` | TIMS | 6 |  | Request time |
| 14 | `CANCEL_BY` | CHAR | 12 |  | Cancelled by |
| 15 | `CANCEL_DATE` | DATS | 8 |  | Cancel date |
| 16 | `CANCEL_TIME` | TIMS | 6 |  | Cancel time |
| 17 | `CHG_APPROVER_BY` | CHAR | 12 |  | Change approver by |
| 18 | `CHG_APPROVER_DAT` | DATS | 8 |  | Change approver date |
| 19 | `CHG_APPROVER_TIM` | TIMS | 6 |  | Change approver time |
| 20 | `APPROVER_BH` | CHAR | 12 |  | Approver Branch Head |
| 21 | `APPR_BH_DATE` | DATS | 8 |  | Approver BH date |
| 22 | `APPR_BH_TIME` | TIMS | 6 |  | Approver BH time |
| 23 | `BH_APPR_INDC` | CHAR | 1 |  | BH approver indicator |
| 24 | `APPROVER_MF` | CHAR | 12 |  | Approver MACS Finance |
| 25 | `APPR_MF_DATE` | DATS | 8 |  | Approver MF date |
| 26 | `APPR_MF_TIME` | TIMS | 6 |  | Approver MF time |
| 27 | `MF_APPR_INDC` | CHAR | 1 |  | MF approver indicator |
| 28 | `APPROVER_DH` | CHAR | 12 |  | Approver Department Head |
| 29 | `APPR_DH_DATE` | DATS | 8 |  | Approver MD date |
| 30 | `APPR_DH_TIME` | TIMS | 6 |  | Approver MD time |
| 31 | `DH_APPR_INDC` | CHAR | 1 |  | MD approver indicator |
| 32 | `RIM_NO_CHANGE` | CHAR | 1 |  | RIM No Change |
| 33 | `PROJ_CAT` | CHAR | 5 |  | Project Category |
| 34 | `PROJ_CAT_B` | CHAR | 5 |  | Project Category |
| 35 | `RATE_CAT_B` | CHAR | 10 |  | Rate Category |
| 36 | `TOT_PROJ_COST_B` | CURR | 13 |  | Total Project Cost |
| 37 | `MAX_INC_APPR_B` | CURR | 13 |  | Max Incentive Approved |
| 38 | `MAX_INC_PCENT_B` | NUMC | 3 |  | Max Incentive as % of total Proj Cost |
| 39 | `CONT_CAPACITY_B` | DEC | 12 |  | Contract Capacity |
| 40 | `BC_RATIO_B` | DEC | 8 |  | BC Ratio (10 Year) |
| 41 | `PEAK_LOAD_IMP_B` | NUMC | 3 |  | Peak Load Impact |
| 42 | `EST_PAYBK_PER_B` | DEC | 6 |  | Estimated Payback Period |
| 43 | `PRO_ADD_SALES_B` | DEC | 12 |  | Proposed Additional Sales p.a. |
| 44 | `COSTGWH_RATIO_B` | DEC | 6 |  | Cost/Gwh Ratio |
| 45 | `CHECK_METER_NO` | CHAR | 60 |  | Check Meter Number |
| 46 | `CHECK_METER_REM` | CHAR | 60 |  | Check meter remarks |
| 47 | `APPR_BH_REMARKS` | CHAR | 60 |  | Approver remarks |
| 48 | `APPR_MF_REMARKS` | CHAR | 60 |  | Approver remarks |
| 49 | `APPR_DH_REMARKS` | CHAR | 60 |  | Approver remarks |
| 50 | `SUPPLIER` | CHAR | 40 |  | Supplier |
| 51 | `SUPPLIER2` | CHAR | 40 |  | Supplier |
| 52 | `CHEQUE_NO` | CHAR | 20 |  | Cheque number |
| 53 | `PROJ_CAT_DTL` | CHAR | 60 |  | Project Category Description |
| 54 | `CHQ_LAST_UPD_ID` | CHAR | 12 |  | Cheque last update by |
| 55 | `CHQ_LAST_UPD_DAT` | DATS | 8 |  | Cheque last update date |
| 56 | `CHQ_LAST_UPD_TIM` | TIMS | 6 |  | Cheque last update time |
| 57 | `CHQ_LAST_UPD_REM` | CHAR | 60 |  | Cheque processing remarks |
| 58 | `EFT_NO` | CHAR | 10 |  | EFT payment no. |
| 59 | `EFMS_INV_DOC_NO` | CHAR | 10 |  | EFMS invoice document no. |
| 60 | `PAYMENT_METHOD` | CHAR | 3 |  | Payment Method |
| 61 | `PAYEE_NAME` | CHAR | 81 |  | Payee Name |
| 62 | `.INCLU--AP` | &nbsp; | 0 |  | Append Structure of zissdapprhist |
| 63 | `DLVY_MODE` | CHAR | 2 |  | Delivery Mode |
| 64 | `EDMS_LINK` | CHAR | 250 |  | EDMS Link |
