# ZFKKRP
**Description:** Transfer structure:Payment Data (Return Lot Transfer)
**Total Fields:** 47
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
- `zisfi0334`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `STYPE` | CHAR | 1 |  | Record Type for Returns Lot Transfer |
| 2 | `TBNAM` | CHAR | 30 |  | Table Name |
| 3 | `SELT1` | CHAR | 1 |  | Selection Category |
| 4 | `SELW1` | CHAR | 20 |  | Field value to be selected |
| 5 | `BETRR` | CHAR | 16 |  | Return amount |
| 6 | `BETRH` | CHAR | 16 |  | Amount In Local Currency With +/- Sign (Batch Input) |
| 7 | `BTRB1` | CHAR | 16 |  | Charge amount from bank 1 |
| 8 | `BTRB2` | CHAR | 16 |  | Charge amount from bank 2 |
| 9 | `BTRV1` | CHAR | 16 |  | Returns Charge 1 |
| 10 | `BTRV2` | CHAR | 16 |  | Return charge 2 |
| 11 | `STBB1` | CHAR | 16 |  | Tax Amount: Bank Charge 1 |
| 12 | `STBB2` | CHAR | 16 |  | Tax amount: Bank charge 2 |
| 13 | `STBV1` | CHAR | 16 |  | Tax amount: Return charges 1 |
| 14 | `STBV2` | CHAR | 16 |  | Tax amount: Return charges 2 |
| 15 | `SKZB1` | CHAR | 2 |  | Tax Code: Bank Charge 1 |
| 16 | `SKZB2` | CHAR | 2 |  | Tax Code from Bank 2 |
| 17 | `SKZV1` | CHAR | 2 |  | Tax Code: Returns Charge 1 |
| 18 | `SKZV2` | CHAR | 2 |  | Tax Code for Return Fees 2 |
| 19 | `RLSKO` | CHAR | 10 |  | Bank clearing account for returns |
| 20 | `BUKRS` | CHAR | 4 |  | Company Code |
| 21 | `GSBER` | CHAR | 4 |  | Business Area |
| 22 | `BLART` | CHAR | 2 |  | Document Type |
| 23 | `WAERS` | CUKY | 5 |  | Currency Key |
| 24 | `KURSF` | CHAR | 10 |  | Exchange Rate (Batch Input) |
| 25 | `BUDAT` | CHAR | 8 |  | Posting Date in Document (Batch Input) |
| 26 | `BLDAT` | CHAR | 8 |  | Document date (batch input) |
| 27 | `VALUT` | CHAR | 8 |  | Value date (batch input) |
| 28 | `XEIPH` | CHAR | 1 |  | Create Line Item in General Ledger |
| 29 | `RLGRD` | CHAR | 3 |  | Return Reason |
| 30 | `RLHBK` | CHAR | 6 |  | House bank's return reason |
| 31 | `TXTVW` | CHAR | 80 |  | Note to Payee in Payment |
| 32 | `BANKL` | CHAR | 3 |  | Banking Country of Business Partner |
| 33 | `BANKK` | CHAR | 15 |  | Business Partner Bank Number |
| 34 | `BANKN` | CHAR | 18 |  | Account Number of Business Partner |
| 35 | `IBAN` | CHAR | 34 |  | IBAN (International Bank Account Number) |
| 36 | `CHECF` | CHAR | 16 |  | Number of a returned check |
| 37 | `XACCEPTCHARGES` | CHAR | 1 |  | Returns: Accepting Charges over Tolerance Limit |
| 38 | `HBKID` | CHAR | 5 |  | Short key for a house bank |
| 39 | `HKTID` | CHAR | 5 |  | ID for account details |
| 40 | `RLMOD` | CHAR | 1 |  | Returns Posting Type |
| 41 | `XERWR` | CHAR | 1 |  | Enhanced Returns Processing |
| 42 | `PRCTR` | CHAR | 10 |  | Profit Center |
| 43 | `KUKEY` | CHAR | 8 |  | Short Key (Surrogate) |
| 44 | `ESNUM` | CHAR | 5 |  | Single Record Number (Line Item Number in Account Statement) |
| 45 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 46 | `SWIFT` | CHAR | 11 |  | SWIFT/BIC for International Payments |
| 47 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
