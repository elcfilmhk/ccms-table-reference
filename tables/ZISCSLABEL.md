# ZISCSLABEL
**Description:** Label Printing Request
**Total Fields:** 19
**Key Fields:** MANDT, REQ_DATE, REQ_NO

## Programs Using This Table
- `ziscs0138`
- `ziscs0141`
- `ziscs0143`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REQ_DATE` | DATS | 8 | 🔑 | Label request date |
| 3 | `REQ_NO` | CHAR | 4 | 🔑 | Request number |
| 4 | `CHANGE_REQ` | CHAR | 20 |  | Change request |
| 5 | `CAPEX_OR_OPEX` | CHAR | 1 |  | CAPEX/OPEX |
| 6 | `CHARGE_TO` | CHAR | 20 |  | Charge to |
| 7 | `CONTACT_PERSON` | CHAR | 12 |  | Contact user id |
| 8 | `DEPT_OF_USER` | CHAR | 20 |  | Department of user |
| 9 | `LABEL_DESP` | CHAR | 15 |  | Description on label |
| 10 | `ADD_TYPE` | CHAR | 1 |  | Address type |
| 11 | `CONTRACT_TYPE` | CHAR | 1 |  | Contract Type |
| 12 | `STAFF_ACCT` | CHAR | 1 |  | Staff Account |
| 13 | `NO_OF_ACCT` | NUMC | 10 |  | Total number of accounts to be printed |
| 14 | `EXPECT_COMP_DATE` | DATS | 8 |  | Expected Completion Date |
| 15 | `ACT_COMP_DATE` | DATS | 8 |  | Actual Completion Date |
| 16 | `COMPLETED_BY` | CHAR | 12 |  | Completed by |
| 17 | `STATUS` | CHAR | 1 |  | Status of Request |
| 18 | `LAST_CHANGE_USER` | CHAR | 12 |  | Name of person who changed object |
| 19 | `LAST_CHANGE_DATE` | DATS | 8 |  | Date of Last Change |
