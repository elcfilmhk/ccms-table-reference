# ZISFIPROMOTION
**Description:** Table for Eligible customers
**Total Fields:** 10
**Key Fields:** MANDT, PROM_ID, CONT_ACNT, REG_DATE, REG_TIME

## Programs Using This Table
- `zisfi0261`
- `zisfi0262`
- `zisfi0263`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROM_ID` | CHAR | 10 | 🔑 | Promotion ID |
| 3 | `CONT_ACNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `REG_DATE` | DATS | 8 | 🔑 | Registration date |
| 5 | `REG_TIME` | TIMS | 6 | 🔑 | Time |
| 6 | `EMAIL` | CHAR | 241 |  | E-Mail Address |
| 7 | `RATE_CAT` | CHAR | 10 |  | Rate category |
| 8 | `ELIGIBILITY` | CHAR | 1 |  | Eligibility Indicator |
| 9 | `PAYMENT_POST` | CHAR | 1 |  | Payment Posting Indicator |
| 10 | `INCENTIVE_AMT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
