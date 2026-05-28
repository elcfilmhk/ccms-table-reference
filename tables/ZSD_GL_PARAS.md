# ZSD_GL_PARAS
**Description:** Parameters for G/L Account Posting
**Total Fields:** 12
**Key Fields:** MANDT, VALIDFROM, VALIDTO, PAYMENTMETHOD, CARDTYPE, GLACCOUNT, BANKCHARGE

## Programs Using This Table
- `zissd00106`
- `zissd00116`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VALIDFROM` | DATS | 8 | 🔑 | Valid From |
| 3 | `VALIDTO` | DATS | 8 | 🔑 | Valid To |
| 4 | `PAYMENTMETHOD` | CHAR | 3 | 🔑 | Payment Method |
| 5 | `CARDTYPE` | CHAR | 3 | 🔑 | Card Type |
| 6 | `GLACCOUNT` | CHAR | 10 | 🔑 | GL Account |
| 7 | `BANKCHARGE` | DEC | 15 | 🔑 | Bank Charge |
| 8 | `TRANSACTIONFEE` | DEC | 13 |  | Transaction Fee per transaction |
| 9 | `POSTDATEOFF` | INT2 | 5 |  | Posting Date Offset |
| 10 | `VALUEDATEOFF` | INT2 | 5 |  | Value Date Offset |
| 11 | `POSIT` | NUMC | 1 |  | Position |
| 12 | `REF_KEY` | CHAR | 10 |  | Reference Key Identifier |
