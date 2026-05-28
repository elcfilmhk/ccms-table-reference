# ZISSDRBSBONSUM
**Description:** Residential Bonus Scheme Bonus Summary
**Total Fields:** 17
**Key Fields:** MANDT, SCHNO, INSTM

## Programs Using This Table
- `zisfi0247`
- `zissd00074`
- `zissd00076`
- `zissd00077`
- `zissd00105`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SCHNO` | CHAR | 10 | 🔑 | Bonus Scheme Number |
| 3 | `INSTM` | CHAR | 4 | 🔑 | Bonus installment |
| 4 | `SCHBD` | DATS | 8 |  | Scheduled billing date |
| 5 | `ELIBA` | CURR | 13 |  | Eligible bonus amount |
| 6 | `ACTPD` | DATS | 8 |  | Actual posting date |
| 7 | `ACTBA` | CURR | 13 |  | Actual bonus amount |
| 8 | `CONSM` | CURR | 13 |  | Consumption |
| 9 | `BILFR` | DATS | 8 |  | Billing period from |
| 10 | `BILTO` | DATS | 8 |  | Billing period to |
| 11 | `RELUA` | CHAR | 1 |  | Released upon approval |
| 12 | `ORGPD` | DATS | 8 |  | Original posting date |
| 13 | `CRDAT` | DATS | 8 |  | Creation date |
| 14 | `CRUSR` | CHAR | 12 |  | Created By |
| 15 | `LCDAT` | DATS | 8 |  | Last change date |
| 16 | `LCUSR` | CHAR | 12 |  | Last change by |
| 17 | `FICADOC` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
