# ZISFIDUNOUTLIST
**Description:** Dunning Outbound Target List
**Total Fields:** 25
**Key Fields:** MANDT, RUN_ID, VKONT

## Programs Using This Table
- `zisfi0146`
- `zisfi0148`
- `zisfi0151`
- `zisfi0152`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUN_ID` | NUMC | 8 | 🔑 | Run ID |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `RUN_DATE` | DATS | 8 |  | Batch run date |
| 5 | `CALLED_BY` | CHAR | 10 |  | Agent ID |
| 6 | `CALL_DATE` | DATS | 8 |  | Call Date |
| 7 | `DURATION` | TIMS | 6 |  | Call Duration |
| 8 | `RATE_CATEGORY` | CHAR | 10 |  | Rate category |
| 9 | `SEGMENT` | CHAR | 1 |  | Segment label |
| 10 | `TRADE_CLASS` | CHAR | 4 |  | Account class |
| 11 | `CREDIT_SCORE` | NUMC | 4 |  | Credit Score |
| 12 | `TOTAL_OS_BAL` | CURR | 17 |  | Total outstanding balance |
| 13 | `DUN_LEVEL` | NUMC | 2 |  | Dunning Level |
| 14 | `ISSUE_DATE` | DATS | 8 |  | Date of issue |
| 15 | `DUE_DATE` | DATS | 8 |  | Warning bill due date |
| 16 | `DEPOSIT_HELD` | CURR | 17 |  | Deposit held |
| 17 | `DELIVERY_METHOD` | CHAR | 20 |  | Delivery Method |
| 18 | `REMAINDED` | CHAR | 1 |  | Reminded |
| 19 | `PAID` | CHAR | 1 |  | Paid |
| 20 | `WRONG_NO` | CHAR | 1 |  | Wrong Number Flag |
| 21 | `NO_BODY_ANS` | CHAR | 1 |  | No Body Answer Flag |
| 22 | `NOT_REG_CUST` | CHAR | 1 |  | Not a Registered Customer Flag |
| 23 | `OTHERS` | CHAR | 1 |  | Other Reasons Flag |
| 24 | `NO_BODY_ANS_TIME` | DEC | 3 |  | No Body Answer Times |
| 25 | `REC_LOCK` | CHAR | 1 |  | Record Lock |
