# ZISBIGOV_SUBSIDY_2011
**Description:** Government Electricity Subsidy 2011
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_bill_presentment=======ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TOTAL_ENTITLEMENT` | CURR | 13 |  | Snapshot of D (2011 Subsidy granted V total to-date) |
| 2 | `SUBSIDY_BF` | CURR | 13 |  | Snapshot of E (Subsidy brought forward from last bill) |
| 3 | `SUBSIDY_PERIOD` | CURR | 13 |  | Snapshot of F (2011 Subsidy granted V since last bill) |
| 4 | `SUBSIDY_USED` | CURR | 13 |  | Snapshot of G (Subsidy used for this bill) |
| 5 | `SUBSIDY_CF` | CURR | 13 |  | Snapshot of H (Subsidy balance) |
| 6 | `SUBSIDY_VOID_FG` | CHAR | 1 |  | Government subsidy void indicator |
