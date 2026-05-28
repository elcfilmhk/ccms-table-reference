# ZISFIRTPMTRECONB
**Description:** Transfer structure:Item (payment lot transfer)
**Total Fields:** 56
**Key Fields:** MANDT, KEYZ1, INFOF

## Programs Using This Table
- `zisfi0311b`
- `zisfi0312`
- `zisfi0313`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `KEYZ1` | CHAR | 12 | 🔑 | Payment Lot |
| 3 | `INFOF` | CHAR | 50 | 🔑 | Additional information |
| 4 | `STYPE` | CHAR | 1 |  | Record Type for Payment Lot Transfer |
| 5 | `TBNAM` | CHAR | 30 |  | Table Name |
| 6 | `SELT1` | CHAR | 1 |  | Selection Category |
| 7 | `SELT2` | CHAR | 1 |  | Selection Category |
| 8 | `SELT3` | CHAR | 1 |  | Selection Category |
| 9 | `SELW1` | CHAR | 35 |  | Field value to be selected |
| 10 | `SELW2` | CHAR | 35 |  | Field value to be selected |
| 11 | `SELW3` | CHAR | 35 |  | Field value to be selected |
| 12 | `BETRZ` | CHAR | 16 |  | Payment amount in transaction currency (batch input) |
| 13 | `BETRH` | CHAR | 16 |  | Amount In Local Currency With +/- Sign (Batch Input) |
| 14 | `TBETR` | CHAR | 16 |  | Partial Amount that Refers to the Specified Selection |
| 15 | `BVRKO` | CHAR | 10 |  | Bank clearing account |
| 16 | `BUKRS` | CHAR | 4 |  | Company Code |
| 17 | `GSBER` | CHAR | 4 |  | Business Area |
| 18 | `BLART` | CHAR | 2 |  | Document Type |
| 19 | `WAERS` | CUKY | 5 |  | Currency Key |
| 20 | `KURSF` | CHAR | 10 |  | Exchange Rate (Batch Input) |
| 21 | `BUDAT` | CHAR | 8 |  | Posting Date in Document (Batch Input) |
| 22 | `BLDAT` | CHAR | 8 |  | Document date (batch input) |
| 23 | `VALUT` | CHAR | 8 |  | Value date (batch input) |
| 24 | `XEIPH` | CHAR | 1 |  | Create Line Item in General Ledger |
| 25 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 26 | `XAKON` | CHAR | 1 |  | Post Payment on Account |
| 27 | `XKLAE` | CHAR | 1 |  | Clarify Payment Transaction |
| 28 | `KLAEH` | CHAR | 10 |  | Clarification Account |
| 29 | `TXTVW` | CHAR | 80 |  | Note to Payee in Payment |
| 30 | `CHCKN` | CHAR | 13 |  | Check number |
| 31 | `BANKS` | CHAR | 3 |  | Bank Country Key |
| 32 | `BANKL` | CHAR | 15 |  | Bank number |
| 33 | `BANKN` | CHAR | 18 |  | Bank account number |
| 34 | `BKONT` | CHAR | 2 |  | Bank Control Key |
| 35 | `KOINH` | CHAR | 60 |  | Name of Holder of Bank Account/Check Issuer/Cardholder |
| 36 | `XPGRO` | CHAR | 1 |  | Post Office Bank Current Account |
| 37 | `XDAUB` | CHAR | 1 |  | Payment by Standing Order |
| 38 | `KUKON` | CHAR | 4 |  | Short Account Assignment for Transfer Postings |
| 39 | `BKREF` | CHAR | 20 |  | Reference specifications for bank details |
| 40 | `CCINS` | CHAR | 4 |  | Payment card type |
| 41 | `CCNUM` | CHAR | 25 |  | Payment cards: Card number |
| 42 | `DATAB` | CHAR | 8 |  | Payment Cards: Valid From (Batch Input) |
| 43 | `DATBI` | CHAR | 8 |  | Payment Cards: Valid To (Batch Input) |
| 44 | `AUNUM` | CHAR | 25 |  | Payment cards: Authorization number |
| 45 | `AUDAT` | CHAR | 8 |  | Payment Cards: Date of Authorization (Batch Input) |
| 46 | `AUTIM` | CHAR | 6 |  | Payment Cards: Time of Authorization (Batch Input) |
| 47 | `ZFILLER` | CHAR | 74 |  | FILLER |
| 48 | `ZREFKEY1` | CHAR | 30 |  | Reference key1 |
| 49 | `ZREFKEY2` | CHAR | 30 |  | Reference key2 |
| 50 | `ZSCANCODE` | CHAR | 30 |  | Indicator of QR code and bar code |
| 51 | `ZPAYPOINT` | CHAR | 30 |  | Point of payment |
| 52 | `ZYOURREF` | CHAR | 40 |  | Counter Party Reference |
| 53 | `ZPAYMEDIA` | CHAR | 30 |  | Means of Payment |
| 54 | `ZBILLTYPE` | NUMC | 2 |  | Bill Type |
| 55 | `ZTXINDCATOR` | NUMC | 2 |  | Transaction indicator |
| 56 | `ZSERVFEEIND` | CHAR | 2 |  | Transaction fee indicator |
