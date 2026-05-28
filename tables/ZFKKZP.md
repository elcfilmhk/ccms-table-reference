# ZFKKZP
**Description:** Transfer structure:Item (payment lot transfer)
**Total Fields:** 52
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0015`
- `zisfi0023`
- `zisfi0133`
- `zisfi0160`
- `zisfi0163`
- `zisfi0196`
- `zisfi0209`
- `zisfi0222`
- `zisfi0233`
- `zisfi0252`
- `zisfi0318`
- `zisfi0323`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `STYPE` | CHAR | 1 |  | Record Type for Payment Lot Transfer |
| 2 | `TBNAM` | CHAR | 30 |  | Table Name |
| 3 | `SELT1` | CHAR | 1 |  | Selection Category |
| 4 | `SELT2` | CHAR | 1 |  | Selection Category |
| 5 | `SELT3` | CHAR | 1 |  | Selection Category |
| 6 | `SELW1` | CHAR | 35 |  | Field value to be selected |
| 7 | `SELW2` | CHAR | 35 |  | Field value to be selected |
| 8 | `SELW3` | CHAR | 35 |  | Field value to be selected |
| 9 | `BETRZ` | CHAR | 16 |  | Payment amount in transaction currency (batch input) |
| 10 | `BETRH` | CHAR | 16 |  | Amount In Local Currency With +/- Sign (Batch Input) |
| 11 | `TBETR` | CHAR | 16 |  | Partial Amount that Refers to the Specified Selection |
| 12 | `BVRKO` | CHAR | 10 |  | Bank clearing account |
| 13 | `BUKRS` | CHAR | 4 |  | Company Code |
| 14 | `GSBER` | CHAR | 4 |  | Business Area |
| 15 | `BLART` | CHAR | 2 |  | Document Type |
| 16 | `WAERS` | CUKY | 5 |  | Currency Key |
| 17 | `KURSF` | CHAR | 10 |  | Exchange Rate (Batch Input) |
| 18 | `BUDAT` | CHAR | 8 |  | Posting Date in Document (Batch Input) |
| 19 | `BLDAT` | CHAR | 8 |  | Document date (batch input) |
| 20 | `VALUT` | CHAR | 8 |  | Value date (batch input) |
| 21 | `XEIPH` | CHAR | 1 |  | Create Line Item in General Ledger |
| 22 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 23 | `XAKON` | CHAR | 1 |  | Post Payment on Account |
| 24 | `XKLAE` | CHAR | 1 |  | Clarify Payment Transaction |
| 25 | `KLAEH` | CHAR | 10 |  | Clarification Account |
| 26 | `TXTVW` | CHAR | 80 |  | Note to Payee in Payment |
| 27 | `CHCKN` | CHAR | 13 |  | Check number |
| 28 | `BANKS` | CHAR | 3 |  | Bank Country Key |
| 29 | `BANKL` | CHAR | 15 |  | Bank number |
| 30 | `BANKN` | CHAR | 18 |  | Bank account number |
| 31 | `BKONT` | CHAR | 2 |  | Bank Control Key |
| 32 | `KOINH` | CHAR | 60 |  | Name of Holder of Bank Account/Check Issuer/Cardholder |
| 33 | `XPGRO` | CHAR | 1 |  | Post Office Bank Current Account |
| 34 | `XDAUB` | CHAR | 1 |  | Payment by Standing Order |
| 35 | `INFOF` | CHAR | 50 |  | Additional information |
| 36 | `KUKON` | CHAR | 4 |  | Short Account Assignment for Transfer Postings |
| 37 | `BKREF` | CHAR | 20 |  | Reference specifications for bank details |
| 38 | `CCINS` | CHAR | 4 |  | Payment card type |
| 39 | `CCNUM` | CHAR | 25 |  | Payment cards: Card number |
| 40 | `DATAB` | CHAR | 8 |  | Payment Cards: Valid From (Batch Input) |
| 41 | `DATBI` | CHAR | 8 |  | Payment Cards: Valid To (Batch Input) |
| 42 | `AUNUM` | CHAR | 25 |  | Payment cards: Authorization number |
| 43 | `AUDAT` | CHAR | 8 |  | Payment Cards: Date of Authorization (Batch Input) |
| 44 | `AUTIM` | CHAR | 6 |  | Payment Cards: Time of Authorization (Batch Input) |
| 45 | `PRCTR` | CHAR | 10 |  | Profit Center |
| 46 | `BEGRU` | CHAR | 4 |  | Authorization Group |
| 47 | `MERCH` | CHAR | 15 |  | Payment cards: Merchant ID at the clearing house |
| 48 | `IBAN` | CHAR | 34 |  | IBAN (International Bank Account Number) |
| 49 | `SWIFT` | CHAR | 11 |  | SWIFT Code/Bank Identifier Code (BIC) |
| 50 | `ESNUM` | CHAR | 5 |  | Single Record Number (Line Item Number in Account Statement) |
| 51 | `.INCLUDE` | &nbsp; | 0 |  | Transaction ID |
| 52 | `ZZTRANSID` | CHAR | 80 |  | Unique Transaction ID |
