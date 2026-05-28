# ZISFIDDA_EXT
**Description:** Direct Debit Application
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0014`
- `zisfi0237`
- `zisfi0248`
- `zisfi0279`
- `ztest_zisfi0248`
- `ztest_zisfi0279`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SOURCE` | CHAR | 1 |  | Source (P = Phone, O = Online) |
| 2 | `DEBTOR_REF` | CHAR | 12 |  | Contract Account Number |
| 3 | `BANK_KEY` | CHAR | 15 |  | Bank Keys |
| 4 | `BANK_NUMBER` | CHAR | 36 |  | Bank account |
| 5 | `SEQUENCE` | NUMC | 2 |  | Sequence number |
| 6 | `ACCT_HOLDER` | CHAR | 140 |  | Account Holder Name 1 & 2 for DDA registration |
| 7 | `ID_TYPE` | CHAR | 6 |  | Identification Type |
| 8 | `ID_NUMBER` | CHAR | 60 |  | Identification Number |
| 9 | `UDATE` | DATS | 8 |  | Creation date of the change document |
| 10 | `UTIME` | TIMS | 6 |  | Time changed |
