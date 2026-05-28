# ZISBI_ADJ_RPT
**Description:** Adjusted Bill Report
**Total Fields:** 26
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0014`
- `zisbi0014t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PERIOD_FR` | DATS | 8 |  | Report Period From |
| 2 | `PERIOD_TO` | DATS | 8 |  | Report Period to |
| 3 | `VKONTO` | CHAR | 12 |  | Contract Account Number |
| 4 | `OPBEL` | CHAR | 12 |  | Number of print document |
| 5 | `NATURE` | CHAR | 30 |  | Nature |
| 6 | `SEQ` | NUMC | 4 |  | Sequence |
| 7 | `DETAIL` | CHAR | 50 |  | Details Description |
| 8 | `READ_DATE` | DATS | 8 |  | Reading Date |
| 9 | `APPR_DATE` | DATS | 8 |  | Approval Date |
| 10 | `CONFIRM_DATE` | DATS | 8 |  | Confirmed Date |
| 11 | `REQ_DAYS` | INT4 | 10 |  | No of Days Requried |
| 12 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 13 | `INPUT_ID` | CHAR | 12 |  | Input User ID |
| 14 | `APPROVER_ID` | CHAR | 12 |  | User ID Approval |
| 15 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 16 | `ADJ_TYPE` | CHAR | 30 |  | Type of Adjustment |
| 17 | `REV_REASON` | CHAR | 40 |  | Reversal Reason |
| 18 | `ORG_CSMP` | DEC | 17 |  | Original Consumption |
| 19 | `ADJ_CSMP` | DEC | 17 |  | Adjusted Consumption |
| 20 | `REV_CSMP` | DEC | 17 |  | Revised Consumption |
| 21 | `ORG_CHRG` | CURR | 13 |  | Original Charge |
| 22 | `ADJ_CHRG` | CURR | 13 |  | Adjusted Charge |
| 23 | `REV_CHRG` | CURR | 13 |  | Revised Charge |
| 24 | `AMT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 25 | `AMI` | CHAR | 1 |  | AMI |
| 26 | `FIT` | CHAR | 1 |  | FIT |
