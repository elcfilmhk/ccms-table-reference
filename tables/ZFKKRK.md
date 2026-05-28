# ZFKKRK
**Description:** Transfer structure:Header data (returns lot transfer)
**Total Fields:** 32
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0004`
- `zisfi0024`
- `zisfi0094`
- `zisfi0144`
- `zisfi0174`
- `zisfi0184`
- `zisfi0225`
- `zisfi0257`
- `zisfi0311b`
- `zisfi0312`
- `zisfi0323`
- `zisfi0334`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `STYPE` | CHAR | 1 |  | Record Type for Returns Lot Transfer |
| 2 | `TBNAM` | CHAR | 30 |  | Table Name |
| 3 | `KEYR1` | CHAR | 12 |  | Returns Lot |
| 4 | `KEYR2` | CHAR | 40 |  | Search term for returns lot |
| 5 | `FIKEY` | CHAR | 12 |  | Reconciliation Key for General Ledger |
| 6 | `RLSKO` | CHAR | 10 |  | Bank clearing account for returns |
| 7 | `BUKRS` | CHAR | 4 |  | Company Code |
| 8 | `GSBER` | CHAR | 4 |  | Business Area |
| 9 | `BLART` | CHAR | 2 |  | Document Type |
| 10 | `WAERS` | CUKY | 5 |  | Currency Key |
| 11 | `KURSF` | CHAR | 10 |  | Exchange Rate (Batch Input) |
| 12 | `BUDAT` | CHAR | 8 |  | Posting Date in Document (Batch Input) |
| 13 | `BLDAT` | CHAR | 8 |  | Document date (batch input) |
| 14 | `VALUT` | CHAR | 8 |  | Value date (batch input) |
| 15 | `XEIPH` | CHAR | 1 |  | Create Line Item in General Ledger |
| 16 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 17 | `XRLSD` | CHAR | 1 |  | Lot Contains Returns for Incoming Payments |
| 18 | `XRLSK` | CHAR | 1 |  | Lot Contains Returns for Outgoing Payments |
| 19 | `XSTEB` | CHAR | 1 |  | Bank Charges Include Tax |
| 20 | `XRLSB` | CHAR | 1 |  | Returns Amounts Include Bank Charges |
| 21 | `BANKL` | CHAR | 3 |  | Bank Country Key |
| 22 | `BANKK` | CHAR | 15 |  | Bank Keys |
| 23 | `BANKN` | CHAR | 18 |  | Bank account number |
| 24 | `HBKID` | CHAR | 5 |  | Short key for a house bank |
| 25 | `HKTID` | CHAR | 5 |  | ID for account details |
| 26 | `XCALCGEB` | CHAR | 1 |  | Calculate Charges Automatically |
| 27 | `XACCEPTCHARGES` | CHAR | 1 |  | Returns: Accepting Charges over Tolerance Limit |
| 28 | `RLMOD` | CHAR | 1 |  | Returns Posting Type |
| 29 | `KSUMS` | CHAR | 15 |  | Specified Debit Total (Batch Input) |
| 30 | `KSUMH` | CHAR | 15 |  | Specified Credit Total |
| 31 | `KSUMP` | NUMC | 6 |  | Specified Number of Items |
| 32 | `XERWR` | CHAR | 1 |  | Enhanced Returns Processing |
