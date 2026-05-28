# ZISBIBBGEN
**Description:** Budget Billing Plan Contract Information
**Total Fields:** 15
**Key Fields:** MANDT, CONTRACT_ACCT, PAYMENT_PLAN

## Programs Using This Table
- `zisbi0108`
- `zisbi0111`
- `zisbi0112`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONTRACT_ACCT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `PAYMENT_PLAN` | CHAR | 12 | 🔑 | Budget billing plan |
| 4 | `AGREED_ANN_CONSU` | DEC | 17 |  | Agreed Annual Consumption |
| 5 | `UNIT_RATE` | DEC | 17 |  | Unit Rate |
| 6 | `SETTLE_DELTA_DR` | CHAR | 1 |  | Option for settlement the delta debit balance |
| 7 | `REBATE_AMT` | CURR | 13 |  | Rebate Amount |
| 8 | `ROUND_DOWN_AMT` | CURR | 13 |  | Round Down Amount |
| 9 | `CF_INSTALLMT_AMT` | CURR | 13 |  | Carried Forward Installment Amount |
| 10 | `INSTALLMT_PERIOD` | CURR | 13 |  | Installment per period |
| 11 | `BILL_FORM` | CHAR | 1 |  | Bill form |
| 12 | `UPLOAD_DATE` | DATS | 8 |  | Upload Date |
| 13 | `CREATED_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `PRINT_DOC` | CHAR | 12 |  | Number of print document |
| 15 | `FICA_DOC_PT_DATE` | DATS | 8 |  | FI-CA Document Posting Date |
