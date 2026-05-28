# ZNEWEFTDETAILS
**Description:** New Autopay subscription
**Total Fields:** 8
**Key Fields:** MANDT, BP, ACCT, MO

## Programs Using This Table
- `ziscs0184`
- `ziscs0298`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BP` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `ACCT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `MO` | DATS | 8 | 🔑 | Move-Out Date |
| 5 | `BANKKEY` | CHAR | 15 |  | Bank Keys |
| 6 | `BANKACCT` | CHAR | 18 |  | Bank account number |
| 7 | `ACCTHOLDER` | CHAR | 60 |  | Account Holder Name |
| 8 | `STATUS` | CHAR | 1 |  | Update Status |
