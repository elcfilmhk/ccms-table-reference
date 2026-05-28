# ZISFI_PROMOTION
**Description:** Master Table for Promotions
**Total Fields:** 13
**Key Fields:** MANDT, PROMO_ID, VALID_FROM, VALID_TO, RATE_CATEGORY, PAYMENT_SELECTED

## Programs Using This Table
- `zisfi0263`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROMO_ID` | CHAR | 10 | 🔑 | Promotion ID |
| 3 | `VALID_FROM` | DATS | 8 | 🔑 | Promotion Valid From Date |
| 4 | `VALID_TO` | DATS | 8 | 🔑 | Promotion Valid To Date |
| 5 | `RATE_CATEGORY` | CHAR | 10 | 🔑 | Rate category |
| 6 | `PAYMENT_SELECTED` | CHAR | 2 | 🔑 | Document Type |
| 7 | `PAY_AMOUNT` | CURR | 13 |  | Payment Amount |
| 8 | `INC_AMOUNT` | CURR | 13 |  | Incentive Amount |
| 9 | `WAERS` | CUKY | 5 |  | Currency Key |
| 10 | `NO_OF_PAYMENTS` | NUMC | 10 |  | Number of Payments |
| 11 | `NO_OF_CUSTOMERS` | NUMC | 10 |  | Number of Customers |
| 12 | `DEL_IND` | CHAR | 1 |  | Deletion Indicator |
| 13 | `PAYMENT_METHOD` | CHAR | 1 |  | Incoming Payment Method |
