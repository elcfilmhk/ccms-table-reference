# ZISCS_ST_ISDM0369
**Description:** Structure for DR incentive Approval report
**Total Fields:** 31
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0369_ssr`
- `zisdm0369_ssr_mod`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CHECK_BOX` | CHAR | 1 |  | Checkbox |
| 2 | `CREATED_ON` | DATS | 8 |  | Imported on date from AutoGrid |
| 3 | `CREATED_AT` | TIMS | 6 |  | Imported at time |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `EVENT_ID` | CHAR | 50 |  | Event ID from Autogrid |
| 6 | `EVENT_DATE` | DATS | 8 |  | Event Date |
| 7 | `EVENT_START_TIME` | TIMS | 6 |  | Start Time |
| 8 | `EVENT_END_TIME` | TIMS | 6 |  | End Time |
| 9 | `BASELINE_USE_STATUS` | CHAR | 2 |  | Use Status |
| 10 | `BLINE_USE_STAT_DESC` | CHAR | 60 |  | Explanatory Short Text |
| 11 | `BASELINE_USE` | DEC | 31 |  | Baseline (kWh) |
| 12 | `ACTUAL_USE_STATUS` | CHAR | 2 |  | Use Status |
| 13 | `ACTUAL_USE_STAT_DESC` | CHAR | 60 |  | Explanatory Short Text |
| 14 | `ACTUAL_USE` | DEC | 31 |  | Actual Demand (kWh) |
| 15 | `CUT_LOAD` | DEC | 31 |  | Qualified Demand Reduction (kWh) |
| 16 | `INCENTIVE_TYPE` | CHAR | 3 |  | Incentive Type for DR |
| 17 | `INCENTIVE` | DEC | 16 |  | Incentive Payment |
| 18 | `ADJUSTMENT` | CHAR | 1 |  | Adjustment Status |
| 19 | `MOVE_IN_DATE` | DATS | 8 |  | Move-In Date |
| 20 | `MOVE_OUT_DATE` | DATS | 8 |  | Move-Out Date |
| 21 | `REASON_FOR_ENDING` | CHAR | 2 |  | Reason for ending subscription |
| 22 | `END_REASON_DESC` | CHAR | 60 |  | Explanatory Short Text |
| 23 | `SMART_GADGETS` | CHAR | 150 |  | Smart Gadget Id. |
| 24 | `APPROVAL_STATUS` | CHAR | 60 |  | Approval Status |
| 25 | `LAST_UPDATED_BY` | CHAR | 12 |  | Name of person who changed object |
| 26 | `LAST_UPDATED_ON` | DATS | 8 |  | Date of Last Change |
| 27 | `REMARK_SHORT_TXT` | CHAR | 50 |  | Short text for Remark |
| 28 | `REMARKS` | CHAR | 150 |  | Remarks |
| 29 | `PROCEESSED` | DATS | 8 |  | Incentive Posting Processe on Date |
| 30 | `STYLE` | TTYP | 0 |  | ALV Control: Style Table for Cells |
| 31 | `COUNTER` | NUMC | 5 |  | Counter for SSR records |
