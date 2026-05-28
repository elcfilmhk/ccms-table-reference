# ZISFIADRTEMPL
**Description:** ZDR09 - DR Invoice Upload Template Update
**Total Fields:** 35
**Key Fields:** MANDT, SEQ_NO, ITEM

## Programs Using This Table
- `zisfi0249_dnld`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SEQ_NO` | INT1 | 3 | 🔑 | Sequence number |
| 3 | `ITEM` | CHAR | 2 | 🔑 | Item |
| 4 | `DOC_DATE` | CHAR | 8 |  | Document Date |
| 5 | `POST_DATE` | CHAR | 8 |  | Posting Date |
| 6 | `CO_CODE1` | CHAR | 4 |  | Company Code |
| 7 | `DOC_TYPE` | CHAR | 2 |  | Document type |
| 8 | `REF` | CHAR | 16 |  | Ref |
| 9 | `DOC_HDR_TXT` | CHAR | 25 |  | Doc Header Text |
| 10 | `CURRENCY` | CHAR | 3 |  | Currency |
| 11 | `EX_RATE` | CHAR | 9 |  | Exchange Rate |
| 12 | `POST_KEY` | CHAR | 2 |  | Posting Key |
| 13 | `CO_CODE2` | CHAR | 4 |  | Company Code |
| 14 | `BUSI_AREA` | CHAR | 4 |  | Business Area |
| 15 | `GL_ACCT` | CHAR | 10 |  | General ledger account |
| 16 | `DOC_AMT` | CHAR | 16 |  | Document Curr Amt |
| 17 | `LOC_AMT` | CHAR | 16 |  | Local Curr Amt |
| 18 | `COST_CENTRE` | CHAR | 10 |  | Cost Centre |
| 19 | `ORDER_NUM` | CHAR | 12 |  | Order number |
| 20 | `WBS` | CHAR | 24 |  | WBS |
| 21 | `PLANT` | CHAR | 4 |  | Plant |
| 22 | `TRADE_PARTNER` | CHAR | 6 |  | Trading Partner |
| 23 | `ASSIGN_NR` | CHAR | 18 |  | Assignment number |
| 24 | `LINE_ITEM_TXT` | CHAR | 50 |  | Line item text |
| 25 | `PAY_TERM` | CHAR | 4 |  | Payment term |
| 26 | `PAY_METH` | CHAR | 1 |  | Payment Method |
| 27 | `BSLN_DATE` | CHAR | 8 |  | Baseline Date |
| 28 | `VENDOR_NAME1` | CHAR | 35 |  | Vendor Name 1 |
| 29 | `VENDOR_NAME2` | CHAR | 35 |  | Vendor Name 2 |
| 30 | `VENDOR_STR` | CHAR | 35 |  | Vendor Street |
| 31 | `VENDOR_CITY` | CHAR | 35 |  | Vendor City |
| 32 | `VENDOR_CN` | CHAR | 3 |  | Vendor Country |
| 33 | `BANK_KEY` | CHAR | 3 |  | Bank country key (Onetime) |
| 34 | `BANK_NUM` | CHAR | 15 |  | Bank number (Onetime) |
| 35 | `BANK_ACCT` | CHAR | 18 |  | Bank account number (Onetime) |
