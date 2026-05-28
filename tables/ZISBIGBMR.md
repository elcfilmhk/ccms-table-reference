# ZISBIGBMR
**Description:** Store Group Bill Data for Group Bill Management Report
**Total Fields:** 35
**Key Fields:** MANDT, GROUP_ACCT_NO, SERV_ACCT_NO, BILL_ISSUED_DATE

## Programs Using This Table
- `zisbi0204`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GROUP_ACCT_NO` | CHAR | 12 | 🔑 | Alternative contract account for collective bills |
| 3 | `SERV_ACCT_NO` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `BILL_ISSUED_DATE` | DATS | 8 | 🔑 | Posting Date in the Document |
| 5 | `CUSTREF` | CHAR | 35 |  | Contract Account Name |
| 6 | `BILL_TYPE` | CHAR | 9 |  | Bill Type (Normal, Amend, Final) |
| 7 | `TRIF_TYPE` | CHAR | 10 |  | Rate category |
| 8 | `ACCTG_NAME` | CHAR | 35 |  | Contract Account Name |
| 9 | `ACCT_ADDR1` | CHAR | 40 |  | Address line 1 |
| 10 | `ACCT_ADDR2` | CHAR | 40 |  | Address line 2 |
| 11 | `ACCT_ADDR3` | CHAR | 40 |  | Address line 3 |
| 12 | `ACCT_ADDR4` | CHAR | 40 |  | Address line 4 |
| 13 | `ACCT_ADDR5` | CHAR | 40 |  | Address line 5 |
| 14 | `PREV_RDG_DATE` | DATS | 8 |  | Group Bill Text File Previous Reading Date |
| 15 | `CURR_RDG_DATE` | DATS | 8 |  | Current Reading Date |
| 16 | `CURR_MTH_CHRG` | CURR | 13 |  | Group Bill Management Report: Current Month Charge |
| 17 | `CURR_TOT_CHRG` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 18 | `CURR_MTH_KWH_ON` | DEC | 31 |  | Billing quantity for internal billing format |
| 19 | `CURR_MTH_KWH_OFF` | DEC | 31 |  | Billing quantity for internal billing format |
| 20 | `PREV_BILLING_ADJ` | CURR | 13 |  | Net amount of billing line item |
| 21 | `CSMP_ADJ1` | DEC | 31 |  | Billing quantity for internal billing format |
| 22 | `CSMP_ADJ2` | DEC | 31 |  | Billing quantity for internal billing format |
| 23 | `GROUP_BILL_PD` | CHAR | 12 |  | Number of print document |
| 24 | `BP_NUMBER` | CHAR | 10 |  | Business Partner Number |
| 25 | `NAME1` | CHAR | 40 |  | Name 1 of organization |
| 26 | `NAME2` | CHAR | 40 |  | Name 2 of organization |
| 27 | `NAME4` | CHAR | 40 |  | Name 4 of organization |
| 28 | `OPT_IN` | NUMC | 1 |  | Opt-in Flag for Group Bill Management Report |
| 29 | `REVERSED` | CHAR | 1 |  | Group Bill Management Report: Reversal Flag |
| 30 | `CREATED_DATE` | DATS | 8 |  | Group Bill Management Report: Creation Date |
| 31 | `CREATED_TIME` | TIMS | 6 |  | Group Bill Management Report: Creation Time |
| 32 | `CREATED_BY` | CHAR | 12 |  | Group Bill Management Report: Created By |
| 33 | `LAST_MODIFIED_DATE` | DATS | 8 |  | Group Bill Management Report: Updated On |
| 34 | `LAST_MODIFIED_TIME` | TIMS | 6 |  | Group Bill Management Report: Updated Time |
| 35 | `LAST_MODIFIED_BY` | CHAR | 12 |  | Group Bill Management Report: Updated By |
