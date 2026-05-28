# ZISCS_EP360_BAL
**Description:** Structure for EP360 Balance
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `zcl_ziscs_pc_incent_02_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CANUMBER` | CHAR | 12 |  | Contract Account Number |
| 2 | `INC_RECV_DATE` | DATS | 8 |  | Incentive Date |
| 3 | `INC_DESCRIPTION` | CHAR | 255 |  | Text, 255 Characters |
| 4 | `BADGE_CODE` | CHAR | 4 |  | Badge Code |
| 5 | `ECO_POINT` | INT4 | 10 |  | Eco Points Transaction Amount (+: award to CA; -: deduct) |
| 6 | `GIFT` | CHAR | 30 |  | Gift |
| 7 | `INCENTIVE_1` | CHAR | 10 |  | Incentive 1 |
| 8 | `INCENTIVE_2` | CHAR | 10 |  | Incentive 2 |
