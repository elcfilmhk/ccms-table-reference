# ZISFIRECONB
**Description:** Transfer structure:Item (payment lot transfer)
**Total Fields:** 60
**Key Fields:** MANDT, KEYZ1, INFOF, ZTRANSID

## Programs Using This Table
- `zisfi0313`
- `zisfi0318`
- `zisfi0323`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `KEYZ1` | CHAR | 12 | 🔑 | Payment Lot |
| 3 | `INFOF` | CHAR | 50 | 🔑 | Additional information |
| 4 | `ZTRANSID` | CHAR | 80 | 🔑 | Unique Transaction ID |
| 5 | `STYPE` | CHAR | 1 |  | Record Type for Payment Lot Transfer |
| 6 | `TBNAM` | CHAR | 30 |  | Table Name |
| 7 | `SELT1` | CHAR | 1 |  | Selection Category |
| 8 | `SELT2` | CHAR | 1 |  | Selection Category |
| 9 | `SELT3` | CHAR | 1 |  | Selection Category |
| 10 | `SELW1` | CHAR | 35 |  | Field value to be selected |
| 11 | `SELW2` | CHAR | 35 |  | Field value to be selected |
| 12 | `SELW3` | CHAR | 35 |  | Field value to be selected |
| 13 | `BETRZ` | CHAR | 16 |  | Payment amount in transaction currency (batch input) |
| 14 | `BETRH` | CHAR | 16 |  | Amount In Local Currency With +/- Sign (Batch Input) |
| 15 | `TBETR` | CHAR | 16 |  | Partial Amount that Refers to the Specified Selection |
| 16 | `BVRKO` | CHAR | 10 |  | Bank clearing account |
| 17 | `BUKRS` | CHAR | 4 |  | Company Code |
| 18 | `GSBER` | CHAR | 4 |  | Business Area |
| 19 | `BLART` | CHAR | 2 |  | Document Type |
| 20 | `WAERS` | CUKY | 5 |  | Currency Key |
| 21 | `KURSF` | CHAR | 10 |  | Exchange Rate (Batch Input) |
| 22 | `BUDAT` | CHAR | 8 |  | Posting Date in Document (Batch Input) |
| 23 | `BLDAT` | CHAR | 8 |  | Document date (batch input) |
| 24 | `VALUT` | CHAR | 8 |  | Value date (batch input) |
| 25 | `XEIPH` | CHAR | 1 |  | Create Line Item in General Ledger |
| 26 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 27 | `XAKON` | CHAR | 1 |  | Post Payment on Account |
| 28 | `XKLAE` | CHAR | 1 |  | Clarify Payment Transaction |
| 29 | `KLAEH` | CHAR | 10 |  | Clarification Account |
| 30 | `TXTVW` | CHAR | 80 |  | Note to Payee in Payment |
| 31 | `CHCKN` | CHAR | 13 |  | Check number |
| 32 | `BANKS` | CHAR | 3 |  | Bank Country Key |
| 33 | `BANKL` | CHAR | 15 |  | Bank number |
| 34 | `BANKN` | CHAR | 18 |  | Bank account number |
| 35 | `BKONT` | CHAR | 2 |  | Bank Control Key |
| 36 | `KOINH` | CHAR | 60 |  | Name of Holder of Bank Account/Check Issuer/Cardholder |
| 37 | `XPGRO` | CHAR | 1 |  | Post Office Bank Current Account |
| 38 | `XDAUB` | CHAR | 1 |  | Payment by Standing Order |
| 39 | `KUKON` | CHAR | 4 |  | Short Account Assignment for Transfer Postings |
| 40 | `BKREF` | CHAR | 20 |  | Reference specifications for bank details |
| 41 | `CCINS` | CHAR | 4 |  | Payment card type |
| 42 | `CCNUM` | CHAR | 25 |  | Payment cards: Card number |
| 43 | `DATAB` | CHAR | 8 |  | Payment Cards: Valid From (Batch Input) |
| 44 | `DATBI` | CHAR | 8 |  | Payment Cards: Valid To (Batch Input) |
| 45 | `AUNUM` | CHAR | 25 |  | Payment cards: Authorization number |
| 46 | `AUDAT` | CHAR | 8 |  | Payment Cards: Date of Authorization (Batch Input) |
| 47 | `AUTIM` | CHAR | 6 |  | Payment Cards: Time of Authorization (Batch Input) |
| 48 | `ZFILLER` | CHAR | 74 |  | FILLER |
| 49 | `ZREFKEY1` | CHAR | 30 |  | Reference key1 |
| 50 | `ZREFKEY2` | CHAR | 30 |  | Reference key2 |
| 51 | `ZSCANCODE` | CHAR | 30 |  | Indicator of QR code and bar code |
| 52 | `ZPAYPOINT` | CHAR | 30 |  | Point of payment |
| 53 | `ZYOURREF` | CHAR | 40 |  | Counter Party Reference |
| 54 | `ZPAYMEDIA` | CHAR | 30 |  | Means of Payment |
| 55 | `ZBILLTYPE` | NUMC | 2 |  | Bill Type |
| 56 | `ZTXINDCATOR` | NUMC | 2 |  | Transaction indicator |
| 57 | `ZSERVFEEIND` | CHAR | 2 |  | Transaction fee indicator |
| 58 | `ZPROCIND` | CHAR | 1 |  | Recon Process Indicator |
| 59 | `ZRECONDATE` | DATS | 8 |  | Recon Date |
| 60 | `ZTRANSTIME` | TIMS | 6 |  | Transaction Time |
